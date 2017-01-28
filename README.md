# Things-I-Wish-I-Knew
Things I wish I knew when I started up; God knows it would have saved me a lot of Googling...

### 1) Customizing Sublime Text Editor 3 to build .html with Chrome in Windows:
(1) Copy below (change chrome.exe path if yours is different) and save as **buildSystemName**.sublime-build in your ST3 folder which is in 
C:\Users\ __yourUserName__ \AppData\Roaming\Sublime Text 3\Packages\User
~~~~
{
	"cmd": ["C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe", "$file"] 
}
~~~~
(2) Select **buildSystemName** as your build system: Tools > Build Systems > buildSystemName

(3) Ctrl+B efficiency!!!!

[step-by-step instructions here](http://www.c-sharpcorner.com/UploadFile/370e35/how-to-configure-sublime-text-to-open-html-file-in-chrome-on/)

### 2) [Using ST3 efficiently](https://www.youtube.com/watch?v=utLIfDpGKsY)

### 3) 
