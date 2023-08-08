# AWS-Cloud-Security
INE Labs

> Objective: 
* GuardDuty: Cloud Watch
* AWS CloudTrail: Creating Trail
* AWS CloudTrail: Athena and CloudWatch Alerts


# GuardDuty: Cloud Watch

Time spent:

> Goal:
* Set up GuardDuty to automatically send notifications via email of GuardDuty findings depending on their severity.


# AWS CloudTrail: Creating Trail

Time spent:

> Goal:
* Create trails for various types of events using AWS CloudTrail and deliver log files to an S3 Bucket.


# AWS CloudTrail: Athena and CloudWatch Alerts

Time spent:

> Goal:
* Process the data with Amazon Athena and configure AWS CloudWatch alerts for CloudTrail events.


# Trello-CLI
A CLI Program that lets you add comments, labels directly into the Trello
website directly from a single command in the terminal. The program uses Click for it's CLI functionality

![Trello](trello_tf2u.jpg)


# Requirements
- Python3
- Pip3
- Venv(For Virtual Environment)

# Getting Started (No Virtual Environment)
1. Install by typing in terminal
- ``` git clone ```
2. Make sure you are in the correct directory in termianl
- ```cd Trello-CLI/```
3. Build the project
- ```pip3 install --editable .```
4. Open the keys.txt file in /Trello directory and add your key, token, and board ID # from trello.(Example shown below)
5. Once in the Trello directory type Trello in the console ```Trello``` and follow the instructions
- If the Terminal says it doesn't recognize the command "Trello" it means you need to add a $PATH line to your .bashrc file
- Open up the .bashrc file in whichever editor you choose ```vi ~/.bashrc```
- Add this line to the bottom of the file
- export PATH="$HOME/.local/bin:$PATH"

# Getting Started (With virtual Environment)
1. Install by typing in terminal
- ``` git clone ```
2. Make sure you are in the correct directory in termianl
- ```cd Trello-CLI/```
3. Open up the virtual Environment by typing
- ```virtualenv env```
4. Build the venv by typing
- ```source venv/bin/activate```
3. Build the project
- ```pip3 install --editable .```
4. Open the keys.txt file in /Trello directory and add your key, token, and board ID # from trello.(Example shown below)
5. Run the project
- ```cd Trello/```
- ```Trello```


![Example](trello_tf2u.jpg)

# Next Development Steps
- Make the UI easier to read in terminal
- Let users be able to type a number that is correleated to a specific ID instead of having to copy/paste the ID numbers
- Add functionality such as being able to remove labels, create brand new labels, create a board, remove a board, etc.
