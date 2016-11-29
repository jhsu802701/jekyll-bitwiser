THINGS TO DO
1. sh credentials.sh
2. git add .
3. git commit -m "Initial commit"
4. sh server.sh
5. Create this project at GitHub, BitBucket, GitLab, etc.
6. git push origin master
7. Set up the host site.

THINGS TO UPDATE
* Title: _config.yml (name)
* Navbar color: _sass/_variables.scss ($nav-back-color)
* Background color: css/style.scss (html/body background-color)
* Remove sidebar: _layouts/home.html
* Index page content: add index.md
* Background color of posts: css/style.scss (.post/.posts/.unit.single-post-excerpt background-color)
* Add site slogan to header
  * Add the following to css/style.scss after .site-title:
       .site-slogan{
	    margin: 0;
	    text-align: center;
       }
  * Add the following to _includes/header.html after header:
      <p class="site-slogan">Insert slogan here.</p>

BITBALLOON HOST SETUP
1. If you have not already done so, create an account at BitBalloon (https://www.bitballoon.com/).
2. Log into BitBalloon and create this application.
3. RECOMMENDED: Save this project's client key and client secret in KeePassX or other password manager.
4. Enter "sh deploy-bitballoon.sh" to deploy your project.  
   You will be asked for this project's client key and client secret in the first deployment.
   You will also be asked for this information when you deploy from a new development environment.

NETLIFY HOST SETUP
1. If you have not already done so, create an account at Netlify (https://www.netlify.com/).
2. Follow the instructions for setting up Netlify at https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/ .
3. Once Netlify is set up properly, pushing your souce code to GitHub, BitBucket, GitLab, etc. automatically triggers deployment.

SURGE HOST SETUP
1. sh deploy-surge.sh
2. You probably do not want to stick with the initial name.
   Pick a permanent name for this site, and deploy to this new URL with
   the "surge _site/ <new name>" command.
   If this new name is not available, please try a different one.
3. Customize the section of the deploy-surge.sh script that sets
   the permanent name.
4. Remove the section of the deploy-surge.sh script that sets a
   temporary name.
5. Use the "surge list" command to list all of your Surge URLs.
6. Use the "surge teardown" command to remove your unwanted Surge URLs.
