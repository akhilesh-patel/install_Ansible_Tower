# How to install Ansible Tower & how to connect Ansible Tower  

#  Supported Operating Systems:
Red Hat Enterprise Linux 8.2 or later 64-bit (x86)

Red Hat Enterprise Linux 7.7 or later 64-bit (x86)

CentOS 7.7 or later 64-bit (x86)


# Requirements
#2 CPUs minimum for Automation Platform installations

#4 GB RAM minimum for Automation Platform installations

************************************************************
############################################################

# Step 1: Update system and add EPEL repository ,For CentOS / RHEL 8
sudo yum -y update

sudo yum -y install epel-release

# step 2
sudo yum -y install ansible vim curl

# Step 2: Download Ansible Tower archive
mkdir /tmp/tower && cd  /tmp/tower

curl -k -O https://releases.ansible.com/ansible-tower/setup/ansible-tower-setup-latest.tar.gz

# Extract downloaded archive.
tar xvf ansible-tower-setup-latest.tar.gz

# Step 3: Install Ansible Tower
cd ansible-tower-setup*/

ls

backup.yml

collections 

install.yml 

licenses  

rekey.yml  

roles

# Edit inventory file to set required credentials


vim inventory


![Screenshot (820)](https://user-images.githubusercontent.com/64592542/146015281-61c8eb53-65b7-4cc4-87ec-1c15de28c8a2.png)
![Screenshot (821)](https://user-images.githubusercontent.com/64592542/146015291-b6b413c8-cd5a-4e0b-bcf5-59d2406d98d1.png)
![Screenshot (822)](https://user-images.githubusercontent.com/64592542/146015299-c59dc218-e170-4fc8-996e-ca9ff7503a99.png)
![Screenshot (823)](https://user-images.githubusercontent.com/64592542/146015302-99377eb2-45a0-4d96-ae61-f12733645391.png)


...................................

sudo ./setup.sh 
***************************************
Step 4: Configure Ansible Tower

# Go to your browser and type your ip address






![Screenshot (826)](https://user-images.githubusercontent.com/64592542/146016212-48e28ddf-6433-4b4a-a896-bb4bf3581102.png)






# Hi, I'm Akhilesh! 👋



## 🚀 About Me
I'm a devops engineer as a intern in mernplus technologoy...


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Other Common Github Profile Sections
👩‍💻 I'm currently working on...

🧠 I'm currently learning...

👯‍♀️ I'm looking to collaborate on...

🤔 I'm looking for help with...

💬 Ask me about...

📫 How to reach me...

😄 Pronouns...

⚡️ Fun fact...


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/akhilesh-patel)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akhilesh-patel-8983aa1a5/)
[![dockerhub](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)

