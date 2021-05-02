# Lab Guide
Everything you need in order to complete labs for flatiron

### Finding and forking the lab
Go to [my github repositories](https://github.com/Anw0514?tab=repositories) and scroll until you find the lab you're looking for. 
If it's not there, that's my b lol. Click on the lab you need and click "fork" on the top right. Once that's done, the repository 
name should have swithced from anw0514/repo-name to danielcho64/repo-name.

### Cloning to your computer
To clone the repo, click the green 'Code' button toward the top right of the page and make sure you're in the ssh tab. 
Copy the ssh link to your clipboard (remember to use cmd instead of ctrl).
You're gonna wanna open iTerm 2 and cd into the correct folder. It should be ~/Development/flatiron/prework.
To clone the repository easily, you can just type gcl and then paste. 

`gcl git@github.com:danielcho64/lab-name.git`

### install necessary gems
After you've cloned your repository, run `bundle install` to make sure all the gems you need are there.

### 'learn'
Wherever they ask you to type 'learn', they're really just asking you to run the spec file. 
Each lab is gonna have one and you just have to run it manually instead.
To do this, you want to find the initial spec file (for the early labs it's just whichever one isn't spec_helper).
Once you've found that file, run it with ruby by typing `ruby spec/name_of_spec_file.rb`

### 'learn submit'
I made a function called "submit" that does the same thing. So all you have to run is `submit` and it should work fine. 
Just make sure to cd out of the project repository once you're done. You can do this easily by running `cd ..`


**Note**
Remember, when you're moving around in the terminal, it's the same thing as moving around in the file explorer. A directory is the same thing as a folder. 
Here's some reminders as a cheat sheet:

`cd ..` - move one folder up

`mkdir folder_name` create a new empty folder in your current directory named folder_name

`touch file_name.whatever` create a new blankfile named file_name.whatever

`code folder_name` open the folder named folder_name in VS Code

`code .` open the current folder in VS Code

`cd ~` move to your home directory. This is the top folder.

`ls` show all the files and folders within your current directory

