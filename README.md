To run this web app follow these insructions

Step 1:
      Launch a AWS ec2 instance with Ubuntu AMI :
      connect to your instance
      
Step 2:
      Update the System command :
      sudo apt-get update

Step 3:
      To get this repository, run the following command inside your git enabled terminal :
      git clone https://github.com/MaheshAneraye/chatbuddy.git

step 4:
      open chatbuddy folder and install following things :
      sudo apt install python3-pip -y
      sudo apt install python3-django -y
      sudo apt install python3-djangorestframework -y
      sudo apt install python3-pillow -y

step 5:
      That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command:
      python3 manage.py runserver 0.0.0.0:8000
      And It's Done...
      
