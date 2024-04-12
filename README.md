# 22CSH-293-Group2-ST
# SURPRISE TEST – SET B (EVEN)
## Name : Sakshi
## UID : 22BDO10064
## Section & Group : 22BCD-1/B
## Subject : Git and GitHub

### Problem :- 
The task, you again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git. Hint: git switch will make you switch from one branch to another.
1.	Use git branch to see the two branches that are relevant for this exercise
2.	What branch are you on?
3.	Use git branch mybranch to create a new branch called mybranch
4.	Use git branch again to see the new branch created.
5.	Use git switch mybranch to switch to your new branch.
6.	How does the output from git status change when you switch between the master and the new branch that you have created?
7.	How does the workspace change when you change between the two branches?
8.	Make sure you are on your mybranch branch before you continue.
9.	Create a file called file1.txt with your name.
10.	Add the file and commit with this change.
11.	Use git log --oneline --graph to see your branch pointing to the new commit.
12.	Switch back to the branch called master.
13.	Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.
14.	Make a new file called file2.txt and commit that file.


### Solution:-
Here’s a step-to-step solution to deal with the above problem

1. This command will list all the branches available in your repository 
   $ git branch 
   ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/4642bf00-079b-43cf-8eeb-a106e0f32ab4)
         

2. To check on which branch you are currently, use the command 
   $ git branch –show-current
   ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/d67d5044-f69d-498e-ba5c-cd07eda5ea5e)


3. Now, to make a new branch named mybranch, use the command 
   $ git branch mybranch
   ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/20d83df5-d6b7-438c-a279-d4fa897464fe)


4. Now, to see the branch again and to observe that the branch you just created is there or not, run the command 
     $ git branch
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/98be758f-7566-4b19-8568-efc6852eda14)
      

5. Use the command for switching between the branches and to switch to your new branch, by using the command 
    $ git switch mybranch
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/6862e17e-ceb5-4352-8fc8-957eb83fb107)

Also, you can use a different command for switching between the branches, that is 
$ git checkout mybranch
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/a3152677-eb40-48a4-8b7e-2df3d8390feb)
       

6. To see the status of both the branches, use the following command in both the branches: $ git status
 
 ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/4f584570-1dda-4cfd-82c2-e7dd42b4c571)

![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/6ff4c0ec-83de-4dcc-8587-db0546e2e72c)

7. The workspace changes when you switch between the two branches because the files and their contents may differ between branches, for which we have already used the command git status.
8. Before you continuing further, make sure that you are on mybranch. You can use the command 
      $ git branch –show-current
to verify the current

![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/c552880d-c23c-489a-9f67-dd869e3ace4d)


9. Create a file called “file1.txt” with your name by using any editor.

   $ touch file1.txt -> for making an empty file  
   ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/4f01beeb-3e4a-4dca-8349-4874a67d07bb)


    $ cat > file1.txt 
   Sakshi                   -> for entering content into the file
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/22c09338-7e04-49b2-b91b-380067f8ae01)
   $ cat file1.txt        -> for seeing the content of the file
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/7c4b81c9-4c93-4dc9-8243-fb2e2f6a3e42)
               

11. Now, add the file by using the command: -

    $ git add file1.txt
  ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/0fb09c5f-e069-49f5-8b72-c580da589707)

  
 And, commit the changes by using the command :-
$ git commit -m “Add file1.txt”
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/22008dc7-4e65-4f3e-97aa-14db2e135b1e)
                      

11. Use the following command, to see your branch pointing to the new commit
    $ git log –oneline –graph
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/49cedd4b-9569-41a8-81ad-33af5324bd0a)

 

12. By using the following command, switch back to the main branch
    $ git switch main    
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/808fc9f9-c532-4ebc-b664-dca2cb550446)

                      

13. Now, use the command $ git log –oneline –graph and notice how the commit you made on the “mybranch” branch is missing on the “main” branch
 ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/4cbfa73f-3453-40de-b207-8fcc16589390)


14. Lastly, make a new file called “file2.txt” by using any editor, after that add it, and then commit it by just the way you did with file1.txt
     $ touch file2.txt  -> for making an empty file 
     $ cat > file2.txt   -> for adding some content into the file
     $ cat file2.txt    -> for seeing the contents of the file
     $ git add file2.txt  -> for adding the file2.txt 
     $ git commit -m “Add file2.txt” -> for committing the file2.txt
 
    ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/4d78fb99-f105-4e4a-8f8d-bb22e60ea20f)

Also, the reference to the solution is attached here within :
 ![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/6dc1faff-5d04-4133-9fae-975f588e5604)
![image](https://github.com/Sakshi-code13/22CSH-293-Group2-ST/assets/119587392/58ff3f42-c265-4387-a930-dd539a3eca37)

 
