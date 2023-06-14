# Qauto
_QAUTO_ - a site where you can create a garage of your cars, add and monitor their mileage and expenses.

# Structure
#### This repository contains:

1. Tests that verify validators of the fields in the Sign Up form in Product
Additionally, I have identified and added two bugs.

2. A checklist has been created containing a dataset that considers equivalence classes 
and boundary values to verify the following fields in the "Add an expense" and "Edit an expense" dialog windows.

3.  Functional tests in Jmeter for user authorization on the project.
    - verification _Car brands_, _Car models_, _User SignUp,SignIn and Delete user_, _Authenticated user profile data_, _Creating new car_.

While running the tests, I found two bugs in _Creating new car _  (Response code and Response message)
<img src="https://github.com/Marusha-Korda/Qauto/blob/main/Response%20code.png" width="792" height="440">

<img src="https://github.com/Marusha-Korda/Qauto/blob/main/Response%20message.png" width="792" height="440">

You can find API documentation [here](https://docs.google.com/document/d/1_GwAjYmz1jbiwA1T7jJFHr3rykg7Kx_tn7YkcDyGNJU/edit?usp=sharing)

# Setup Functional tests in Jmeter
- Clone this repository:
  - Navigate to https://github.com/Marusha-Korda/Qauto.git
  - Click on Clone or Download and copy the project url
  - Open the command line terminal
  - Navigate to the desired directory for the project
  - Execute git clone [ProjectURL]
- Running the tests in Jmeter:
  - Open file (functional  tests.jmx) in Jmeter
  - Open View Results Tree and star run collection 
  <img src="https://github.com/Marusha-Korda/Qauto/blob/main/Run%20collection.png" width="792" height="440">
