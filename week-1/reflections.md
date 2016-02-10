# 1.1 Think About Time Reflection

Which time management and productivity ideas did you learn about?
I learned about the importance of meditation, having a growth mindset, and how to improve my personal productivity. One of my main focuses in life is ensuring I have a growth mindset when presented with both new and recurring situations, and it seems by having a growth mindset you can massively improve your productivity. The most important notion I took away from the resources is that one must fail to grow. I came across this video of Google's artificial intelligence program playing a video game Block Breaker -- and it's an excellent analogy for having a growth mindset.

Here is the link:
https://www.youtube.com/watch?v=V1eYniJ0Rnk (Links to an external site.)


The reason this video is so important with regards to a growth mindset is that it shows that the best way to learn something is by failing at it multiple times and in unique ways. One lesson to be learned from it is that failing for the same reason repeatedly does not enhance your algorithm (or intelligence). But failing uniquely is pivotal to growing rapidly and efficiently.

I also read the Pomodoro Technique extensively (including before Dev Bootcamp). I use it on big projects that need to be completed in a short time-span -- and it is incredibly useful. My attention span increases two fold even after a 5 minute break and it allows me to truly digest the lessons learned from the previous 25 minutes.

What is "Time Boxing?" How can you use it in Phase 0?
While similar to the Pomodoro Technique I just mentioned, it is the parent for the Pomodoro Technique in code-speak. Time boxing is allotting a certain amount of time for you to fully focus on a specific task (the readings also hinted that the more specific your task is, the higher your productivity) followed by another certain amount of time to take a break and reflect on what you just learned. In Phase 0, I plan to use the Pomodoro Technique when working on the tasks so that I can both retain new material and become more productive.

How do you manage your time currently?
I use the Pomodoro Technique. It allows me to work more efficiently on a problem and to be concentrated on a project for a longer time without becoming distracted.

Is your current strategy working? If not, why not?
My strategy is working very well! I highly recommend the technique.

Can/will you employ any of them? If so, how?
Yes, I will continue employing the Pomodoro Technique by focusing on a specific problem/task for 25 minutes followed by a 5 minute reflection/tea break.

What is your overall plan for Phase 0 time management?
To complete the tasks as soon as they come with the Pomodoro Technique. As soon as the new tasks are released, I will concentrate on completing them because I am very enthusiastic about learning to code!

# 1.2 The Command Line Reflection

What is a shell? What is "bash?"
A shell is your command line, Terminal, or PowerShell. The 'bash' is a Unix shell (a command processor) that runs in a text window where you can type commands (input) and it will generate output based on your commands. It is particularly useful when running development servers, generating rails projects, installing certain dependencies, and managing directories, files, etc.

What was the most challenging for you in going through this material?
Trying to memorize the terminal commands. However, I believe that the more I keep using the commands the more they will become second-nature. So I plan on doing that!

Were you able to successfully use all of the commands?
Almost but not entirely. I am on a Windows 8 so commands like sudo give me back an error. Regardless, I have memorized those commands as well to ensure that I feel comfortable using terminal commands no matter the operating system I am using.

In your opinion, what are the most important commands and arguments to know?
'cd' is by far the most used command as I find myself switching directories all the time. The command 'ls' to view your directory's contents and the commands 'rm' | 'rmdir' to remove certain directories or files also comes in handy very frequently. However, the most important command to remember is likely the 'help' command, as it will give a list of the commands in case you forget them!

Can you remember what each of the following does of the top of your head? Write what each does.
-pwd = 'print working directory', which shows you your current path

-ls = 'list directory', which lists the contents of your current path

-mv = 'moving a file', which moves files or, rather, renames them

-cp = 'copy', which copies a file under your current path

-cd = 'change directory', which changes your directory to a different path depending on what you input after the command (ie. 'cd ..' to move up a directory

-../ = 'up', which moves your path up a directory

-touch = 'new file item', which makes an empty file

-mkdir = 'make directory', which makes an empty directory under your current path

-less = 'view a file', which allows you to look at the contents of a file through paging (MORE on Windows)

-rmdir = 'remove directory', which takes a directory name after the command and removes it under your current path

-rm = 'remove file', which takes a file name after the command and removes it under your current path

-help = 'help', which lists a few key commands that will help you if you forget a command name

-grep = 'grep', which allows you to look inside specific files. With Ruby on Rails, for example, I use this command often when after rake routes like 'rake routes | grep articles' to only display the routes that have the keyword 'articles' in it.

# 1.4 Forking and Cloning Reflection

If you were going to write instructions for a new person on how to create a new repo, fork a repo, and clone a repo, what would they be? Why would you fork a repository as opposed to create a new one?
A fork is just a request for GitHub to clone the project and registers it under your username; GitHub also keeps track of the relationship between the two repositories, so you can visualize the commits and pulls between the two projects (and other forks). When you are cloning a GitHub repo on your local workstation, you cannot contribute back to the upstream repo unless you are explicitly declared as "contributor."

Step 1: Create a C9 account (unless you prefer using your local machine)

Step 2: Create a new workspace (this will create a VM that runs on C9's servers, which makes your life much much easier as far as getting set up!)

Step 3: Create a GitHub account

Step 4: Go to https://github.com/Devbootcamp/p0-cli-exploration (Links to an external site.)

Step 5: Click fork repository, which creates a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

Step 6: Once redirected to the fork you just made, copy the text after 'HTTPS' or 'SSH' (only use SSH if you have SSH keys defined on your GitHub account), which should look something like -- git@github.com:USERNAME/p0-cli-exploration.git

Step 7: Go to your new C9 workspace and ensure you are in your /workspace directory. Then, type 'git clone git@github.com:USERNAME/p0-cli-exploration.git' into the terminal.

Check if your cloned repository from your fork was created successfully by then typing in 'ls' to see the files/directories under your current path. And that's it! 

What struggles did you have setting up git and GitHub? What did you learn in the process?
No struggles! I learned how to fork a repository and clone it. However, I also understood that if I do a git commit on a forked repository, it does not count towards my total commits on my GitHub profile page, which means you could lose your streak if you're not careful!