<html>
 <head> 
  <script src="https://code.jquery.com/jquery-3.1.1.min.js"></script> 
  <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js"></script> 
  <script src="https://cdn.jsdelivr.net/npm/jquery-ui-touch-punch@0.2.3/jquery.ui.touch-punch.min.js"></script> 
  <script src="https://html2canvas.hertzen.com/dist/html2canvas.min.js"></script> 
 </head> 
 <body id="windows-container" class="aero-3"> 
  <div id="logon"> 
   <div id="logon-wrapper"> 
    <div id="user"> 
     <img src="https://i.imgur.com/8rv47SC.jpg" width="100"> 
    </div> 
    <div id="name">
      Pupul the decoder 
    </div> 
    <div id="input"> 
     <input type="text" id="password" placeholder="Pin" autofocus> 
     <div class="butt on round" id="start">
       ➜ 
     </div> 
    </div> 
   </div> 
  </div> 
  <div id="windows"> 
   <div id="desktop"> 
    <div id="desktop-menu"> 
     <div class="menu-item has-sub">
       View 
      <div class="sub-menu"> 
       <div class="menu-item ico-size" data-size="lg">
         Large icons 
       </div> 
       <div class="menu-item ico-size active" data-size="md">
         Medium icons 
       </div> 
       <div class="menu-item ico-size" data-size="sm">
         Small icons 
       </div> 
       <hr> 
       <div class="menu-item ico-hide active">
         Show desktop icon 
       </div> 
      </div> 
     </div> 
     <div class="menu-item refresh" id="refresh">
       Refresh 
     </div> 
     <div class="menu-item folder" id="new-folder">
       New folder 
     </div> 
     <div class="menu-item personal" data-toggle="window" data-target="#window-personal">
       Personalize 
     </div> 
    </div> 
    <div class="icons icons-md"> 
     <div class="column"> 
      <div class="icon bin" data-toggle="window" data-target="#window-bin"> <label>Recycle Bin</label> 
      </div> 
      <div class="icon computer" data-toggle="window" data-target="#window-computer"> <label>My PC</label> 
      </div> 
      <div class="icon ie" data-toggle="window" data-target="#window-ie"> <label> firefox</label> 
      </div> 
     </div> 
    </div> 
    <div class="window" id="window-about"> 
     <div class="titlebar"> 
      <div class="title about">
        About 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-about">
         – 
       </div> 
       <div class="control maximize" data-target="#window-about">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-about">
         × 
       </div> 
      </div> 
     </div> 
     <div class="container"> 
      <h2> Windows 7<sup class="text-50 text-normal">®</sup> 7 <small class="text-normal">emulator</small> </h2> 
      <p class="text-center text-75">version 2.0</p> 
      <p>Components:</p> 
      <ul> 
       <li>HTML</li> 
       <li>CSS</li> 
       <li>JS</li> 
      </ul> 
      <p>Libraries</p> 
      <ul> 
       <li>jQuery</li> 
       <li>jQueryUI</li> 
       <li>jQueryUI Touch Punch</li> 
       <li>html2canvas</li> 
      </ul> 
      <p>Functional features:</p> 
      <ul> 
       <li>Windows GUI</li> 
       <li>User log on/log off</li> 
       <li>Windows (open, close, minimize, maximize, move)</li> 
       <li>Recycle Bin (UI)</li> 
       <li>My Computer (UI)</li> 
       <li>Calculator (Standard)</li> 
       <li>Internet Explorer (Browse, Search Bing)</li> 
       <li>Desktop Menu (View, Refresh, New Folder, Personalize) - hold your finger to open</li> 
       <li>Personalize (Aero themes, Basic themes)</li> 
       <li>Notepad (File, Edit, Format)</li> 
       <li>Snipping Tool (Rectangular, Full-screen)</li> 
       <li>can be used as an permanent os system for any device as long as you are connected to the internet</li> 
       <li>it tells whether you are connected to the internet using api javascript </li> 
       <li>update will be every week can also visit my other emulator which is for pc and is <br>based on andriod </li> 
      </ul> 
      <div class="text-center"> 
       <p>© 2019 - <a>shamil</a></p> 
       <p>Do not copy without permission</p> 
      </div> 
     </div> 
    </div> 
    <div class="window" id="window-calc"> 
     <div class="titlebar"> 
      <div class="title calc">
        Calculator 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-calc">
         – 
       </div> 
       <div class="control closewin" data-target="#window-calc">
         × 
       </div> 
      </div> 
     </div> 
     <div class="container"> 
      <div id="display"> 
       <input disabled id="operation"> 
       <input disabled id="result" maxlength="20" value="0"> 
      </div> 
      <table class="btns"> 
       <tbody> 
        <tr> 
         <td class="bt btn-fnc"><b>←</b></td> 
         <td class="bt btn-fnc">CE</td> 
         <td class="bt btn-fnc">C</td> 
         <td class="bt btn-fnc">±</td> 
         <td class="bt btn-fnc">√</td> 
        </tr> 
        <tr> 
         <td class="bt btn-bright btn-num">7</td> 
         <td class="bt btn-bright btn-num">8</td> 
         <td class="bt btn-bright btn-num">9</td> 
         <td class="bt btn-fnc">/</td> 
         <td class="bt btn-fnc">%</td> 
        </tr> 
        <tr> 
         <td class="bt btn-bright btn-num">4</td> 
         <td class="bt btn-bright btn-num">5</td> 
         <td class="bt btn-bright btn-num">6</td> 
         <td class="bt btn-fnc">*</td> 
         <td class="bt btn-fnc">1/x</td> 
        </tr> 
        <tr> 
         <td class="bt btn-bright btn-num">1</td> 
         <td class="bt btn-bright btn-num">2</td> 
         <td class="bt btn-bright btn-num">3</td> 
         <td class="bt btn-fnc">-</td> 
         <td class="bt btn-fnc text-200" rowspan="2">=</td> 
        </tr> 
        <tr> 
         <td class="bt btn-bright btn-num" colspan="2">0</td> 
         <td class="bt btn-bright btn-num">.</td> 
         <td class="bt btn-fnc">+</td> 
        </tr> 
       </tbody> 
      </table> 
     </div> 
    </div> 
    <div class="window" id="window-bin"> 
     <div class="titlebar"> 
      <div class="title bin">
        Recycle Bin 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-bin">
         – 
       </div> 
       <div class="control maximize" data-target="#window-bin">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-bin">
         × 
       </div> 
      </div> 
     </div> 
     <div class="addrbar"> 
      <div> 
       <div class="button round back">
         ➜ 
       </div> 
       <div class="button round">
         ➜ 
       </div> 
      </div> 
      <div class="addr bin"> <label>Recycle Bin</label> 
      </div> 
      <div class="input"> 
       <input type="search" placeholder="Search Recycle Bin"> 
      </div> 
     </div> 
     <div class="toolbar"> 
     </div> 
     <div class="container"> 
      <div class="text-center text-muted">
        Recycle bin is empty. 
      </div> <!--<div class="icons">--> <!--    <div class="column">--> <!--        <div class="icon icon-sm file"><label>My file</label></div>--> <!--    </div>--> <!--</div>--> 
     </div> 
    </div> 
    <div class="window" id="window-ie"> 
     <div class="titlebar"> 
      <div class="title ie">
        Windows Internet Explorer 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-ie">
         – 
       </div> 
       <div class="control maximize" data-target="#window-ie">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-ie">
         × 
       </div> 
      </div> 
     </div> 
     <div class="addrbar"> 
      <div> 
       <div class="button round back">
         ➜ 
       </div> 
       <div class="button round">
         ➜ 
       </div> 
      </div> 
      <div class="input"> 
       <input type="text" id="webaddr" value="https://www.bing.com/"> 
      </div> 
      <div class="input"> 
       <input type="search" id="bing" placeholder="Bing"> 
      </div> 
     </div> 
     <div class="toolbar"> 
      <div class="toolbar-item">
        Favorites 
      </div> 
      <div class="toolbar-item">
        Bookmarks 
      </div> 
     </div> 
     <div class="container p-0"> <iframe id="webpage" frameborder="0" data-html2canvas-ignore="true" src="https://www.bing.com/"></iframe> 
     </div> 
    </div> 
    <div class="window" id="window-notepad" data-child="#window-font"> 
     <div class="titlebar"> 
      <div class="title notepad">
        Untitled - Notepad 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-notepad">
         – 
       </div> 
       <div class="control maximize" data-target="#window-notepad">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-notepad">
         × 
       </div> 
      </div> 
     </div> 
     <div class="toolbar"> 
      <div class="toolbar-item">
        File 
       <ul class="toolbar-subitem"> 
        <li id="notepad-new">New</li> 
        <li id="notepad-open" class="text-muted">Open</li> 
        <li id="notepad-save" class="text-muted">Save</li> 
        <hr> 
        <li class="closewin" data-target="#window-notepad">Exit</li> 
       </ul> 
      </div> 
      <div class="toolbar-item">
        Edit 
       <ul class="toolbar-subitem"> 
        <li id="notepad-undo">Undo</li> 
        <hr> 
        <li id="notepad-cut" class="text-muted">Cut</li> 
        <li id="notepad-copy" class="text-muted">Copy</li> 
        <li id="notepad-paste" class="text-muted">Paste</li> 
        <li id="notepad-del" class="text-muted">Delete</li> 
        <hr> 
        <li id="notepad-find" class="text-muted">Find...</li> 
        <li id="notepad-findnext" class="text-muted">Find Next</li> 
        <li id="notepad-replace" class="text-muted">Replace...</li> 
        <li id="notepad-goto" class="text-muted">Go to...</li> 
        <hr> 
        <li id="notepad-all">Select All</li> 
        <li id="notepad-datetime">Time/Date</li> 
       </ul> 
      </div> 
      <div class="toolbar-item">
        Format 
       <ul class="toolbar-subitem"> 
        <li id="notepad-wrap">Word Wrap</li> 
        <li data-toggle="window" data-target="#window-font">Font...</li> 
       </ul> 
      </div> 
      <div class="toolbar-item">
        View 
       <ul class="toolbar-subitem"> 
        <li id="notepad-statbar" class="text-muted">Status Bar</li> 
       </ul> 
      </div> 
     </div> 
     <div class="container p-0"> <textarea id="notepad-editor"></textarea> 
     </div> 
    </div> 
    <div class="window window-child" id="window-font"> 
     <div class="titlebar"> 
      <div class="title p-0">
        Font 
      </div> 
      <div class="controls"> 
       <div class="control closewin" data-target="#window-font">
         × 
       </div> 
      </div> 
     </div> 
     <div class="container"> 
      <div class="font-row"> 
       <div class="column-font"> 
        <div class="text-75">
          Font: 
        </div> 
        <ul class="list"> 
         <li> <input type="radio" name="font-family" id="font-lucida" value="&quot;lucida console&quot;,monospace" checked> <label for="font-lucida" style="font-family: &quot;lucida console&quot;,monospace">Lucida Console</label> </li> 
         <li> <input type="radio" name="font-family" id="font-verdana" value="verdana,monospace"> <label for="font-verdana" style="font-family: verdana,monospace">Verdana</label> </li> 
         <li> <input type="radio" name="font-family" id="font-arial" value="arial,sans-serif"> <label for="font-arial" style="font-family: arial,sans-serif">Arial</label> </li> 
         <li> <input type="radio" name="font-family" id="font-impact" value="impact,sans-serif"> <label for="font-impact" style="font-family: impact,sans-serif">Impact</label> </li> 
         <li> <input type="radio" name="font-family" id="font-times" value="times,serif"> <label for="font-times" style="font-family: times,serif">Times New Roman</label> </li> 
         <li> <input type="radio" name="font-family" id="font-georgia" value="georgia,serif"> <label for="font-georgia" style="font-family: georgia,serif">Georgia</label> </li> 
        </ul> 
       </div> 
       <div class="column-style"> 
        <div class="text-75">
          Style: 
        </div> 
        <ul class="list"> 
         <li> <input type="radio" name="font-style" id="style-regular" value="normal,normal" checked> <label for="style-regular">Regular</label> </li> 
         <li> <input type="radio" name="font-style" id="style-italic" value="italic,normal"> <label for="style-italic" style="font-style: italic">Italic</label> </li> 
         <li> <input type="radio" name="font-style" id="style-bold" value="normal,bold"> <label for="style-bold" style="font-weight: bold">Bold</label> </li> 
         <li> <input type="radio" name="font-style" id="style-bi" value="italic,bold"> <label for="style-bi" style="font-style: italic; font-weight: bold">Bold Italic</label> </li> 
        </ul> 
       </div> 
       <div class="column-size"> 
        <div class="text-75">
          Size: 
        </div> 
        <ul class="list"> 
         <li> <input type="radio" name="font-size" id="size-10" value="10" checked> <label for="size-10">10</label> </li> 
         <li> <input type="radio" name="font-size" id="size-11" value="11"> <label for="size-11">11</label> </li> 
         <li> <input type="radio" name="font-size" id="size-12" value="12"> <label for="size-12">12</label> </li> 
         <li> <input type="radio" name="font-size" id="size-14" value="14"> <label for="size-14">14</label> </li> 
         <li> <input type="radio" name="font-size" id="size-18" value="18"> <label for="size-18">18</label> </li> 
         <li> <input type="radio" name="font-size" id="size-25" value="25"> <label for="size-25">25</label> </li> 
        </ul> 
       </div> 
      </div> 
      <div class="font-row flex-right mt-5"> <button class="bt bt-primary closewin" data-target="#window-font" id="notepad-font">OK</button> <button class="bt bt-secondary closewin" data-target="#window-font">Cancel</button> 
      </div> 
     </div> 
    </div> 
    <div class="window" id="window-personal"> 
     <div class="titlebar"> 
      <div class="title personal">
        Personalize 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-personal">
         – 
       </div> 
       <div class="control maximize" data-target="#window-personal">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-personal">
         × 
       </div> 
      </div> 
     </div> 
     <div class="addrbar"> 
      <div> 
       <div class="button round back">
         ➜ 
       </div> 
       <div class="button round">
         ➜ 
       </div> 
      </div> 
      <div class="addr personal"> <label>Personalize</label> 
      </div> 
     </div> 
     <div class="container"> 
      <div class="title-1">
        Change the visuals and sounds on your computer 
      </div> Click a theme to change the desktop background, window color and sound all at once. 
      <div class="themes"> 
       <div class="headline">
         Aero Themes (10) 
       </div> 
       <ul class="theme-collection"> 
        <li class="theme selected" id="aero-1"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Windows 7</label> </li> 
        <li class="theme" id="aero-2"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Architecture</label> </li> 
        <li class="theme" id="aero-3"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Landscapes</label> </li> 
        <li class="theme" id="aero-4"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Nature</label> </li> 
        <li class="theme" id="aero-5"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>More</label> </li> 
        <li class="theme" id="aero-6"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>More and more</label> </li> 
        <li class="theme" id="aero-7"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label></label> </li> 
        <li class="theme" id="aero-8"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label></label> </li> 
        <li class="theme" id="aero-9"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label></label> </li> 
        <li class="theme" id="aero-10"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label></label> </li> 
       </ul> 
       <div class="headline">
         Basic and High Contrast Themes (4) 
       </div> 
       <ul class="theme-collection"> 
        <li class="theme theme-basic" id="basic-1"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Windows 7 Basic</label> </li> 
        <li class="theme theme-basic" id="basic-2"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>Windows Classic</label> </li> 
        <li class="theme theme-basic" id="basic-3"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>High Contrast Black</label> </li> 
        <li class="theme theme-basic" id="basic-4"> 
         <div class="theme-bg"></div> 
         <div class="theme-color"></div> <label>High Contrast White</label> </li> 
       </ul> 
      </div> 
      <p>Current theme: <b id="theme-name">landscapes</b></p> 
     </div> 
    </div> 
    <div class="window" id="window-computer"> 
     <div class="titlebar"> 
      <div class="title computer">
        Computer 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-computer">
         – 
       </div> 
       <div class="control maximize" data-target="#window-computer">
         □ 
       </div> 
       <div class="control closewin" data-target="#window-computer">
         × 
       </div> 
      </div> 
     </div> 
     <div class="addrbar"> 
      <div> 
       <div class="button round back">
         ➜ 
       </div> 
       <div class="button round">
         ➜ 
       </div> 
      </div> 
      <div class="addr computer"> <label>Computer</label> 
      </div> 
      <div class="input"> 
       <input type="search" placeholder="Search Computer"> 
      </div> 
     </div> 
     <div class="toolbar"> 
      <div class="toolbar-item">
        Organize 
      </div> 
     </div> 
     <div class="container"> 
      <div class="headline" data-toggle="expand" data-target="#hdd">
        Hard Disk Drives (3) 
      </div> 
      <div class="devices" id="hdd"> 
       <div class="device disk-os" id="disk-C"> 
        <div class="name"> <label>WIN</label> (C:) 
        </div> 
        <div class="storage-bar"></div> 
        <div class="storage-txt"></div> 
       </div> 
       <div class="device disk-data" id="disk-D"> 
        <div class="name"> <label>DATA</label> (D:) 
        </div> 
        <div class="storage-bar"></div> 
        <div class="storage-txt"></div> 
       </div> 
       <div class="device disk-data" id="disk-E"> 
        <div class="name"> <label>Local Disk</label> (E:) 
        </div> 
        <div class="storage-bar"></div> 
        <div class="storage-txt"></div> 
       </div> 
      </div> 
      <div class="headline" data-toggle="expand" data-target="#cdd">
        Devices with Removable Storage (2) 
      </div> 
      <div class="devices" id="cdd"> 
       <div class="device disk-cd"> 
        <div class="name">
          DVD RW Drive (F:) 
        </div> 
       </div> 
       <div class="device disk-usb" id="disk-G"> 
        <div class="name"> <label>Removable Disk</label> (G:) 
        </div> 
        <div class="storage-bar"></div> 
        <div class="storage-txt"></div> 
       </div> 
      </div> 
     </div> 
    </div> 
    <div class="window" id="window-snipping"> 
     <div class="titlebar"> 
      <div class="title snipping">
        Snipping Tool 
      </div> 
      <div class="controls"> 
       <div class="control minimize" data-target="#window-snipping">
         – 
       </div> 
       <div class="control closewin" data-target="#window-snipping">
         × 
       </div> 
      </div> 
     </div> 
     <div class="toolbar"> 
      <div class="toolbar-item snipping">
        New 
       <ul class="toolbar-subitem"> 
        <li class="text-muted">Free-form Snip</li> 
        <li class="snip" id="snip-rect">Rectangular Snip</li> 
        <li class="snip" id="snip-win">Window Snip</li> 
        <li class="snip" id="snip-full">Full-screen Snip</li> 
       </ul> 
      </div> 
      <div class="toolbar-item cancel" id="snip-cancel">
        Cancel 
      </div> 
     </div> 
     <div class="container direction" id="snip-result">
       Select snip mode to start snipping. 
     </div> 
    </div> 
    <div class="window" id="window-wait"> 
     <div class="container text-center text-bold">
       Please Wait 
     </div> 
    </div> 
   </div> 
   <div id="taskbar"> 
    <div id="start-menu"> 
     <div id="programs"> 
      <div class="program about" data-toggle="window" data-target="#window-about">
        About 
      </div> 
      <div class="program calc" data-toggle="window" data-target="#window-calc">
        Calculator 
      </div> 
      <div class="program ie" data-toggle="window" data-target="#window-ie">
        Internet Explorer 
      </div> 
      <div class="program notepad" data-toggle="window" data-target="#window-notepad">
        Notepad 
      </div> 
      <div class="program snipping" data-toggle="window" data-target="#window-snipping">
        Snipping Tool 
      </div> 
      <div class="program paint">
        Paint 
      </div> 
      <div class="program game" data-toggle="window" data-target="#window-game">
        Game 
      </div> 
      <div class="program"></div> 
      <div class="program"></div> 
      <div class="program" id="search"> 
       <input type="search" placeholder="Search programs and files"> 
      </div> 
     </div> 
     <div id="links"> 
      <div class="link">
        Users 
      </div> 
      <div class="link">
        Documents 
      </div> 
      <div class="link">
        Pictures 
      </div> 
      <div class="link">
        Music 
      </div> 
      <hr> 
      <div class="link" data-toggle="window" data-target="#window-computer">
        Computer 
      </div> 
      <hr> 
      <div class="link">
        Control Panel 
      </div> 
      <div class="link">
        Devices and Printers 
      </div> 
      <div class="link">
        Default Programs 
      </div> 
      <div class="link">
        Help and Support 
      </div> 
      <div class="link"> 
       <div class="button" id="logoff">
         Log off 
       </div> 
      </div> 
     </div> 
    </div> 
    <div class="taskbar-item" id="start-button"></div> 
    <div class="taskbar-item right" id="wifi"></div> 
    <div class="taskbar-item right" id="show-desktop"></div> 
    <div class="taskbar-item right" id="datetime"> 
     <div id="time"></div> 
     <div id="date"></div> 
    </div> 
    <div class="taskbar-item right" id="battery"> 
     <div id="gauge"></div> 
    </div> 
   </div> 
  </div> 
  <audio id="startup" src="https://vignette.wikia.nocookie.net/khangnd/images/5/58/Windows7-startup-sound.ogg"></audio> 
  <style>
    /** VARIABLES **/
