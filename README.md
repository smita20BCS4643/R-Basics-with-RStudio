# R-Basics-with-RStudio
R Basics with RStudio

# RStudio main UI
In this lab, you will be introduced to RStudio, the most popular and powerful IDE for developing R projects.

The main UI of RStudio is shown here:

RStudio user interface 

![image](https://github.com/user-attachments/assets/f6acacba-3fb8-4b5a-9c95-35eba131ad16)


In the Console panel, you can quickly try some R commands and see the results immediately.

In the File Editor panel, you can write your R code or other text files with the help of syntax highlighting and auto completion.

In the Workspace panel, you can review and manage the created objects.

In the File/Plots/Package Explorer panel, you can manage your files and other assets, such as plots or packages.



# Write the first Hello World code snippet in the Console
Let us write your first Hello World in RStudio Console.

Find the blinking cursor in the Console panel, type an incomplete ``` prin ``` or  ```print``` and pause a little bit for RStudio to show a pop-up suggestion list:
Console panel pop-up suggestion list

![image](https://github.com/user-attachments/assets/c296bd1a-da32-460e-84b7-39e70ff6db81)


The auto-complete feature of RStudio can help avoid the need for memorizing the code details and reducing keystrokes by just selecting from a suggestion list.

Select the __print_ function and add a character input ___Hello World!_, then press the Enter key:
1
``` print("Hello World!") ```

Copied!
You should see __Hello World!__ printed on the console.

Hello World! code snippet

![image](https://github.com/user-attachments/assets/1bdbddff-e63b-4221-8218-536ee7896ee1)

![image](https://github.com/user-attachments/assets/4fd669a7-4799-4257-b053-85b1abb4b7d8)


That’s it, you have written your first Hello World code snippet in RStudio.

For practice, you can play with the console by typing anything you have learned so far, such as creating variables and doing basic math operations.

If you want to clear the console, you can press Ctrl or Control + L key combination.


# Review R objects in the Environment panel
Now let’s try the Environment panel to review the R objects we created in the console.

Type and run the following three lines of code in the console:

``` x<-1 ```

``` y<-2 ```

```
z<-x+y 
```

You should see three variables x, y, z with assigned values in the Environment panel.
Variables __x, y, and z_ with assigned values

![image](https://github.com/user-attachments/assets/6d9fcda1-2f97-48a4-8b08-42fdffaf516d)


To clean the workspace, you can click the Broom icon as shown below:
Workspace shows ``` Broom ``` icon

![image](https://github.com/user-attachments/assets/2ccc5a4d-f54d-4776-842b-40aeed1e8423)


# Create your first R script file
By now, you have written some simple R code in the console interactively. Next, create an R script file with multiple lines of code and run them in batch mode.

First, from the menu click ``` File > New File > R Script. ```

![image](https://github.com/user-attachments/assets/f0fe190a-be1a-4728-b3d2-a368d4a7b62b)


Then click ``` File > Save ```, and name the file something like ``` first_script ```. After the script file is saved, you can see an empty file called ``` first_script.R ``` file created in your working directory.

![image](https://github.com/user-attachments/assets/cf3912f9-b0d3-4551-87fd-260e0bc39b6f)


Next, click __first_script.R_ file to add the following code snippet:

```
x <- 3
y <- 4
z <- x + y
print(z)

```

You need to make sure the last line of the file is a new empty line.

Now, you can run the code in the script file, there are two running modes:

The first mode is called **Run the current line or selection**. You can click and drag your mouse or use **Shift + Up/Down keys to select all lines** and then click the following **Run icon** to run them:

![image](https://github.com/user-attachments/assets/7157bb92-21c2-4ca6-bc79-11bb0355d520)

You should see the results in the console:

![image](https://github.com/user-attachments/assets/093ba0ed-1c1c-4135-9bf2-88e537ceb68d)

That’s it about creating and running the R script file!

