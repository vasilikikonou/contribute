# Code Explanation

This is a Python script that produces a webpage displaying 30 squares using Flask Python Framework. Each square is filled with a unique color. The script uses a predefined list of 30 specific hex color codes. The colors are stored in a list variable named colors. Each square has also a unique name of a fruit/vegetable. The text displayed in each square is defined in a separate config.json file and is loaded by the Flask application. <br>

# Prerequisites  <br>  
Python <br>
Flask <br>

# Prepare your environment to run and debugg the code<br>

Using your terminal <br>

Install python<br>
Verify python installation<br>

Install flask<br>
Verify flask installation<br>


# Configure your git global set up<br>

Check your git global set up ---> git config --list<br>
If not already match your username and email with the one you have created for github <br>
`git config --global user.name "your username"`<br>
`git config --global user.email " your email address"`<br>

# Prepare you github account<br>

Go to github.com and login to your account<br>
Go to https://github.com/settings/keys<br>
Go back to your terminal and create an ssh key for your github account<br>
`ssh-keygen -t ed25519 -C "your_email@example.com"`<br>
`cat ~/.ssh/id_ed25519.pub`<br>
Copy the key
In the github keys section: Click create new ssh key, give it a name and paste the key you copied earlier from the terminal. Click save<br>
Check your machine connection with your github account ---> `ssh -T git@github.com`<br>

# Fork the repository you would like to contribute
Go to https://github.com/xpaulos/contribute and click fork <br>  
Go back to your account and you should see a copy of the original repository into your account. <br>
Go to your terminal and create a directory named devopscourse under your home directory and enter it <br>
Clone the forked repository from your account in the directory devopscourse using the ssh command allocated in the green "code" button in your accounts repository <br>

# You are now ready to start contributing to the project.<br>

Open your VS Code editor <br>
Observe the files of the project and try to run the code to see how it works <br>
Ignore the Dockerfile<br>