:root {
    --taskbar : 36px;
    --titlebar: 20px;
    --addrbar : 31px;
    --toolbar : 35px;
    --margin  : 5px;
    --padding : 20px;
    --screenw : 100vw;
    --screenh : 100vh;
    --headline: #3083b7;
  --aero-1  : url(https://i.imgur.com/rd5dzsT.jpg);
  --aero-2  : url(https://i.imgur.com/o6ebTSi.jpg);
  --aero-3  : url(https://i.imgur.com/v15gh6X.jpg);
  --aero-4  : url(https://i.imgur.com/REAaN9T.jpg);
    --aero-5  : url(https://i.imgur.com/VW1OKss.jpg);
     --aero-6  : url(https://i.imgur.com/92fjsAY.jpg);
     --aero-7  : url(https://i.imgur.com/mNify5m.jpg);
     --aero-8  : url(https://i.imgur.com/z5rYs36.jpg);
     --aero-9  : url(https://i.imgur.com/8BV1OTt.jpg);
     --aero-10  : url(https://i.imgur.com/UQdXDWw.jpg);
  --aero-1-color: rgba(170, 209, 251, 0.6);
  --aero-2-color: rgba(85, 132, 200, 0.6);
  --aero-3-color: rgba(171, 171, 171, 0.6);
  --aero-4-color: rgba(179, 155, 207, 0.6);
    --aero-5-color: rgba(179, 155, 207, 0.6);
    --aero-6-color: rgba(179, 155, 207, 0.6);
    --aero-7-color: rgba(179, 155, 207, 0.6);
    --aero-8-color: rgba(179, 155, 207, 0.6);
     --aero-9-color: rgba(179, 155, 207, 0.6);
    --aero-10-color: rgba(179, 155, 207, 0.6);
}

/** ICONS **/
.about { background-image: url(https://i.imgur.com/lHNzVVq.png) }
.calc { background-image: url(https://i.imgur.com/66Rctgz.png) }
.paint { background-image: url(https://i.imgur.com/nrKLvq2.jpg) }
.snipping { background-image: url(https://i.imgur.com/3rEMUdW.png) }
.notepad { background-image: url(https://i.imgur.com/zaI9fMo.png) }
.bin { background-image: url(https://i.imgur.com/QTUZ6iR.png) }
.computer { background-image: url(https://i.imgur.com/24dwXF1.png) }
        .folder { background-image: url(https://i.imgur.com/XAabxpZ.png) }
.personal { background-image: url(https://i.imgur.com/nUTTrjp.png) }
.ie { background-image: url(https://i.imgur.com/9y1cRkP.png) }
.file { background-image: url(https://i.imgur.com/Zg4R50G.png) }
.desktop { background-image: url(https://i.imgur.com/nUTTrjp.png) }
.disk-data { background-image: url(https://i.imgur.com/sVHBzGZ.png) }
.disk-usb  { background-image: url(https://i.imgur.com/sVHBzGZ.png) }
.disk-os   { background-image: url(https://i.imgur.com/Q4A5Hzb.png) }
.disk-cd { background-image: url(https://freepngimg.com/download/windows/24630-5-windows-cd-cover-transparent.png) }
.cancel { background-image: url(https://i.imgur.com/Hw42swJ.png) }

/** LOG ON **/
#logon {
    width: var(--screenw);
    height: var(--screenh);
    text-align: center;
    background: linear-gradient(135deg, #053c99, #28a2e3, #89e9f9);
}
#logon-wrapper {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
#user {
    display: inline-block;
    padding: 8px;
    border: 1px solid #3f3f3f;
    border-radius: 20px;
    box-shadow: inset 1px 1px 1px #fff, 0 0 15px rgba(0, 0, 0, 0.5);
    background: linear-gradient(to bottom, #cfeaf8, #65aac9 45%, #3b90b5 45%, #5db3de);
}
#user > img {
    border: 1px solid #3f3f3f;
    border-radius: 5px;
    box-shadow: 0 0 1px 1px #fff;
}
#name {
    margin: 10px 0;
    color: #fff;
    text-shadow: 0 1px 2px #000;
    font-weight: bold;
}
#input {
    position: relative;
}
#password {
    width: 150px;
    border: 1px solid #666;
    border-radius: 3px;
}
#start {
    position: absolute;
    top: 50%;
    left: 102%;
    transform: translateY(-50%);
    font-weight: bold;
    font-size: 150%;
    text-shadow: 0 1px 1px #000;
}

/** DESKTOP **/
#windows {
    display: none;
    width: var(--screenw);
    height: var(--screenh);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    position: relative;
}
#desktop {
    position: fixed;
    width: var(--screenw);
    height: calc(var(--screenh) - var(--taskbar));
}
.icons { display: flex }
.column { margin: 5px }
.icon {
    position: relative;
    background-size: 70%;
    background-position: center 10%;
    background-repeat: no-repeat;
}
.icons-sm .icon { width: 30px;  height: 30px }
.icons-md .icon { width: 60px;  height: 60px }
.icons-lg .icon { width: 120px; height: 120px }
.icon:hover { background-color: rgba(255, 255, 255, 0.4) }
.icon > label {
    width: 100%;
    position: absolute;
    bottom: 0;
    text-align: center;
    text-overflow: ellipsis;
    white-space: nowrap;
    overflow: hidden;
    font-size: 50%;
    color: #fff;
    text-shadow: 1px 1px #000;
}
.icon > label > input {
    width: 80%;
    text-align: center;
    padding: 0;
    font-size: 100%;
}
#desktop-menu {
    z-index: 1;
    display: none;
    background: #fff;
    font-size: 70%;
}
#desktop-menu,
.sub-menu {
    min-width: 130px;
    position: absolute;
    border: 1px solid #bbb;
    box-shadow: 2px 2px 2px 0 rgba(4, 69, 133, 0.4);
}
.menu-item {
    padding: 4px 0 4px 20px;
  color: #000;
    position: relative;
    background-size: 9%;
    background-position: 4px center;
    background-repeat: no-repeat;
}
.menu-item:hover { background-color: rgba(205, 224, 255, 0.4) }
.has-sub:after {
    content: '';
    position: absolute;
    top: 50%;
    right: 3px;
    transform: translateY(-50%);
    border: 4px solid transparent;
    border-left-color: currentColor;
}
.sub-menu {
    display: none;
    top: 0;
    left: 98%;
    background: #fff;
}
.sub-menu > .active:before,
.toolbar-subitem > li.active:before {
    content: '';
    position: absolute;
    top: calc(50% - 2.5px);
    left: 6px;
  width: 5px;
  height: 5px;
  border-radius: 50%;
  background: currentColor;
}
.has-sub:hover > .sub-menu { display: block }
#desktop-menu hr {
    border-color: rgba(255, 255, 255, 0.5);
    margin: 2px 6px
}

/** TASKBAR **/
#taskbar {
    position: fixed;
    width: 100%;
    height: var(--taskbar);
    z-index: 1;
    left: 0;
    bottom: 0;
    box-sizing: border-box;
    border-top: 1px solid #555;
    background: linear-gradient(to bottom, rgba(255, 255, 255, 0.8), transparent 3px);
}
.taskbar-item { display: inline-block; color: #fff }
.taskbar-item.left:before {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    background:
        linear-gradient(135deg,
            rgba(255, 255, 255, 0.6),
            rgba(255, 255, 255, 0.2),
            transparent 40%,
            rgba(255, 255, 255, 0.5) 95%
        ),
        linear-gradient(to right, #fff, transparent 1px),
        linear-gradient(to left , #fff, transparent 1px);
}
.taskbar-item.left {
    position: relative;
    margin-right: 3px;
    width: 45px;
    height: 100%;
    background-size: 60%;
    background-position: center center;
    background-repeat: no-repeat;
}
.taskbar-item.right {
    height: 100%;
    margin-left: 8px;
    float: right;
}
#start-button {
  margin: 3px;
    width: 40px;
    height: 40px;
    background: url(https://i.imgur.com/RuIg1YN.png) no-repeat;
    background-size: contain;
  float: left;
}
#start-button:hover,
#start-button.active { filter: brightness(1.4) contrast(1.3) }
#show-desktop {
    width: 15px;
    border-radius: 3px;
    background:
        linear-gradient(135deg,
            rgba(255, 255, 255, 0.6),
            rgba(255, 255, 255, 0.2),
            transparent 40%,
            rgba(255, 255, 255, 0.5) 95%
        ),
        linear-gradient(to right, #fff, transparent 1px),
        linear-gradient(to left , #fff, transparent 1px);
}
#datetime {
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    font-size: small;
}
#battery {
    position: relative;
    margin-top: 10px;
    width: 11px;
    height: 16px;
    border: 1px solid #fff;
    border-radius: 2px;
    padding: 1px;
    box-sizing: border-box;
}
#battery:before {
    content: '';
    position: absolute;
    bottom: 100%;
    left: 25%;
    width: 50%;
    height: 2px;
    background: #fff;
}
#gauge {
    position: relative;
    width: 100%;
    height: 100%;
    top: 0;
    background: #fff;
}
 #wifi {
     
 }
#start-menu {
    display: none;
    position: absolute;
    bottom: 100%;
    min-width: 350px;
    height: 300px;
    padding: 6px;
    border: 1px solid #555;
    border-radius: 3px;
  box-shadow: inset 0 0 0 0.5px #fff;
    font-size: 70%;
  background: linear-gradient(transparent, rgba(0,0,0,0.6), transparent);
}
#start-menu .program,
#start-menu .link {
    display: flex;
    flex-direction: column;
    justify-content: center;
    box-sizing: border-box;
    border: 1px solid transparent;
}
#start-menu > #programs {
    float: left;
    width: 55%;
    height: 100%;
    background: #fff;
    border-radius: 2px;
    padding: 2px;
    box-sizing: border-box;
}
#start-menu .program {
    width: 100%;
    height: 10%;
    background-repeat: no-repeat;
    background-size: contain;
    padding-left: 33px;
    border-radius: 2px;
}
#start-menu .program:hover {
    background-color: #cce2ef;
    border-color: #bbb;
}
.program#search { padding: 0 }
#start-menu > #links {
    float: left;
    width: 45%;
    height: 100%;
    color: #fff;
    padding: 2px 5px;
    box-sizing: border-box;
}
#start-menu hr {
    margin: 3px 0;
    border-color: #999;
}
#start-menu .link {
    height: 9.3%;
    padding-left: 5px;
}
#start-menu .link:not(:last-child):hover {
    border-color: #999;
    background-image: linear-gradient(to bottom,
        rgba(255, 255, 255, 0.2),
        rgba(0, 0, 0, 0.3) 50%,
        transparent 98%);
}

/** WINDOW **/
.window {
    position: absolute;
    top: 0;
  z-index: 1;
    display: none;
    width: 300px;
    height: 50%;
    padding: 5px;
    border: 1px solid #000;
    border-radius: 5px;
    box-shadow: inset 0 0 0 1px #fff, 0 0 5px #000;
    box-sizing: border-box;
}
#taskbar:before,
#start-menu:before,
.window:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  background: rgba(0,0,0,0.25);
}
.window > div:not(:first-child) { margin-top: var(--margin) }
.window > .titlebar { position: relative }
.titlebar > .title {
    font-size: small;
    line-height: 20px;
    padding-left: 23px;
    text-shadow:
        0 0 10px #fff, 0 0 10px #fff,
        0 0 10px #fff, 0 0 10px #fff,
        0 0 10px #fff, 0 0 10px #fff,
        0 0 10px #fff, 0 0 10px #fff;
    background-repeat: no-repeat;
    background-size: contain;
}
.titlebar > .controls {
    position: absolute;
    right: 0;
    top: -5px;
    display: flex;
  border-radius: 0 0 3px 3px;
  overflow: hidden;
}
.controls > .control {
    width: 25px;
    line-height: 15px;
    font-weight: bold;
    text-align: center;
  color: #fff;
    border-right: 1px solid #666;
    text-shadow: 1px 1px 0 #000;
    box-sizing: border-box;
  box-shadow: inset 0 0 0 0.5px #eee;
    background-image: linear-gradient(
        rgba(255,255,255,0.3), rgba(255,255,255,0.3) 45%,
        rgba(0, 0, 0, 0.1) 50%, rgba(0, 0, 0, 0.1) 70%,
    rgba(255, 255, 255, 0.5)
  );
}
.controls > .closewin {
    background-color: #d04a37;
    width: 35px;
}
.controls > .maximize { line-height: 12px }
.maximized {
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
}
.focused { z-index: 2 }
.addrbar {
    display: flex;
    align-items: center;
}
.addrbar > div:first-child { min-width: 60px }
.addrbar > div:not(:first-child) {
    flex-grow: 1;
    margin-left: 5px;
}
.addrbar > .input { height: 23px }
.addrbar input { width: 100%; height: 100% }
.addr,
.addrbar input {
    background-color: #ecf5fe;
    border: 1px solid #888;
    border-bottom-color: #ccc;
    border-right-color: #ccc;
  box-sizing: border-box;
}
.addr {
    white-space: nowrap;
    font-size: 80%;
    padding: 3px 0 3px 20px;
    position: relative;
    background-size: contain;
    background-repeat: no-repeat;
}
.addr > label { margin-left: 15px }
.addr:before {
    content: '';
    position: absolute;
    top: calc(50% - 4px);
    border: 4px solid transparent;
    border-left-color: currentColor;
    margin-left: 5px;
}
.toolbar {
    background: linear-gradient(#fff 30%, #dce6f5 70%);
    border: 1px solid #555;
    height: 28px;
    line-height: 28px;
    font-size: 80%;
    margin-bottom: -6px;
    display: flex;
}
.toolbar-item {
    padding: 0 10px;
    color: #3b5372;
    position: relative;
    /white-space: nowrap;/
    /overflow: hidden;/
    /text-overflow: ellipsis;/
}
.toolbar-item:hover > .toolbar-subitem { display: block }
.toolbar-subitem {
    display: none;
    position: absolute;
    left: 0;
    top: 100%;
    min-width: 100px;
    background: #f0f0f0;
    padding: 1px;
    border: 1px solid #999;
    box-shadow: 2px 2px 1px rgba(0,0,0,0.3);
    margin: 0;
}
.toolbar-subitem > li {
    list-style: none;
    margin: 0;
    padding-left: 20px;
    border: 1px solid transparent;
  position: relative;
}
.toolbar-subitem > li:hover {
    border-color: rgb(177, 208, 244);
    background: linear-gradient(rgba(255, 255, 255, 0.5), rgba(177, 208, 244, 0.3));
}
.toolbar-subitem > hr {
    margin: 0 3px;
    border-color: #fff;
}
.window > .container {
    padding: 10px;
    background: #fff;
    border: 1px solid #555;
    overflow: auto;
    height: calc(100%
        - var(--titlebar)
        - var(--addrbar)
        - var(--toolbar)
        - var(--padding)
    );
}
#window-about > .container {
    height: calc(100%
        - var(--titlebar)
        - var(--margin)
        - var(--padding)
    );
}
#window-ie > .container {
    height:  calc(100%
        - var(--titlebar)
        - var(--addrbar)
        - var(--toolbar)
    );
}

/** CALCULATOR **/
#window-calc {
  width: auto;
  height: auto
}
#window-calc > .container {
    background: #d9e4f1;
    padding: 10px;
    border: 1px solid #8a939c;
}
#display, .bt {
    box-sizing: border-box;
    border: 1px solid #8a939c;
    border-radius: 3px;
}
#display {
    height: 70px;
    position: relative;
    background-image: linear-gradient(#d9e4f1, #fff);
    margin-bottom: 3px;
}
#display > input {
    position: absolute;
    font-family: monospace;
    text-align: right;
    background: none;
    border: 0;
    color: #000;
    width: 100%;
    font-size: 120%;
}
#display > #result {
    font-size: 250%;
    bottom: 0;
}
@media only screen and (max-width: 480px) {
    #result { font-size: 200% }
}
#window-calc .btns {
    width: 100%;
    border-spacing: 5px;
}
#window-calc .bt {
    width: 20%;
    background: linear-gradient(rgba(255,255,255,0.4) 50%, transparent 50%);
    box-shadow: inset 0 0 2px 1px #fff;
    padding: 5px;
    text-align: center;
}
#window-calc .btn-bright { background: linear-gradient(rgba(255,255,255,0.7) 50%, rgba(255,255,255,0.4) 50%) }
#window-calc .bt:hover {
    border-color: rgb(255, 219, 0);
    background: linear-gradient(rgb(255, 238, 219) 50%, rgb(255, 212, 119) 50%);
}

/** NOTEPAD **/
#window-notepad > .toolbar {
  height: 20px;
    line-height: 20px;
    padding: 1px;
}
#window-notepad .toolbar-item {
    padding: 0 5px;
    color: #000;
    border: 1px solid transparent;
    border-radius: 3px;
}
#window-notepad .toolbar-item:hover {
    border-color: #555;
    background: rgba(0,0,0,0.1);
}
#window-notepad > .container {
    height: calc(100% - var(--titlebar) - 30px);
}
#notepad-editor {
    overflow: scroll;
    resize: none;
    white-space: nowrap;
    font-family: "lucida console", monospace;
    font-size: 10pt;
    border: 0;
    width: 100%;
    height: 100%;
    cursor: text;
}
#notepad-editor.wrap { white-space: normal }

#window-font { height: auto }
#window-font > .container {
    height: calc(100%
        - var(--titlebar)
        - var(--padding)
        - var(--margin)
    );
}
.font-row { display: flex }
.font-row > div { white-space: nowrap; overflow: hidden; }
.font-row > div:not(:first-child) { margin-left: 8px }
.flex-right { justify-content: flex-end }
.list {
    margin: 0; padding: 0;
    overflow: hidden; overflow-y: auto;
    border: 1px solid #555;
    height: 100px;
}
.list > li { list-style: none; }
.list > li > input { display: none }
.list > li > label { display: block }
.list > li > input:checked + label { color: #fff; background: #299bfc }

/** PERSONALIZE **/
#window-personal > .container {
    height: calc(100%
        - var(--titlebar)
        - var(--addrbar)
        - var(--padding)
        - var(--margin)
    );
}
.themes {
    margin-top: 10px;
    border: 1px solid #555;
    padding: 8px;
}
.headline {
    color: var(--headline);
    display: flex;
    align-items: center;
}
.headline:after {
    content: '';
    width: 100%;
    flex: 1;
    border-top: 1px solid #ccc;
}
.theme-collection {
    display: flex;
    flex-wrap: wrap;
    padding: 0;
    text-align: center;
}
.theme {
    list-style: none;
    width: 100px;
    height: 100px;
    border: 1px solid transparent;
    box-sizing: border-box;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 5px;
  margin: 3px;
    font-size: 12px;
}
.device:hover,
.theme:hover,
.theme.selected {
    border-color: rgb(177, 208, 244);
    background-color: rgba(177, 208, 244, 0.3);
}
.theme > .theme-bg {
    position: absolute;
    top: 5px;
    right: 5px;
    width: 70%;
    height: 45%;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}
.theme > .theme-color {
    position: absolute;
    top: 50%;
    left: 5px;
    transform: translateY(-50%);
    width: 50%;
    height: 50%;
    border-radius: 4px;
    border: 1px solid #888;
    box-shadow: inset 0 0 0 1px #fff;
    box-sizing: border-box;
}
.theme > label {
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}
.theme:hover > label { white-space: normal; }
.theme-basic > .theme-color {
    border-radius: 0;
    border-color: transparent;
    box-shadow: none;
    display: flex;
    flex-direction: column;
}
.theme-basic > .theme-color:before,
.theme-basic > .theme-color:after {
    content: '';
    background: #000;
    display: block;
}
.theme-basic > .theme-color:before { height: 35% }
.theme-basic > .theme-color:after  { height: 65% }

#aero-1 > .theme-bg { background-image: var(--aero-1) }
#aero-1 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-1-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

#aero-2 > .theme-bg { background-image: var(--aero-2) }
#aero-2 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-2-color) 65%, rgba(85, 132, 200, 0.3) 70%) }

#aero-3 > .theme-bg { background-image: var(--aero-3) }
#aero-3 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-3-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

 #aero-4 > .theme-bg { background-image: var(--aero-4) }
#aero-4 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-4-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

#aero-5 > .theme-bg { background-image: var(--aero-5) }
#aero-5 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-5-color) 65%, rgba(85, 132, 200, 0.3) 70%) }
        
 #aero-6 > .theme-bg { background-image: var(--aero-6) }
#aero-6 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-6-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

#aero-7 > .theme-bg { background-image: var(--aero-7) }
#aero-7 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-7-color) 65%, rgba(85, 132, 200, 0.3) 70%) }

#aero-8 > .theme-bg { background-image: var(--aero-8) }
#aero-8 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-8-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

 #aero-9 > .theme-bg { background-image: var(--aero-9) }
#aero-9 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-9-color) 65%, rgba(170, 209, 251, 0.3) 70%) }

#aero-10 > .theme-bg { background-image: var(--aero-10) }
#aero-10 > .theme-color { background-image: radial-gradient(circle at 100% 100%, var(--aero-10-color) 65%, rgba(85, 132, 200, 0.3) 70%) }
                         
/* windows basic */
#basic-1 > .theme-bg { background-image: var(--aero-1) }
#basic-1 > .theme-color {
    background: #a7bfd7;
    box-shadow: 0.5px 0.5px 0 1px #000, inset 0 0 0 0.5px #fff;
    border-radius: 4px 4px 0 0;
    padding: 3px;
}
#basic-1 > .theme-color:before { box-shadow: inset 0 0 0 4px #a7bfd7, inset -7px -7px 0 #a7bfd7 }
#basic-1 > .theme-color:after  { box-shadow: inset 0 0 0 4px #fff, inset -19px -19px 0 #fff }

/* windows classic */
#basic-2 > .theme-bg { background-color: #3b6ea4 }
#basic-2 > .theme-color {
    background: #d0d0d0;
    box-shadow: 0.5px 0.5px 0 1px #000;
    padding: 1px;
}
#basic-2 > .theme-color:before { box-shadow: inset 0 0 0 5px #0f75c9, inset -7px -7px 0 #0f75c9; background: #fff; }
#basic-2 > .theme-color:after  { box-shadow: inset 0 0 0 4px #fff, inset -21px -21px 0 #fff }

/* contrast black */
#basic-3 > .theme-bg { background-color: #000 }
#basic-3 > .theme-color {
    background: #fff;
    padding: 0.5px;
}
#basic-3 > .theme-color:before { box-shadow: inset 0 0 0 5px #81007f, inset -7px -7px 0 #81007f; background: #fff; }
#basic-3 > .theme-color:after  { box-shadow: inset 0 0 0 4px #000, inset -21px -21px 0 #000; background: #fff; }

/* contast white */
#basic-4 > .theme-bg { background-color: #fff; box-shadow: inset 0 0 0 1px #999 }
#basic-4 > .theme-color {
    background: #fff;
    box-shadow: 0.5px 0.5px 0 1px #000;
    padding: 0.5px;
}
#basic-4 > .theme-color:before { box-shadow: inset 0 0 0 5px #000, inset -7px -7px 0 #000; background: #fff; }
#basic-4 > .theme-color:after  { box-shadow: inset 0 0 0 4px #fff, inset -21px -21px 0 #fff }

#window-wait > .container { padding: 30px 0 }
#window-wait {
    width: 250px;
    height: auto;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
  z-index: 2;
}

/** SNIPPING TOOL **/
#window-snipping { height: auto }
#window-snipping .toolbar { background: #ededed; border-color: transparent }
#window-snipping .toolbar-subitem { min-width: 160px }
#window-snipping .toolbar-item:hover { border-color: #555; box-shadow: inset 0 1px 3px rgba(0,0,0,0.4) }
#window-snipping .toolbar-item {
  color: #000;
  background-size: 25%;
  background-repeat: no-repeat;
  background-position: 5px center;
  padding-left: 25px;
  border: 1px solid transparent;
  border-radius: 3px
}
#window-snipping .direction { background: linear-gradient(#fff 30%, #ededed 70%); border-color: transparent }

/** THEMES **/

/* AERO 1 - WINDOWS 7 */
.aero-1 #windows { background-image: var(--aero-1) }
.aero-1 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-1 .window,
.aero-1 #taskbar,
.aero-1 #start-menu { background-color: var(--aero-1-color) }
.aero-1 .controls > .control:last-child { border-right: 0 }
.aero-1 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}

/* AERO-2 - ARCHITECTURE */
.aero-2 #windows { background-image: var(--aero-2) }
.aero-2 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-2 .window,
.aero-2 #taskbar,
.aero-2 #start-menu { background-color: var(--aero-2-color) }
.aero-2 .controls > .control:last-child { border-right: 0 }
.aero-2 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}

