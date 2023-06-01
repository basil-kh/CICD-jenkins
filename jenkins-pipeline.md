# Pipe 1 - Run automated tests on pushed code
![Alt text](imgs-pipeline/1.png)
![Alt text](imgs-pipeline/2.png)
![Alt text](imgs-pipeline/3.png)
![Alt text](imgs-pipeline/4.png)
![Alt text](imgs-pipeline/5.png)
![Alt text](imgs-pipeline/6.png)
![Alt text](imgs-pipeline/7.png)
![Alt text](imgs-pipeline/8.png)

# Setting up webhook on github
![Alt text](imgs-jenkins/10.png)
![Alt text](imgs-jenkins/11.png)
![Alt text](imgs-jenkins/12.png)

# Pipe 2 - Merge dev branch to main

![Alt text](imgs-pipeline/9.png)
![Alt text](imgs-pipeline/10.png)

![Alt text](imgs-pipeline/11.png)

![Alt text](imgs-pipeline/12.png)

# Pipe 3 - Push changes to app and run

## General and office 365 connector Settings same as pipe 2.
Back on main branch as the previous job should have merged dev into main.
![Alt text](imgs-pipeline/13.png)
The pem can be added to jenkins in a similiar way as the github SSH private key
![Alt text](imgs-pipeline/14.png)

If all goes smoothly, you can try to change some words in the app folder and push to dev branch and see if the changes appear on your webpage like so : ![Alt text](imgs-pipeline/15.png)



5



