# Reconfigurable IoT Lockboxes Website

The recent addition of internet controlled locking (doors, Amazon boxes, etc.) is creating unique opportunities and security risks for customers. This project will focus on creating a simple IoT lock box with an emphasis on security and privacy for users. This security and privacy should extend both the person opening the lockbox and the company filling the lock box. Lock boxes need to be extremely low power or even "no power" with a possible serverless design to allow for a box to be opened only by an authorized user 10's or 100's of years in the future. Lock boxes need to be reconfigurable in that multiple boxes can be quickly connected and disconnect from banks of other boxes if so desired.

Tekbots store: https://eecs.oregonstate.edu/tekbots/store \
Project link: http://eecs.oregonstate.edu/capstone/submission/pages/viewSingleProject.php?id=76PUZ5BqzxpBf3Tw \
Google site: https://sites.google.com/oregonstate.edu/ece44x201916 \
Project Showcase: https://eecs.oregonstate.edu/project-showcase/projects/?id=cnGNc9shaO8Aziud


# Group Member
CS: Mingming Su, Julie Kuang\
ECE: Cody Nhem, Jacob Gibson

# Set up

This code directory is fully installed on a student webspace: http://web.engr.oregonstate.edu/~sum/IoT_lockbox/main_page/ 

1. Download and open putty and connect to the flip server (flip.engr.oreognstate.edu) OR if on Linus&Mac Machine, open the "Terminal" and connect to the flip server (flip.engr.oreognstate.edu).
2. Enter ONID id: sum and password: woyaochitudou0411 and pass duo authentication. (Please email to :sum@oregonstate.edu if need to pass duo authentication, thank you)
3. Enter command `cd public_html`
4. Enter command `cd IoT_lockbox`
5. Now you are able to edit any files on the server.
6. To see any changes after you edit a file, go to http://web.engr.oregonstate.edu/~sum 
7. Go to folder “IoT_lockbox”
8. Click on “main_page” then you will see the main webpage
****
Optional: If you want to run the code on your own webspace, you have to do the following:
1. Send an email to the Information Services office (iamteam@oregonstate.edu)  to get CAS authorization for your website.(link: http://onid.oregonstate.edu/docs/technical/cas.shtml)
2. Ask one of the faculty members (client, instructor, etc.) to send a verification email to the IS office.
3. Once you get a response from them, clone the github repository to your own public_html folder.\
  a. Download and open putty and connect to the flip server (flip.engr.oreognstate.edu) OR if on Linus&Mac Machine, open the "Terminal" and connect to the flip server (flip.engr.oreognstate.edu).\
  b. Enter your ONID id and password and pass duo authentication. \
  c. Enter command `cd public_html` \
  d. Enter command `git clone https://github.com/Lockbox-group/lockboxWebsite.git` \
  e. Go to your web browser and go to http://web.engr.oregonstate.edu/~[your_engineering_username] \
  f. Go to folder “lockboxWebsite” \
  g. Go to folder “IoT_lockbox” \
  h. Click on file “main_page” and you will redirect to the main webpage 
****

# How does the website works
1. Website work process: https://drive.google.com/open?id=1cxUDHE3loHT4tZ4Sa_1rVfzUBxQ51DrZ \
  a. When testing admin login, use ONID: sum Password: woyaochitudou0411 \
  b. When testing the "pickup package part", you need to make sure that the admin has successffully logout in the "admin page".

2. Check if admin login or not: https://drive.google.com/open?id=1e5zBKJMMxYsENPCeOn-Tijri9meee7d4
3. EECE lockbox video: https://drive.google.com/a/oregonstate.edu/file/d/1Dg5efGddvlHtViF0bF_CeFcUCx_QkUcX/view?usp=sharing

# Function Introduce (NOW)
1. For admin, using CAS way to login in.
2. Send the package in the send package page and send the email to the student email.
3. For student, enter the information in the main page to open the box.

# Next Step
1. After students pickup the package, they will recieve the email, like " Your package had picked up". This will improve the security for the lockbox.
2. History: Admin can check the send package history.
3. Add the session PHP and cookie to improve the passcode security.