/* AERO-3 - LANDSCAPES */
.aero-3 #windows { background-image: var(--aero-3) }
.aero-3 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-3 .window,
.aero-3 #taskbar,
.aero-3 #start-menu { background-color: var(--aero-3-color) }
.aero-3 .controls > .control:last-child { border-right: 0 }
.aero-3 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}

/* AERO-4 - NATURE */
.aero-4 #windows { background-image: var(--aero-4) }
.aero-4 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-4 .window,
.aero-4 #taskbar,
.aero-4 #start-menu { background-color: var(--aero-4-color) }
.aero-4 #start-menu {
    border-radius: 3px;
  box-shadow: inset 0 0 0 0.5px #fff;
  background-color: var(--aero-4-color);
}
.aero-4 .controls > .control:last-child { border-right: 0 }
.aero-4 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}
/* AERO-5 - more */
.aero-5 #windows { background-image: var(--aero-5) }
.aero-5 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-5 .window,
.aero-5 #taskbar,
.aero-5 #start-menu { background-color: var(--aero-5-color) }
.aero-5 #start-menu {
    border-radius: 3px;
  box-shadow: inset 0 0 0 0.5px #fff;
  background-color: var(--aero-5-color);
}
.aero-5 .controls > .control:last-child { border-right: 0 }
.aero-5 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}        
/* AERO-6 - more */
.aero-6 #windows { background-image: var(--aero-6) }
.aero-6 .window {
  background:
    linear-gradient(135deg, transparent 30%, rgba(255, 255, 255, 0.3) 30%),
    linear-gradient(transparent 20%, #fff 40%, transparent 40%);
}
.aero-6 .window,
.aero-6 #taskbar,
.aero-6 #start-menu { background-color: var(--aero-6-color) }
.aero-6 #start-menu {
    border-radius: 3px;
  box-shadow: inset 0 0 0 0.5px #fff;
  background-color: var(--aero-6-color);
}
.aero-6 .controls > .control:last-child { border-right: 0 }
.aero-6 .controls {
    box-shadow: 0 1px 1px #eee;
    border: 1px solid #666;
    border-top: 0;
}        
/* BASIC-1 - WINDOWS 7 */
.basic-1 #windows { background-image: var(--aero-1) }
.basic-1 .window:before { background: linear-gradient(rgba(0,0,0,0.2), transparent 5%) }
.basic-1 .window,
.basic-1 #taskbar,
.basic-1 #start-menu { background-color: #a7bfd7 }
.basic-1 #start-menu hr { border-color: #999 }
.basic-1 #start-button {
  margin: -6px 3px 0;
  width: 40px;
  height: 40px;
}
.basic-1 .titlebar > .controls { top: 0 }
.basic-1 .controls > .control {
  width: 26px !important;
  margin-left: 3px;
  border: 1px solid #666;
  border-radius: 3px;
}

