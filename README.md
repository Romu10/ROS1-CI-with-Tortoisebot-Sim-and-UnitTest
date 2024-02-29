
---
This repository sends repo push events to the Jenkins instance via a webhook URL.

# Automated Tortoisebot Waypoints Test

In this **Checkpoint 24 Rosject** we need to have Jenkins running. 

For start Jenkins, run the next command:

  - *cd /home/user/webpage_ws*
  - *bash start_jenkins.sh*
  - wget -nc https://raw.githubusercontent.com/TheConstructAi/jenkins_demo/master/setup_ssh_git.sh && bash setup_ssh_git.sh

In order to get the url run the command shown below to display the link URL for the Jenkins server that you started:

  - *cat /home/user/jenkins__pid__url.txt*

Before making the pull request use the next command and save the URL generated:

  - *echo "$(jenkins_address)github-webhook/"*

**In the pool request form please provide the generated URL.**

## Git repositories ##

Make the pull request in the next repositor: 

  - *https://github.com/Romu10/ROS1-CI-with-Tortoisebot-Sim-and-UnitTest.git*

Others repository:

  - https://github.com/rigbetellabs/tortoisebot.git
  - https://github.com/Romu10/ROS1-UnitTest.git
