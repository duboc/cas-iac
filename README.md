# Welcome to the SE Latam Hack Night! 


**Please Note, this site is currently in beta/preview mode and under active development. Please excuse any errors or ommissions**

The SE Latam Hack Night on Github provides a challenge with free learning resources for IaC technologies with a learn-by-doing approach focused on practical, hands on skills.

All the content on this site revolves around challenging exercises, with different levels, which align tightly with the common customer operations.

# Requirements 
- Amazon account (You have an extra step if you use your own account, but also bonus points!)
- GitHub account
- Git client installed on your laptop
- Access to VMware Cloud Assembly (CAS LATAM org, it's going to be provided one day before the event)
- Access to Wavefront (Sandbox – Workspace One)
- Ninja Google search skills

# Intro & Overview

## Level 100 - High Level Activities
### It’s just a guide line, do it on your way….. Google is your friend.

- Configure AWS environment as cloud destination
  - Use your group name as a prefix for everything 
- Fork git repository for basic blueprint (cas-iac)
  - https://github.com/duboc/cas-iac
- Some basic Git commands are:
``` 
git clone
git add
git commit
```
Great tutorial if you need one: http://www.justait.net/2016/10/github-basics-1.html
- Create an integration between your GitHub project and Cloud Assembly
- Use your team’s name as your hostname
- Provision Deployment 


## Level 200 - High Level Activities
### It’s just a guide line, do it on your way….. Google is your friend and you can always check the CMBU Blogs :wink: 

Change code to add:
- Input for different flavors, like:
  - Small, Medium and Large
- Apache installation
  - Wavefront apache integration (use wavefront-sandbox)
- Add tag:
  - key = team 
  - value = “Your team’s name”
- Commit change to git (command line is a bonus)
- Make a new deployment


## Level 300 - High Level Activities
### It’s just a guide line, do it on your way….. Google is your friend.

##### Create a CodeStream Pipeline such as:
1. Create deployment using latest blueprint
2. Approval policy 
   - aduboc@vmware.com
   - emeirelles@vmware.com
   - tbaeta@vmware.com
   - astratikopoulo@vmware.com
3. Delete deployment