/* BASIC-2 - WINDOWS CLASSIC */
.basic-2 #windows { background: #3b6ea4 }
.basic-2 .window,
.basic-2 #taskbar,
.basic-2 #start-menu { background: #d0d0d0 }
.basic-2 .window:before,
.basic-2 #taskbar:before,
.basic-2 #start-menu:before { content: none }
.basic-2 #start-button:hover,
.basic-2 #start-button.active { filter: none; border-color: #333 #fff #fff #333 }
.basic-2 #start-button:after { content: 'Start'; padding-left: 26px; font-weight: bold }
.basic-2 #start-button {
  width: 70px;
  height: 26px;
  line-height: 22px;
  margin: 5px;
  background-image: url(https://vignette.wikia.nocookie.net/khangnd/images/e/ee/Windows7-start-button.png/revision/20190724063543);
  background-position: 3px;
  box-sizing: border-box;
}
.basic-2 #start-menu {
  border-radius: 0;
  border-width: 2px;
  border-color: #fff #555 #555 #fff;
}
.basic-2 #start-menu hr { border-color: #eee }
.basic-2 #start-menu > #programs { background: none }
.basic-2 #start-menu > #links { color: #000; border-left: 1px solid #eee }
.basic-2 #start-menu .button { background: none; box-shadow: none;}
.basic-2 #start-button,
.basic-2 #start-menu .button,
.basic-2 .window,
.basic-2 .window .control,
.basic-2 .taskbar-item.left,
.basic-2 .bt {
  border: 2px solid;
  border-color: #fff #333 #333 #fff;
  border-radius: 0;
  color: #000;
}
.basic-2 #start-menu .link:not(:last-child):hover,
.basic-2 #start-menu .program:hover,
.basic-2 .menu-item:hover,
.basic-2 .toolbar-subitem > li:hover { background-color: #082767; color: #fff }
.basic-2 .toolbar-subitem > li:hover { background-image: none }
.basic-2 #start-menu .link:not(:last-child):hover { background-image: none }
.basic-2 .taskbar-item { color: #000 }
.basic-2 #battery { box-shadow: 0 0 0 1px #999; background: #999 }
.basic-2 .storage-bar,
.basic-2 .window {
  border-radius: 0;
  box-shadow: none;
}
.basic-2 .window .controls { top: 0 }
.basic-2 .window .control {
  width: 20px;
  background: #d0d0d0;
  color: #000;
  text-shadow: none;
}
.basic-2 .window > .titlebar { background: linear-gradient(to right, #7f7e78, transparent) }
.basic-2 .window .title { text-shadow: none; color: #fff; font-weight: bold }
.basic-2 .addr,
.basic-2 .addrbar input { border-color: #999 #fff #fff #999 }
.basic-2 .addr { background-color: transparent }
.basic-2 .addrbar input { background: #fff }
.basic-2 .toolbar { background: none; border: none }
.basic-2 .container { border-color: #ddd }
.basic-2 #show-desktop {
  width: 20px;
  background: center center url(https://vignette.wikia.nocookie.net/khangnd/images/a/a2/Windows7-desktop.ico) no-repeat;
  background-size: contain;
}
.basic-2 .taskbar-item.left:before { content: none }
.basic-2 .bt { background: #d0d0d0; box-shadow: none }
.basic-2 .bt-primary { box-shadow: inset -1px -1px 0 #aaa }
.basic-2 .bt-secondary { border-color: #fff #999 #999 #fff }
.basic-2 .storage-bar > div { background: #082767 }
.basic-2 .red-bar > div { background: #e50001 }

/* BASIC-3 - CONTRAST BLACK */
.basic-3 { color: #fff }
.basic-3 #windows,
.basic-3 .window,
.basic-3 .window > .container,
.basic-3 .window > .toolbar,
.basic-3 #taskbar,
.basic-3 #start-menu,
.basic-3 #start-menu > #programs,
.basic-3 .window .control,
.basic-3 .toolbar-subitem,
.basic-3 #window-calc > .container,
.basic-3 .bt,
.basic-3 .button { background: #000; color: #fff; box-shadow: none }
.basic-3 .window,
.basic-3 #start-menu,
.basic-3 .window .control,
.basic-3 .taskbar-item.left,
.basic-3 .bt { border: 2px solid #fff; border-radius: 0 }
.basic-3 .button { box-shadow: 0 0 0 1px #fff; border-radius: 0 }
.basic-3 .window > .titlebar,
.basic-3 #start-menu .program:hover,
.basic-3 #start-menu .link:not(:last-child):hover,
.basic-3 .toolbar-subitem > li:hover { background-color: #81007f; border-color: transparent }
.basic-3 #start-menu .link:not(:last-child):hover { background-image: none }
.basic-3 #taskbar { border-top: 2px solid #fff }
.basic-3 #start-button:hover,
.basic-3 #start-button.active { filter: none }
.basic-3 #start-button:after { content: 'Start'; padding-left: 26px; font-weight: bold }
.basic-3 #start-button {
  width: 70px;
  height: 26px;
  line-height: 22px;
  margin: 5px;
  background-image: url(https://vignette.wikia.nocookie.net/khangnd/images/e/ee/Windows7-start-button.png/revision/20190724063543);
  background-position: 3px;
  box-sizing: border-box;
  border: 2px solid #fff;
}
.basic-3 #show-desktop {
  width: 20px;
  background: center center url(https://vignette.wikia.nocookie.net/khangnd/images/a/a2/Windows7-desktop.ico) no-repeat;
  background-size: contain;
}
.basic-3 .taskbar-item.left:before { content: none }
.basic-3 .window .title { font-weight: bold; text-shadow: none }
.basic-3 .window .controls { top: 0 }
.basic-3 .window .control {
  width: 20px;
  text-shadow: none;
  margin: 2px;
  border-width: 1px;
}
.basic-3 .addr,
.basic-3 .addrbar input { background-color: #000; color: #fff }
.basic-3 .toolbar-item { color: #fff !important }
.basic-3 .toolbar-subitem > li:hover { background-image: none }
.basic-3 .storage-bar { border-radius: 0 }
.basic-3 .storage-bar > div { background: #81007f }
.basic-3 .red-bar > div { background: #e50001 }

/* BASIC-4 - CONTRAST WHITE */
.basic-4,
.basic-4 .icon > label ,
.basic-4 .taskbar-item { color: #000; text-shadow: none }
.basic-4 .window:before,
.basic-4 #taskbar:before,
.basic-4 #start-menu:before { content: none }
.basic-4 #windows,
.basic-4 .window,
.basic-4 .window > .container,
.basic-4 .window > .toolbar,
.basic-4 #taskbar,
.basic-4 #start-menu,
.basic-4 #start-menu > #links,
.basic-4 .window .control,
.basic-4 .toolbar-subitem,
.basic-4 #window-calc > .container,
.basic-4 .bt,
.basic-4 .button { background: #fff; color: #000; box-shadow: none }
.basic-4 .window,
.basic-4 #start-menu,
.basic-4 .window .control,
.basic-4 .taskbar-item.left,
.basic-4 .bt { border: 2px solid #000; border-radius: 0 }
.basic-4 .button { box-shadow: 0 0 0 1px #000; border-radius: 0 }
.basic-4 .window > .titlebar,
.basic-4 #start-menu .program:hover,
.basic-4 #start-menu .link:not(:last-child):hover,
.basic-4 .toolbar-subitem > li:hover { background-color: #000; color: #fff; border-color: transparent }
.basic-4 #start-menu .link:not(:last-child):hover { background-image: none }
.basic-4 #taskbar { border-top: 2px solid #000 }
.basic-4 #start-button:hover,
.basic-4 #start-button.active { filter: none }
.basic-4 #start-button:after { content: 'Start'; padding-left: 26px; font-weight: bold }
.basic-4 #start-button {
  width: 70px;
  height: 26px;
  line-height: 22px;
  margin: 5px;
  background-image: url(https://vignette.wikia.nocookie.net/khangnd/images/e/ee/Windows7-start-button.png/revision/20190724063543);
  background-position: 3px;
  box-sizing: border-box;
  border: 2px solid #000;
}
.basic-4 #show-desktop {
  width: 20px;
  background: center center url(https://vignette.wikia.nocookie.net/khangnd/images/a/a2/Windows7-desktop.ico) no-repeat;
  background-size: contain;
}
.basic-4 .taskbar-item.left:before { content: none }
.basic-4 #battery { box-shadow: 0 0 0 1px #333; background: #333 }
.basic-4 .window .title { font-weight: bold; text-shadow: none }
.basic-4 .window .controls { top: 0 }
.basic-4 .window .control {
  width: 20px;
  text-shadow: none;
  margin: 2px;
  border-width: 1px;
}
.basic-4 .addr,
.basic-4 .addrbar input { background-color: #fff; color: #000 }
.basic-4 .toolbar-item { color: #000 !important }
.basic-4 .toolbar-subitem > li:hover { background-image: none }
.basic-4 .storage-bar { border-radius: 0 }
.basic-4 .storage-bar > div { background: #000 }
.basic-4 .red-bar > div { background: #e50001 }

/** MY COMPUTER **/
.devices {
  display: flex;
  flex-wrap: wrap;
  margin: 5px 0;
  font-size: 80%;
}
.device {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 180px;
  height: 50px;
  padding: 5px 5px 5px 55px;
  background-repeat: no-repeat;
  background-size: 20%;
  background-position: 5px center;
  border: 1px solid transparent;
  border-radius: 3px;
}
.storage-bar {
    height: 13px;
    border: 1px solid #999;
    border-radius: 3px;
    position: relative;
  margin: 2px 0;
}
.storage-bar > div {
  height: 100%;
    background:
        linear-gradient(to right, rgba(0,0,0,0.2), transparent 30%, transparent 70%, rgba(0,0,0,0.2)),
        linear-gradient(to bottom, #56cfe4 40%, #005f7f 50%, #56cfe4 99.9%);
}
.red-bar > div {
  background:
        linear-gradient(to right, rgba(0,0,0,0.1), transparent 30%, transparent 70%, rgba(0,0,0,0.1)),
        linear-gradient(to bottom, #ffbfbf 40%, #e50001 50%);
}
.storage-txt { color: #999 }

/** UTILITIES **/
#windows-container {
    margin: 0;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}
.grayout * { pointer-events: none }
.grayout {
  filter: grayscale(100%);
  -webkit-filter: grayscale(100%);
  transition: 2s;
}
* { cursor: default }
p { margin: 3px }
label { margin: 0 }
h2 {
    text-align: center;
    margin: 0;
}
iframe {
    width: 100%;
    height: 100%;
}
.badge {
    float: right;
    padding: 0 5px;
    display: inline-block;
    color: #fff;
    background: #16c60c;
    line-height: 1;
}
.button.back {
    transform: scaleX(-1);
}
.button {
    display: inline-block;
    padding: 5px;
    box-shadow: inset 0 0 2px #fff, 0 0 2px 1px #1b3a4d;
    border: 0;
    border-radius: 3px;
    color: #fff;
    background: linear-gradient(to bottom,
        rgba(255, 255, 255, 0.2),
        rgba(255, 255, 255, 0.2) 40%,
        rgba(39, 71, 86, 0.5) 50%,
        rgba(39, 71, 86, 0.1) 90%,
        rgba(255, 255, 255, 0.5)
    );
}
.bt:not(:first-child) { margin-left: 5px }
.bt { padding: 1px 15px; font-size: 75%; }
.bt-primary {
    border-color: #3083b7;
    box-shadow: inset 0 0 0 1px #34deff;
    background: linear-gradient(#e7f6fd 50%, #bde3f8 50%)
}
.bt-secondary {
    box-shadow: inset 0 0 0 1px #fff;
    background: linear-gradient(#efefef 50%, #d7d7d7 50%);
}
.round { line-height: 1; border-radius: 50% }
.mt-5 { margin-top : 5px }
.p-0 { padding: 0 !important }
.text-200 { font-size: 200% !important }
.text-75  { font-size: 75% !important }
.text-50  { font-size: 50% !important }
.text-center { text-align: center !important }
.text-right  { text-align: right  !important }
.text-normal { font-weight: normal !important }
.text-bold   { font-weight: bold !important }
.text-muted  { color: #999 !important; pointer-events: none !important }
.icon-sm { background-size: 50% }
.title-1 { color: var(--headline); margin: 8px 0; font-size: 18px }
input[type=search] {
    width: 100%;
    height: 100%;
    padding: 0 5px;
    padding-right: 18px;
    border-width: 1px;
    background-image: url(data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20x%3D%220px%22%20y%3D%220px%22%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%3E%3Cg%3E%3Cpath%20stroke%3D%22%232070b9%22%20d%3D%22M%2010.5%201%20C%208.019531%201%206%203.019531%206%205.5%20C%206%206.558594%206.382813%207.523438%207%208.292969%20L%202.023438%2013.269531%20L%202.726563%2013.980469%20L%207.707031%209%20C%208.476563%209.617188%209.441406%2010%2010.5%2010%20C%2012.980469%2010%2015%207.980469%2015%205.5%20C%2015%203.019531%2012.980469%201%2010.5%201%20Z%20M%2010.5%202%20C%2012.4375%202%2014%203.5625%2014%205.5%20C%2014%207.4375%2012.4375%209%2010.5%209%20C%208.5625%209%207%207.4375%207%205.5%20C%207%203.5625%208.5625%202%2010.5%202%20Z%20%22%3E%3C%2Fpath%3E%3C%2Fg%3E%3C%2Fsvg%3E);
    background-position: 99% center;
    background-repeat: no-repeat;
}
    </style> 
  <script>$(() => {
    'use strict';
     alert('password 2008263 ');
    var isEnter = e => e.key === 'Enter' || e.which === 13;
    
    /** LOGON **/
    $('#password').keyup(e => { if(isEnter(e)) $('#start').click() });
    $('#start').click(e => {
        if($('#password').val() !== '2008263') {
            alert('incorrect password the correct password is 2008263 ');
            return;
        }
        alert('Click About in Start Menu to view info and functional features.\nFollow me for more updates. there are always updates on the code thats why if you copy you will have an outdated version of this emulator i added mor wallpapers in the personalize option also for better expereince on mobile devices turn sound to 100 and turn mobile device to landscape mode and zoom out as much as possiable.there might be some bugs in the emulator if you see any comment on the project and i will fix them for now only 6 of the themes on this emulator work i am trying to make the others work thank you enjoy. ');
        $('#startup')[0].play();
        $('#logon').hide();
        $('#windows').show();
        $('#password').val('2008263');
    });
    
    
    /** TASKBAR **/
    
    // datetime
    var today, date, time;
    var tFormat = 'hh:mm';
    var dFormat = 'dd/mm/yyyy';
    var padZero = o => o < 10 ? '0' + o : o;
    var timer = () => {
        today = new Date();
        time = tFormat
            .replace('hh', padZero(today.getHours()))
            .replace('mm', padZero(today.getMinutes()));
        date = dFormat
            .replace('dd', padZero(today.getDate()))
            .replace('mm', padZero(today.getMonth() + 1))
            .replace('yyyy', today.getFullYear());

        $('#time').text(time);
        $('#date').text(date);
    };
    timer();
    setInterval(timer, 30000);

    // battery
    if(navigator.getBattery) {
        navigator.getBattery().then(battery => {
            $('#gauge')
                .height(battery.level * 100 + '%')
                .css('top', (1 - battery.level) * 100 + '%');
        });
    }
    
    // start menu
    var $menu = $('#start-menu');
    var $btn  = $('#start-button');
    $('body').click(e => {
        $menu.hide();
        $btn .removeClass('active');
    });
    $menu.click(e => e.stopPropagation());
    $btn .click(e => {
        e.stopPropagation();
        $menu.toggle();
        $(e.target).toggleClass('active');
    });
    $('#logoff').click(e => {
        $('#logon').show();
        $('#windows').hide();
    });
    
    
    /** WINDOWS **/
    
    // show desktop
    $('#show-desktop').click(() => {
        var $items = $('.taskbar-item.left');
        if(!$items.length) return; // check opened items
        $items.each((i, item) => $(item.dataset.target).toggle());
    });
    
    // open
    var openw = e => {
        var $target = $(e.target.dataset.target);
        $target.trigger('ontop');

        // window is already opened
        if ($('[data-id=' + $target.attr('id') + ']').length) {
      if (!$target.is(':visible')) $target.show();
      return;
    }
        
        $target.show();
        
        if($target.hasClass('window-child')) return;

        // display icon in taskbar
        var icon = $target.attr('id').split('-')[1];
        $('<div>', {
            'class': 'taskbar-item left minimize ' + icon,
            'data-id': $target.attr('id'),
            'data-target': '#' + $target.attr('id'),
            'appendTo': '#taskbar'
        });
    };
   $(document).on('click', '[data-toggle=window]', openw);
    $('[data-toggle=window]').click(openw);
    
    // close
    $(document).on('click', '.closewin', e => {
        var $target = $(e.target.dataset.target),
            $child  = $($target.data('child'));
        $target.hide();
        $child .hide();
        $('[data-id=' + $target.attr('id') + ']').remove();
    });
    
    // maximize
    $(document).on('click', '.maximize', e => $(e.target.dataset.target).toggleClass('maximized'));
    
    // minimize
    $(document).on('click', '.minimize', e => $(e.target.dataset.target).toggle());
    
    // focus
    var focus = e => {
    var $target = $(e.target).hasClass('window')
      ? $(e.target)
      : $(e.target).parents('.window');
    if($target.hasClass('focused')) return;
        $('.window').removeClass('focused');
        $target.addClass('focused');
    };
    $(document)
    .on('click', '.window', focus)
    .on('ontop', '.window', focus);

    // move
    $('.window').draggable({
        containment: 'parent',
        handle: '.title'
    });
    
    /** DESKTOP **/
    
    // toggle menu
    var menu = $('#desktop-menu');
    var sub  = $('.sub-menu');
    var desktop = $('#desktop');
    desktop
        .on('click', e => {
            // if current target is not desktop menu -> hide
            if($(e.target).parents('#desktop-menu').attr('id') !== 'desktop-menu'
            &&  menu.is(':visible'))
                menu.hide();
        })
        .on('contextmenu', e => {
            if(e.target.id !== 'desktop'
            && e.target.className.indexOf('icons') < 0) return;
            
            e.preventDefault();

            var x = e.offsetX || e.touches[0].offsetX;
            var y = e.offsetY || e.touches[0].offsetY;
            var w = menu.outerWidth();
            var h = menu.outerHeight();
            var dw = desktop.width();
            var dh = desktop.height();
            menu.show()
                .css({
                    left: x + w < dw ? x : x - w,
                    top : y + h < dh ? y : y - h
                });
            if(x + w + sub.width() > dw)
                sub.css({ left: 'initial', right: '100%' });
            else
                sub.css({ left: '98%', right: ''});
        });
    
    //  hide icons
    $('.menu-item:not(.has-sub)').click(() => menu.hide());
    $('.ico-hide').click(e => {
        $('.icon').toggle();
        $(e.target).toggleClass('active');
    });
    
    // resize icons
    $('.ico-size').click(e => {
        var $target = $(e.target);
        $('.icons').attr('class', 'icons icons-' + $target.data('size'));
        $('.ico-size').removeClass('active');
        $target.addClass('active');
    });
    
    // refresh
    var refresh = val => $('.icon').css('opacity', val);
    $('#refresh').click(() => {
        refresh(0);
        setTimeout(() => refresh(1), 100);
    });
    
    // new folder
    var count = 0;
    function Window(title, controls, components) { // Window object
        this.titlebar = $('<div>', { 'class': 'titlebar'});
        this.addrbar  = $('<div>', { 'class': 'addrbar' });
        this.toolbar  = $('<div>', { 'class': 'toolbar' });
        this.content  = $('<div>', { 'class': 'container' });
        this.title    = $('<div>', { 'class': 'title folder' });
        this.controls = $('<div>', { 'class': 'controls' });
        
        this.controls
            .append(this.makeCtrl(controls))
            .appendTo(this.titlebar);
        this.title
            .text(title)
            .appendTo(this.titlebar);
        this.addrbar
            .append([
                $('<div>').append([
                    $('<div class="button round back">&#x279C;</div>'),
                    $('<div class="button round">&#x279C;</div>')
                ]),
                $('<div>', {
                    'class': 'addr folder',
                    append: $('<label>', { text: title })
                }),
                $('<div>', {
          'class': 'input',
                    append: $('<input>', {
                        type: 'search',
                        placeholder: 'Search ' + title
                    })
                })
            ]);
        this.content.append('<div class="text-center text-muted">This folder is empty.</div>');
        var _window = $('<div>', { 'class': 'window', id: 'window-folder-' + count++ });
        _window.append(this.titlebar);
        components.forEach(component => { _window.append(this[component]) });
        return _window;
    }
    Window.prototype.makeCtrl = function(controls) {
        var _controls = [];
        controls.forEach(control => {
            _controls.push(
                $('<div>', {
                    'class': 'control ' + control,
                    'data-target': '#window-folder-' + count,
                    'text':
                        control === 'maximize' ? '□' :
                        control === 'minimize' ? '–' : '×'
                })
            );
        });
        return _controls;
    };

    var $input;
    var rename = target => {
        $(target)
            .parents('.folder')
            .attr('data-target', '#window-folder-' + count);
        $(target).parent().text(target.value);
        $(target).remove();
        new Window(target.value,
            ['minimize', 'maximize', 'closewin'],
            ['addrbar', 'toolbar', 'content']
        )   .appendTo('#desktop')
            .draggable({
                containment: 'parent',
                handle: '.title'
            });
    };
    $('#new-folder').click(() => {
        $input = $('<input>')
            .val('New folder')
            .focus(e => e.target.select())
            .blur(e => rename(e.target))
            .keyup(e => { if(isEnter(e)) rename(e.target) });
        $('<div>', {
            'class': 'icon folder',
            'data-toggle': 'window',
            appendTo: $('.icons > .column'),
            append  : $('<label>', { append: $input })
        });
        $input.focus();
    });
    
    /** CALCULATOR **/
    var $res = $('#result'),
        $op  = $('#operation'),
        flag = false; // calculating flag
    
    var input = e => {
        var value = $res.val(),
            input = e.target.innerText;
        
        if(input === '.' && value.indexOf('.') > 0 // only allow 1 decimal point
        || value.length === 20) // limit 20 digits
            return;
        else if(input === '.' && value === '0') // add zero before decimal point
            $res.val('0.');
        else if(flag || value === '0') {
            flag = false;
            $res.val(input);
        }
        else
            $res.val(value + input);
    };
    
    var calc = e => {
        var v_raw = $res.val(),
            v_num = parseFloat(v_raw),
            input = e.target.innerText,
            operation = $op.val(),
            result = 0;
        switch(input) {
            case '←':
                result = v_raw.length === 1 ? 0 : v_raw.slice(0, v_raw.length - 1);
                break;
            case 'CE':
                result = 0;
                break;
            case 'C':
                operation = '';
                break;
            case '±':
                if(v_raw === '0')
                    return;
                else if (v_raw.indexOf('-') === 0)
                    result = v_raw.slice(1, v_raw.length);
                else
                    result = '-' + v_num;
                break;
            case 'v':
                operation = 'sqrt(' + v_num + ')';
                result = Math.sqrt(v_num);
                break;
            case '%':
                operation = v_num + ' / 100';
                result = v_num / 100;
                break;
            case '1/x':
                operation = '1 / ' + v_num;
                result = 1 / v_num;
                break;
            case '=':
                result = eval(operation + v_num);
                operation = '';
                break;
            default:
                result = eval(operation + v_num);
                operation += v_num + ' ' + input + ' ';
                break;
        }
        flag = true;
        $op.val(operation);
        $res.val(isNaN(result)? 'Invalid input' : result);
    };
    $('.btn-num').click(input);
    $('.btn-fnc').click(calc);
    
    
    /** IE **/
    var $addr = $('#webaddr'),
        $page = $('#webpage'),
        $bing = $('#bing');
    $addr.focus(e => e.target.select());
    $addr.keyup(e => {
        if(!isEnter(e)) return;
        $page[0].src = e.target.value;
    });
    $bing.keyup(e => {
        if(!isEnter(e)) return;
        $page[0].src = 'https://www.bing.com/search?q=' + e.target.value;
    });      
    
    /** NOTEPAD **/
    var $editor = $('#notepad-editor'),
        start, end; // cursor position

    // file
    $('#notepad-new').click(() => $editor.val(''));
    
    // edit
    var copy  = () => document.execCommand('copy');
    var del   = () => document.execCommand('delete');
    var cut   = () => document.execCommand('cut');
    $('#notepad-undo').click(() => document.execCommand('undo'));
    $('#notepad-all') .click(() => $editor.select());
    $('#notepad-datetime').click(() => document.execCommand('insertText', false, time + ' ' + date));
    $editor.blur(e => {
        start = e.target.selectionStart;
        end   = e.target.selectionEnd;
        if(end === start) {
            $('#notepad-cut') .addClass('text-muted').off('click');
            $('#notepad-copy').addClass('text-muted').off('click');
            $('#notepad-del') .addClass('text-muted').off('click');
        } else {
            $('#notepad-cut') .removeClass('text-muted').on('click', cut);
            $('#notepad-copy').removeClass('text-muted').on('click', copy);
            $('#notepad-del') .removeClass('text-muted').on('click', del);
        }
    });
    
    // format
    $('#notepad-wrap').click(e => {
        $editor.toggleClass('wrap');
        $(e.target).toggleClass('active');
    });
    $('#notepad-font').click(e => {
        $editor.css({
            'font-family': $('input[name="font-family"]:checked').val(),
            'font-style':  $('input[name="font-style"]:checked').val().split(',')[0],
            'font-weight': $('input[name="font-style"]:checked').val().split(',')[1],
            'font-size':   $('input[name="font-size"]:checked').val() + 'pt'
        });
    });
    
    /** PERSONALIZE **/
    $('.theme').click(function() {
    var $body = $('#windows-container');
    if ($body.hasClass(this.id)) return;
    
    var $wait = $('#window-wait');
    $wait.show();
    $body.addClass('grayout');
    setTimeout(() => {
      $body.attr('class', this.id);
      $('#theme-name').text(this.innerText);
      $('.theme').removeClass('selected');
      $(this).addClass('selected');
      
      if(/basic-2|basic-3|basic-4/.test(this.id))
        $('#startup')[0].src = 'https://vignette.wikia.nocookie.net/khangnd/images/2/2c/Windows7-startup-sound-classic.ogv';
      else
        $('#startup')[0].src = 'https://vignette.wikia.nocookie.net/khangnd/images/5/58/Windows7-startup-sound.ogg';
      $wait.hide();
      }, Math.random() * 2000);
    });
  
  /** MY COMPUTER **/
  
  // expand
  $('[data-toggle=expand').click(e => $(e.target.dataset.target).toggle() );
  
  // disk space
  function Disk(selector, values) {
    var max = values.max - Math.random() * values.max / 50, // simulate system restore points
      cur = values.cur;
    $(selector + ' > .storage-bar').progressbar({ value: cur, max: max });
    $(selector + ' > .storage-txt').text(
      (max - cur).toFixed(1)
      + ' GB free of '
      + max.toFixed(1) + ' GB'
    );
    
    if((max - cur) / max * 100 <= 10 ) $(selector + ' > .storage-bar').addClass('red-bar');
  };
  
  Disk('#disk-C', { cur: 44,  max: 150 })
  Disk('#disk-D', { cur: 140, max: 150 })
  Disk('#disk-E', { cur: 100, max: 200 })
  Disk('#disk-G', { cur: 2,  max: 8 })
  
  /** SNIPPING TOOL **/
  
  var $snip = $('#snip-result');
  var $wind  = $('#window-snipping');
  var screen = $('#windows')[0];
  
  var options = {
    allowTaint: true,
    imageTimeout: 0
  };
  var show = snip => {
    $wind.show()
       .addClass('maximized');
    $snip.removeClass('direction')
       .html(snip);
  };
  function Overlay() {
    // create a canvas as an overlay
    this.canv = $('<canvas>', {
      appendTo: screen,
      attr: {
        width:  $(screen).width(),
        height: $(screen).height()
      },
      css: {
        'z-index': '9999',
        position: 'absolute',
        cursor: 'crosshair'
      }
    });
    var canv = this.canv[0];
    this.ctx = canv.getContext('2d');
    this.ctx.lineWidth = 1;
    this.ctx.strokeStyle = 'red';
    this.ctx.fillStyle = 'rgba(255, 255, 255, 0.6)';
    this.ctx.fillRect(0, 0, canv.width, canv.height);
  }
  var snipArea = () => {
    var x, y, x1, y1, rect;
    var overlay = new Overlay();
    var ctx  = overlay.ctx;
    var canv = overlay.canv;

    // event handlers
    $(screen).on('mousedown touchstart', function(e) {
      // get start offsets
      x = e.offsetX || e.touches[0].clientX - $(e.target).offset().left;
      y = e.offsetY || e.touches[0].clientY - $(e.target).offset().top;
      
      $(this).on('mousemove touchmove', function(e) {
        // get end offsets
        x1 = e.offsetX || e.touches[0].clientX;
        y1 = e.offsetY || e.touches[0].clientY;
        rect = {
          x: x1 > x ? x : x1,
          y: y1 > y ? y : y1,
          width : Math.abs(x1 - x),
          height: Math.abs(y1 - y)
        };
        
        // highlight rect
        ctx.clearRect(0, 0, canv[0].width, canv[0].height);
        ctx. fillRect(0, 0, canv[0].width, canv[0].height);
        ctx.strokeRect(rect.x, rect.y, rect.width, rect.height);
        ctx. clearRect(rect.x, rect.y, rect.width, rect.height);
      });
      
      $(this).on('mouseup touchend', function(e) {
        // get snip and clear up events
        html2canvas(screen, $.extend(rect, options)).then(show);
        canv.remove();
        $(this)
          .off('mousedown mouseup mousemove')
          .off('touchstart touchmove touchend');
      });
    });
  };
  $('.snip').click(e => {
    switch(e.target.id) {
      case 'snip-rect':
        $wind.hide();
        snipArea();
        break;
      case 'snip-win':
        // $wind.hide();
        // snipWind();
        break;
      case 'snip-full':
        html2canvas(screen, options).then(show);
        break;
    }
  });
  $('#snip-cancel').click(e => {
    $wind.removeClass('maximized');
    $snip.addClass('direction')
       .html('Select snip mode to start snipping.');
  });
});
  const alertOnlineStatus = () => {
    window.alert(navigator.onLine ? 'wifi online please press ok to run emulator made for pc only' : 'wifi offline reload to run emulator made for pc only')
  }

  window.addEventListener('online',  alertOnlineStatus)
  window.addEventListener('offline',  alertOnlineStatus)

  alertOnlineStatus()
        
    </script> 
  <script> navigator.getBattery().then(function(battery) { 
    var level = battery.level; 
    document.getElementById("batt").innerHTML = Math.round(Number(level*100)) + "%";
    console.log("your battery level is "+level*100+"%");</script> 
  <script></script> 
 </body>
</html>
