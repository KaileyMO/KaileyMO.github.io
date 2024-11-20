[Back to Portfolio](./)

Webscraping Project
===============

-   **Class: Survey of Scripting Languages (CSCI 301)** 
-   **Grade: 100** 
-   **Language(s): Python** 
-   **Source Code Repository:** [Webscraping Program](https://github.com/KaileyMO/Webscraping-Project)  
    (Please [email me](mailto:kmowens@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This program pulls from a website containing a short list of jobs. It displays the job titles and a link to them, and then picks three of the jobs that I consider my favorite options. The program lists jobs from a website and then lists my three preferred options.

## How to compile and run the program

To run this python program, open up an operating system that runs python and go to the folder containing the code file. For an operating system, type something like this to access and then run the program:

```bash
cd ./folder-with-code
python webscraping_program.py
```

If you need software to run python, here is a sufficient system that installs and runs python code, called IDLE: [IDLE download](https://www.python.org/downloads/)

Once downloaded, go to the source code repository and download the .py file containing this program's code. Right click this downloaded file and select "Edit with IDLE {IDLE version}" (Fig 1).

![screenshot](images/run_python1.png)  
Fig 1. Run code step 1  

Now, run this code through "Run module", or F5 (Fig 2).

![screenshot](images/run_python2.png)  
Fig 2. Run code step 2

### Install

This coding project itself uses libraries such as "requests" and "beautifulsoup", so the system may need to have them installed to run this program. Here are examples of how to install to the system:

```bash
pip install requests

pip install beautifulsoup4
```

This can work with the IDLE operator as well; input the file explorer's .py file location into Command Prompt, which is found by inputting cmd in the window's search feature, and type the installations there.

```bash
cd ./folder-with-code

pip install requests

pip install beautifulsoup4
```

## UI Design

This project prints information to the screen. It looks through the list of jobs from the website [pythonjobs.github.io](https://pythonjobs.github.io/), and picks out three favored jobs from the list. After running the program, the lists are displayed that the user can analyze (Fig 3).

![screenshot](images/webscraping_icon.png)  
Fig 3. The display screen

[Back to Portfolio](./)
