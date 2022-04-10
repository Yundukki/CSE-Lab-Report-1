# Lab Report #1: Remote Access

1. ### Installing Visual Studio Code
    
    a. To begin, we will first head to the [Visual Studio Code](https://code.visualstudio.com/) Website. Select MacOS, Windows x64, or Linux x64 for your respective operating system.

    ![](labreport1pic1.png)

2. ### Remotely Connecting

    a. (Windows Only) Start by installing [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse).

    b. Next, we will look up our [Course-specific Account](https://sdacs.ucsd.edu/~icc/index.php). Here you will enter your credentials and find your course-specific account under Additional Accounts.

    ![](additionalaccounts.png) 

    c. To set up remote connection, head to VS Code and open a new terminal (Terminal -> New Terminal). 
        
    Enter the Command (zz will be replaced by your course-specific account)
        
    `$ssh cs15lsp22zz@ieng6.ucsd.edu`

    If it is your first time logging, you may be prompted to a question in which you answer yes and enter your password. 

    After doing so, your terminal should look like this:

    ![](remoteaccess.png)

    You are now successfully connected! Your computer is now called the _client_ and the remote computer is called the _server_.

3. ### Testing Commands while Remotely Connected

    
    A few commands you could try are:

    * `ls -lat`

        This command combines three options in one. -l shows all of the hidden files. -a shows additional information. -t shows all of the files and information sorted by time and date of when they were created/modified. 


    * `ls -a`
        
        This command searches the current directory and shows additional information of all the files.

    Each of these commands should be tested in both the Client (your computer) and Server (remotely connected computer). 

    Example Command:

    ![](examplecommand.png)

    As we can see here, the command attemps to access another students files from their directory. The server does not allow this so the request is denied. 

    Using the command `exit` or CTRL-D will log you out of the server. 


4. ### Moving Files Using scp








        

    
