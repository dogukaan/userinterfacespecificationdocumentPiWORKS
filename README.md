# user interface specification document for PiWORKS
PiWORKS user interface specification document
## Introduction
User interface specification sheet

## Purpose
To make the features of the given user interface understandable and codable for software engineers



![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/intro.png)

                                          Picture 1 : User Management Screen
## User interface
We divide the user interface given to us into three parts
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/alltopics.png)
* Part 1 Top bar
* Part 2 User information
* Part 3 New user form

### PART 1 Top Bar
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/topbar.png)

We will examine the ball bar in 3 parts.
> * Top Bar
> 1. New User button
> 2. Hide disabled  users button
> 3. Save user button


#### 1. New User Button
When the new user button is pressed, the new user adding panel opens and the necessary information is entered in the panel (we will examine this in the third part). 

#### 2. Hide Disabled User Checkbox
This checkbox helps to hide deactivated users from the user list (we will examine the user list in the second part).

#### 3. Save User Button
This button saves the user data written on the screen and sends it to the database.

###  PART 2 User Details 
We will examine here in 5 parts.

![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/userlist.png)

> - User Details
> 1. Sorting by ID button
> 2. Sorting by User Name button
> 3. Sorting by Email button
> 4. Sorting by User Status
> 5. Show User List

#### 1. Sorting by ID button
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/ID.png)

By pressing this button, the IDs are filtered from large to small or large to small.

#### 2. Sorting by User Name button
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/username.png)

This button sorts by User Name. User Name is string variable. It sorts alphabetically. (A-Z or Z-A)

#### 3. Sorting by Email button
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/email.png)

This button sorts by Email. Email is string variable. It sorts alphabetically. (A-Z or Z-A)

#### 4. Sorting by User Status
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/enabled.png)

This button sorts by User Status. User Status is boolean variable. Boolean working principle is true or false. So it sorts enabled to disabled or disabled to enabled. 

#### 5. Show User List
![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/userlistdetail.png)

This section shows user informations. Informations included ID, User Name, Email, User Status(Enabled-Disabled)

### PART 3 New User Register
We will examine here in 6 parts.

![](https://github.com/dogukaan/userinterfacespecificationdocumentPiWORKS/blob/main/newuserregister.png)

>- New User Register
> 1. Username Textbox
> 2. Display Name Textbox
> 3. Phone Textbox
> 4. Email Textbox
> 5. User Role Menu
> 6. User Status Checkbox

#### Username Textbox
The username of the user to be registered is entered here.

#### Display Name Textbox
The phone number of the user to be registered is entered here.

#### Phone Textbox
The phone number of the user to be registered is entered here.

#### Email Textbox
The email of the user to be registered is entered here.

#### User Role Menu
User roles are divided into three parts
1-guests (can only see their own information)
2-Admin (Can see, edit but not delete all users)
3-Super Admin (Can do all operations) 

This is continued by selecting the required roles.

#### User Status Checkbox
If the user is an active user, then this is marked.
After all the necessary boxes are filled in, click the save user button and the page is refreshed.
The new user switches to the user list.
