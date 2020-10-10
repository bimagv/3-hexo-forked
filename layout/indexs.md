<div style="margin-top:-3.4em;margin-bottom:-2.5em;"class="gradient">
  <h2>8-log Archive</h2>
</div>

<div style="background: transparent url(https://api.netlify.com/api/v1/badges/95b6550b-d1cb-44d6-912d-011055d10ccd/deploy-status) no-repeat; height: 50px; width: 300px;"></div>

This site are build with [hexo](https://hexo.io) *static site generator*.. it's like JAVASCRIPT anyWEH but this archive come in with each topic in one site so, maybe it complicated like my mind.

Visit the [page](space/) for another listing of article and [man](space/man) space filled with random writtings.

<header class="global">
<p class="help">
	<span>need help?</span>
	<a href="https://t.me/bimagv" onclick="return SnapABug.startLink();" class="chat">
		t.me/bimagv
	</a>
</p>
  <div class="mimi"></div>
</header>
<style>
header.global  {
text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
}
header.global p.help:hover {
-moz-transform: scale(1) translateZ(0);
-webkit-transform: scale(1) translateZ(0);
-o-transform: scale(1) translateZ(0);
-ms-transform: scale(1) translateZ(0);
transform: scale(1) translateZ(0);
}
header.global p.help {
width: 210px;
height: 95px;
background-position: center center;
background-image: url(https://res.cloudinary.com/bimagv/image/upload/v1602343992/icon/cloud_x7d4vi.png);
background-repeat: no-repeat;
position: absolute;
margin: 0;
padding: 45px 0 0 0px;
right: 60px;
color: #666;
bottom: 180px;
z-index: 1;
text-align: center;
font-size: 15px;
line-height: 1.4;
-moz-transform: scale(0.9) translateZ(0);
-webkit-transform: scale(0.9) translateZ(0);
-o-transform: scale(0.9) translateZ(0);
-ms-transform: scale(0.9) translateZ(0);
transform: scale(0.9) translateZ(0);
-webkit-transform-origin: 0 100% "";
-moz-transform-origin: 0 100% "";
-ms-transform-origin: 0 100% "";
-o-transform-origin: 0 100% "";
transform-origin: 0 100% "";
-webkit-transition: transform 0.1s ease-in-out;
-moz-transition: transform 0.1s ease-in-out;
-ms-transition: transform 0.1s ease-in-out;
-o-transition: transform 0.1s ease-in-out;
transition: transform 0.1s ease-in-out;
 color: #666;
text-align: center;
font-size: 15px;
line-height: 1.4;
}
header.global p.help a {
display: block;
color: #f03;
}
header.global .mimi {
height: 242px;
width: 100%;
position: absolute;
bottom: 0;
right: 0;
background-position: right top;
background-image: url(https://res.cloudinary.com/bimagv/image/upload/v1602345365/icon/header_werku_qhvi0e.png);
background-repeat: no-repeat;
}
.gradient {
   position: relative;
}
.gradient:after {
   color:#000;
   position: absolute;
   top: 0;
   left: 0;
   z-index: -1;
}
.gradient h2 {
    /* Fallback: Set a background color. */
  background-color: #CA4246;
  /* Create the gradient. */
   background-image: linear-gradient(
        45deg,
        #CA4246 16.666%, 
        #E16541 16.666%, 
        #E16541 33.333%, 
        #F18F43 33.333%, 
        #F18F43 50%, 
        #8B9862 50%, 
        #8B9862 66.666%, 
        #476098 66.666%, 
        #476098 83.333%, 
        #A7489B 83.333%);
  /* Set the background size and repeat properties. */
  background-size: 100%;
  background-repeat: repeat;
  /* Use the text as a mask for the background. */
  /* This will show the gradient as a text color rather than element bg. */
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent; 
  color: #111111;
  font-size:2.1em;
  /* -webkit-mask-box-image: -webkit-gradient(linear,
            left top, left bottom,
            color-stop(20%,rgba(0,0,0,1)),
            color-stop(100%,rgba(0,0,0,0)));
              font-weight: normal;*/
  font-size: 4em;
  width: 505px;
}
</style>

# Overview
> This site will be shown all ```post``` article in one place, then the command line reference and other writings will be placed in [space](space/)

<h2><i class="fa fa-question-circle"></i> Search</h2>
Searching the article should be easy with full-text search and per word. I won't lose any writing records. if you're on the server, it's possible! to searching this material in command line 

```
$ python auto.py
```

Alternatively just running on the server

```
$ git clone 
```

This archive was set with keybinds or keyboard shortcut. scroll up/scroll down: ```j``` /```k```,  full-text search: ```i```, full full-screen: ```s```, post-toc-menu: ```w```

<div class="keybinds">
  <h2><i class="fa fa-question-circle"></i> Main Shortcuts</h2>
  <table>
    <tr>
      <td><kbd>j</kbd><kbd>k</kbd></td>
      <td>Scoll up and scroll down</td>
    </tr>
    <tr>
      <td><kbd>i</kbd></td>
      <td>Using full-text search</td>
    </tr>
    <tr>
      <td><kbd>s</kbd></td>
      <td>Entering full-read mode or enable navbar</td>
    </tr>
    <tr>
      <td><kbd>w</kbd></td>
      <td>Entering post-toc-menu</td>
    </tr>
  </table>
</div>

<style>
      keybinds {
      /* background: url(https://i.imgur.com/4e5dUxi.jpg); */
      font-family: "Monaco";
      font-size: 12px;
      line-height: 1.2;
      margin: 0;
      padding: 0;
    }
    table {
      border-collapse: collapse;
      margin-bottom: 5em;
    }
    tr {
      outline: 1px solid rgba(0, 0, 0, 0);
    }
    tr:hover {
       outline-color: rgba(0, 0, 0, 0.2);
    }
    tr:hover td {
      background-color: #e7e7e7 !important;
    }
    tr, td {
      transition: all 210ms ease-in-out;
    }
    td {
      padding: 0.3em 1em;
      vertical-align: middle;
    }
    td:first-child {
      text-align: center;
      width: 35%;
      white-space: nowrap;
    }
    kbd {
      background-color: #fff;
      border: 1px solid #ccc;
      color: #333;
      line-height: 1.4;
      text-shadow: 0 1px 0 #fff;
      display: inline-block;
      white-space: nowrap;
      box-shadow: 1px 0 1px 0 #eee, 0 2px 0 2px #ccc, 0 2px 0 3px #444;
      border-radius: 3px;
      box-sizing: border-box;
      position: relative;

      text-align: center;
      margin: 0.5em 2em 1em 0;
      padding: 0.9em 0;
      width: 3em;
    }
    kbd:hover {
      box-shadow: 1px 0 1px 0 #ccc, 0 2px 0 2px #eee, 0 2px 0 3px #ddd;
    }
    kbd:after {
      content: "+";
      display: block;
      padding: 0 0 0 0.8em;
      position: absolute;
      left: 100%;
      top: 0.9em;
    }
    td > kbd:last-child:after {
      content: "";
      display: none;
      padding: 0;
      position: static;
    }
    tr:nth-child(odd) td {
       background: #f7f7f7;
    }
</style>