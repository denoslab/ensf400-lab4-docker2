# ensf400-lab4-docker2

### Task 1

1. Create GitHub Codespace of https://github.com/denoslab/dockerstepbystep
1. Start the container on Codespace using `docker-compose_deploy.yml`
1. Attach to the shell and type a command to demonstrate you are in the container, such as `pwd`
1. Enable port forwarding and open the application in a browser

### Task 2

1. Clone https://github.com/denoslab/toolbox and familiarize yourself with the project by reading the documentation.
1. Switch to branch `ensf400_w25`
1. Create a branch off the `ensf400_w25` branch
1. On your own branch, modify the project to create your personal desired development environment
1. Select one modification you have implemented on your sub branch which you think could be useful to others and merge it to the `ensf400_w25` branch (make sure that this change is documented!)
1. Send a pull request to the original project, on the `ensf400_w25` branch

### Task 3

1. Use Portainer to start your sub branch of the project in a container
  - Tip: You will need to create a new docker-compose file which is appropriate for your local environment (consider where the volume is mounted on the local system and which image is being used) - there is a Portainer compose example to help you
  - Tip: You will need set the repository URL and repository reference in Stacks
  - Tip: Ensure “Re-pull image and redeploy” is disabled in the pop-up window when you hit “Pull and redeploy”

### Demonstrate for the TA

- The dockerstepbystep application is running in the browser from Codespace
  - TA: check that URL ends in app.github.dev

- You made a pull request to the original project
  - TA: check that there is an open pull request at https://github.com/denoslab/toolbox/pulls by a student in the group

- You made your own branch on your fork
  - TA: in cloned repository on student’s local machine, check structure with git show-branch

- You are running your toolbox application using Portainer
  - TA: view Portainer in browser, look at Stacks and ensure repository reference is to their branch (under GitOps > advanced configuration), scroll down and ensure container is running