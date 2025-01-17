# RunX (Edit: do not use this tool, doesnt work properly, also is using external resources, not worth it)
Online compiler for competitive programmers and all the coding enthusiasts.

## Install
```pip3 install poetry```  
```pip3 install dj-database-url```  
```pip3 install django-compression-middleware```  
```pip3 install shortuuid```  
```poetry install```

## SQL migration script
```
CREATE TABLE "runx_database" (
"id"	INTEGER,
"uid"	TEXT,
"lang"	TEXT,
"fname"	TEXT,
"src"	TEXT,
PRIMARY KEY("id" AUTOINCREMENT)
);
```

## Run
```python3 manage.py runserver```

## Features
* 👉 Use it as a simple compiler.
* 👉 Autosaving code at every 10 seconds.
* 👉 Solve single problem or all the problems of any contest in a single window.
* 👉 Inbuilt whiteboard which can help you to build logic for problems.
* 👉 Automatic test case integration (No need to copy paste sample test cases and run them individually). 
* 👉 Compare your output with the sample test case output.
* 👉 Check your saved files in the bookmarks tab.
* 👉 Search and sort files by various fields like filename, date, lastedit, etc.
## Supported Languages
* C
* C++
* Java
* Python
## Video


https://user-images.githubusercontent.com/55176863/125821183-0082124d-4369-4886-a4d0-cb4f30574368.mp4


## ScreenShots
### HomePage
![HomePage](./ScreenShots/Homepage2.png)
### CreateFile
![CreateFile](./ScreenShots/Codeforces_file.png)
### Problem View
![ProblemView1](./ScreenShots/ProblemView1.png)
![ProblemView2](./ScreenShots/ProblemView2.png)
### Whiteboard
![WhiteBoard](./ScreenShots/WhiteBoard.png)
### Theme
* Default
![Default](./ScreenShots/Default.png)
* Sublime
![Sublime](./ScreenShots/Sublime.png)
* Light
![Light](./ScreenShots/Light.png)
### Bookmarks
![Bookmarks](./ScreenShots/Bookmarks2.png)

## Star this repo if you liked this project.
