#python 3.7.1
def ip2int(ip):
    try:
        oc = [int(e) for e in ip.split(".")]
        if len(oc)!=4: raise IndexError
        for o in oc:
            if o<0 or o>255: 
                raise ValueError
        n = oc[0]<<24 | oc[1]<<16 | oc[2]<<8 | oc[3]
    except Exception as e:
        raise ValueError("invalid IP: A.B.C.D 0<=octet<=255")
    else:
        return n

def int2ip(n):
    try:
        if n<0 or n>4294967295 : raise ValueError
        ip = str(n>>24 & 255)
        ip += "." + str(n>>16 & 255)
        ip += "." + str(n>>8 & 255)
        ip += "." + str(n & 255)
    except Exception as e:
        raise ValueError("number must be integer between 0 to 4,294,967,295")
    else:
        return ip

def cidr2int(s):
    n = 0
    try:
        if s<8 or s>32: raise ValueError
        for i in range(32-s,32): n |= 1<<i
    except Exception as e:
        raise ValueError("number must be integer between 8 to 32 ")
    else:
        return n

def getnetid(ipn, netmask):
    return ipn & netmask

def getbroadcast(netid, netmask):
    return 4294967295 ^ netmask | netid

ip, cidr = (e.strip() for e in input("Enter Your IP (A.B.C.D/N):").split("/"))
cidr = int(cidr)
ipn = ip2int(ip)
netmask = cidr2int(cidr)
netid = getnetid(ipn, netmask)
broadcast = getbroadcast(netid, netmask)
firstip = netid+1
lastip = broadcast-1

print("Net ID       :", int2ip(netid))
print("Netmask      :", int2ip(netmask))
print("BroadCast IP :", int2ip(broadcast))
print("First IP     :", int2ip(firstip))
print("Last IP      :", int2ip(lastip))
