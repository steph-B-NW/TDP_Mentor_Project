# Mentored Project
 
## Tasks
 
Here a Python application that is made up of 4 different services.
 
- Service 1 - Central App
- Service 2 - Provides random numbers
- Service 3 - Provides random letters
- Service 4 - Create an account number (Based on info from service 2&3) and gives a prize based on that account number.
 
You are tasked with deploying this application using all the skills you have developed throughout your time in the academy.
 
Your deployment should make use of,
 
- Docker/Docker-compose
- Ansible
- Jenkins
- Nexus
- SAST Testing
 
You should keep as many metrics as possible and write up reports on them in your README file. These metrics can include.
 
- Testing Coverage
- Deployment Success
- Build Logs
- Security Risks
 
## Stretch Goals
 
1. Use NGINX as a reverse proxy
2. Version Docker images
3. Include DAST Testing and Artefact Scanning
 
### Submission
 
You should create a Git repository that contains the code for the 4 services and any files you created to deploy your application including Dockerfiles, playbooks, reports etc.
You are also expected to make a README.md file and to fill this README with information of this challenge. It should contain the following headers.
 
# Why are we doing this?

This piece covers the knowledge we'd been working on from pretty much start to finish in our initial bootcamp, so it's a good way to review, summarise and contextualise the work we've been doing. This is a good way to encourage revision. 

# How I expected the challenge to go.

This is quite the laundry list, and I found a few of these areas quite challenging. I was ready get caught on some of the most basic concepts as I went back over their main points, as well as understanding how I would have to adapt the techniques to work within the custom bounds at play. We have been working mostly without context for the containers and files we've been using, so creating this structure and going through the processes correctly Was something I knew would be a challenge in itself.

# What went well?

the construction of the docker-compose files and the playbook.yaml were definitely the parts I felt most comfortable with, and confident enough to create the appropriate script. I also began to understand the process as a bigger series of events and dependencies that need to be generated and associated. This was actually very helpful to keep me moving forward.

# What didn't go as planned?

Unfortunately, it was what I intially expected to be trouble. Jenkinsfiles are very challenging for me, the syntax is confusing, and I simply was unable to move past an error in the very early stages of the file regarding "no steps specified" and unfortunately telling the machine "there's a step right there!" Was not quite the bugfix I needed. I attempted many iterative changes, but unfortunately I was not able to find a solution that I could use effectively.

# Possible improvements for future challenges.

I need to feel more comfortable seeking assistance. I am definitely still stuck in a mindset that prevents me from going to my colleagues for their opinion as I don't want to bother them. Normally I would feel comfortable to do this, but remote working has made this feel difficult, as often this turns into a full call for what would normally be a quick check, and that could be disruptive to someone else's day. This Jenkinsfile error would likely have been remedied through a second opinion, so I definitely made an error attempting to solve it all by myself. I'll work on improving this in the future.
