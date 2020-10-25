<div style="margin-top:-3.4em;margin-bottom:-1em;"class="gradient">
  <h1>8-log Archive</h1>
</div>
<div style="background: transparent url(https://api.netlify.com/api/v1/badges/95b6550b-d1cb-44d6-912d-011055d10ccd/deploy-status) no-repeat; height: 50px; width: 300px;"></div>

<h2><i class="fa fa-question-circle"></i> Search</h2>
Searching the article should be easy with full-text search and per-word to search any writing records. If you're on the server it possible to searching this material in command line interface

```
$ python auto.py
...
```

* I will update soon

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
