THINGS TO DO
1. sh credentials.sh
2. git add .
3. git commit -m "Initial commit"
4. sh server.sh
5. Create this project at GitHub, BitBucket, GitLab, etc.
6. git push origin master
7. Set up the host site.

BITBALLOON SETUP
1. If you have not already done so, create an account at BitBalloon (https://www.bitballoon.com/).
2. Log into BitBalloon and create this application.
3. OPTIONAL: Save this project's client key and client secret in KeePassX or other password manager.
4. Enter "sh deploy-bitballoon.sh" to deploy your project.  
   You will be asked for this project's client key and client secret in the first deployment.
   You will also be asked for this information when you deploy from a new development environment.
5. git mv deploy-bitballoon.sh deploy.sh
6. git add .
7. git commit -m "deploy.sh"
8. git push origin master

