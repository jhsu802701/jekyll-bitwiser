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
2. Create this application at BitBalloon.
3. OPTIONAL: Save this project's client key and client secret in KeePassX or other password manager.
4. Enter "sh deploy-bitballoon.sh" to deploy your project.  
   You will be asked for this project's client key and client secret in the first deployment.
   You will also be asked for this information when you deploy from a new development environment.
5. git mv deploy-bitballoon.sh deploy.sh
6. git add .
7. git commit -m "deploy.sh"
8. git push origin master

DISTELLI SETUP
1. If you have not already done so, create an account at Distelli (https://www.distelli.com/).
2. Follow the instructions at https://www.distelli.com/docs/tutorials/build-and-deploy-jekyll-website .
   When you need to enter your Distelli credentials, just enter "sh credentials.sh".
3. git rm deploy-bitballoon.sh
4. git add .
5. git commit -m "Removed deploy script"
6. git push origin master
