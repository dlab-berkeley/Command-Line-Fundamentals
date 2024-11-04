# D-Lab Command Line Workshop


## 3. Navigating File system

🥊**3-1**: Let's navigate to the downloaded workshop folder. <br>
This path depends on your computer and names of your directories. 
```
cd ~/Downloads/Command-Line-Main
```

## 4. Create, move,and delete files and directories
### Creating Directories and Files
🥊**4-1**: Make a folder with a different name. Make a text file within the folder.<br>
```
mkdir test
cd test
touch test.txt
```

🥊**4-2**: Copy the text file to another folder. <br>
```
cp test.txt ../solutions
```

🥊**4-3**:  Rename a file using mv<br>
```
cd ..
mv test.txt test2.txt
ls
```
🥊**4-4**:  Move the file to a different directory.<br>
```
mv test2.txt ../images
ls
```

🥊**4-5**:  Navigate to `test`, and remove `test.txt`.<br>
```
cd test
rm test.txt
ls
```

🥊**4-6**:  Navigate to `imgages`, and remove `test.img`.<br>
```
cd images
rm test.png
ls
```


## 5. Viewing and Editing Files


🥊**5-1**:  Open `Workshops.txt` and add this workshop to the list of workshops.<br>
```
nano Workshops.txt
```
Type `Command Line Workshop` <br>
`Ctrl + O`<br>
`Ctrl + X`<br>


## 6. Dealing with outputs: Pipes and redirection
🥊**6-1**:  save a list of files as “text.txt” or any filename of your choice
```
ls > “test.txt”
```
🥊**6-2**: Let's obtain list of files from a directory, search for filenames that include "pdf", and save that list as `files.txt`. Try to do this in one line of code. <br>
```
ls | grep “pdf”  > “test_pdf.txt”
```


