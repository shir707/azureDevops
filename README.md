##General info <br />
*This is a CI/CD pipeline using yaml.<br />
*In the CI pipeline, I installed all the dependencies and publish the app artifact in a zip file and store it in Azure Devops.<br />
*In the CD pipeline, I download the artifact into "a" folder in agent servers and deploy the artifact application into stage and prod enviorments.<br />

##Technologics <br />
Project is created with: <br />
*terraform code. git for the code: https://github.com/shir707/TF-Code <br />
*ansible code. git for the code: https://github.com/shir707/ansibleProject <br />

##In order to connect to the website application <br />
for prod enviorment: http://20.85.132.121:8080/list  <br />
for stage enviorment: http://20.106.47.103:8080/list