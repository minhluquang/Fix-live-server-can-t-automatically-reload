# Fix live server extention can't automatically reload !
*<p align = "center">📑 Detailed article: <a href = "https://viblo.asia/p/live-server-lam-gi-khi-cai-vs-code-extension-than-yeu-tro-chung-Do754AP4KM6">Click here</a>    (Source: @khangnd)</p>*
<h1>💡Solution</h1>
<p> - First, the thing to do is <i><b><a href = "https://nodejs.org/en/">install NodeJS</b></i> because the Live Server is a Node package.</p>
<p> - After installing Node, you open <i><b>cmd</b></i> or <i><b>command line</b></i> of VS Code to install the <i><b>Live Server package</b></i> with the command: </p>

```
npm i live-server -g
```
<p> - So we have installed, from now on each time we need to host a certain folder or file, just open that folder in VS Code, or point to the directory path and run the live-server command in the command line.</p>
<h1>💫 Server Configuration Changes</h1>
<p> When you need to change the server configuration, such as IP or port, just pass the corresponding arguments to the CLI. Visit the repo for a full list of supported arguments. For example to change the default port to 3000, and open it in Firefox after the server is enabled:</p>

```
live-server --port=3000 --browser=Firefox
```

<h1>☑️ Activate with keyboard shortcuts</h1>
<p> - In VS Code, press the <i><b>F1</i></b> key, a Command Palette will appear including all the functions of VS Code.</p>
<p> - Type in keyboard shortcuts and select <i><b>Preferences: Open Keyboard Shortcuts (JSON)</i></b></p>

```
{
  "key": "alt+l alt+o",
  "command": "workbench.action.terminal.sendSequence",
  "args": {
    "text": "live-server --port=3000 --browser=Firefox\u000D"
  }
}
```

<h1>🔥 How to use?</h1>
<p>From now on, each time we want to activate the Live Server, we just need to open the CLI <i><b>(press Ctrl + ')</i></b> and the key combination <i><b>Alt + L, Alt + O</i></b> is done.</p>

<h1>🔓  If you have done the above but still get the error!</h1>
- If you've done the above but failed then try this, I'm pretty sure it will fix the error of not reloading the page itself.
</br>
  <i><b>Extention name: <a href = "https://marketplace.visualstudio.com/items?itemName=yandeu.five-server">Live Server (Five Server)</i></b></br>
  <i><b>Current version in use: v0.1.11</i></b> </br>
<p>- You can find it in VS Code</p>
<div align = "center">
  <img width = 100% src= "https://github.com/binvan789/Fix-live-server-can-t-automatically-reload/blob/main/liveserver.png">
</div>

</br>
</br>




><p align = "center">Contact: <i><a href = "mailto: luminh2004@gmail.com">luminh2004@gmail.com</a></i></p>
