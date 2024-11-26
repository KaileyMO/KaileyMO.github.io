[Back to Portfolio](./)

Machine Learning Project
===============

-   **Class: Fund of Artificial Intelligence (CSCI 409)** 
-   **Grade:** 
-   **Language(s): Python** 
-   **Source Code Repository:** [Machine Learning Code](https://github.com/KaileyMO/ai_machine_learning)  
    (Please [email me](mailto:kmowens@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project collects data from a dataset and then uses this data for machine learning. The program reads in from a dataset and splits it up to test and train multiple models to find the most highly predictable consistencies within the dataset. One of this program's goals is to discover if there is a correlation between an increased abstract count and an increased citation count within the dataset. Around six graphs are created based on these values.

## How to compile and run the program

To run this python program, open up an operating system that runs python and go to the folder containing the code file. For an operating system, type something like this to access and then run the program:

```bash
cd ./folder-with-code
python machine_learning.py
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
pip install pandas numpy scikit-learn matplotlib requests scipy
```

This can work with the IDLE operator as well; input the file explorer's .py file location into Command Prompt, which is found by inputting cmd in the window's search feature, and type the installations there.

```bash
cd ./folder-with-code

pip install pandas numpy scikit-learn matplotlib requests scipy
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

This program requires a csv file titled "papers.csv" to be in the same location as the running code for it to work. Download it in the source code's repository for the program to work as intended.

[Back to Portfolio](./)
