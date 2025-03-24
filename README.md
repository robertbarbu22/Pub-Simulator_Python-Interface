# Pub Simulator - Python Interface



# Group Time Reporting
The first meeting is on Feb 12. Read the requirements and get the main points from it.
The second meeting on Feb 17 go through the prototype and polish
Feb-19 meeting supervision with professor-confirm the prototype and details
Feb 24 meeting go through the code structure and start coding for the model part
Feb 26 meeting go through everyone’s model code and move to the controller
Mar 03 meeting Controller code and together with view code
Mar 11  meeting go through everyone’s codes and fix
Mar 13  meeting start to pitch them step by step
Mar 17 meetinggo through all the functions
Mar 18 meeting Practice for presentation
Mar 19 meeting Practice for presentation

# Structure
Our system have two sides: Customer side and Bartender side
We finished each first, and then combined them together

bar-management-system/
├── Models/                     
│   ├── BarModel.py            
│   ├── MenuModel.py           
│   ├── Order_Payment_Model.py 
│   ├── TableModel.py          
│   └── UserModel.py           
├── Controllers/                
│   ├── MenuController.py      
│   ├── OrderController.py     
│   ├── Order_bar_controller.py
│   ├── TableController.py     
│   ├── TranslationController.py 
│   └── UserController.py      
├── Views/                      
│   ├── BartenderView.py       
│   ├── CustomerView.py        
│   ├── LoginView.py           
│   ├── MainView.py            # For the customer side
│   ├── MenuView.py
│   ├── OrderViewClass.py       
│   └── Order_bar_view.py
├── Assets/                     
│   ├── ChineseTranslation.json 
│   ├── EnglishTranslation.json 
│   └── SwedishTranslation.json 
├── Database/                   
│   ├── MenuDB.json            
│   ├── OrderDB.json           
│   ├── PaymentDB.json        
│   ├── TablesDB.json          
│   └── UsersDB.json           
├── Images/               
├── test bartenderuser.py   # bartender side interface
├── test user.py    # Customer side interface
├── MainProgram.py             # Run this program to start
└── README.md                   # Description

# Run program
Please run MainProgram.py to start

# Login account
Customer: 
Username "Alice Smith"，Password "password123"
Bartender:
Username "Charlie Brown"，Password "helloWorld789"

# Chatbot help
We used Claude, Deepseek, Chatgpt to help us to fix the error and adjust the interface

# Self Time Reporting
Mu Tang
Feb 17-Feb 19 Working on the prototype with Figma
Feb 24-Feb 26 Coding on the bartender side order model
Feb 26-Mar 07 Coding for the Bartender side order function
Mar 14 Coding on forming the bartender interface and link the orderDB with bartender order list
Mar 15 Coding on creating the main view for the program
Mar 16 Coding on adding the language switching function
Mar 18 Coding on adding the UNDO-REDO function
Mar 18-Mar 19 Preparing presentation

Hao Zuo
Feb 12-Feb 15 Working on the prototype with Figma
Feb 17-Feb 19 Going through requirements and Studying for MVC separation
Feb 24-Feb 26 Designing the user side model and simple user database
Feb 26-Mar 03 Building the control for detailed functions
Mar 03-Mar 11 Coding and debugging for the LoginView/CustomerView and main frame
Mar 11-Mar 17 Adjusting functionality for connection with others' parts
Mar 18-Mar 19 Preparing presentation
Mar 21-Mar 23 Modifying code and comments

