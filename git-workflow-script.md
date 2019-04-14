**Getting Started with Github Organizations**

1. **Create Organization**

![image alt text](images/image_0.png?raw=true)

- create a name

- invite team members

- invite project manager (fellow) and instructors

- skip the survey step

- change settings at organization level to make everyone an admin

2. **Create a new repository under organization**

![image alt text](images/image_1.png?raw=true)

- create a name

- public

- Initialize this repository with a README

3. **Clone project repository to local machine and set up Boilermaker**

- follow directions in Boilermaker setup to get [boilermaker](https://github.com/FullstackAcademy/boilermaker) code in your project repo


4. **Protect master branch**

_(this step should be done after setting up boilermaker)_

![image alt text](images/image_2.png?raw=true)

- purpose: prevent dangerous pull requests being merged into master

- Require pull request reviews before merging

- Include administrators - ensures even admins need to get approval for PRs

- save

![image alt text](images/image_3.png?raw=true)



- saved changes to master branch in screenshot below:

![image alt text](images/image_4.png?raw=true)

5. **Branches**

- other team members clone project repository

- new branches created using following command: git checkout -b "name-of-branch" (-b creates new branch)

- create a demo.js file

- add and commit changes to your branch and leave meaningful commit messages

- push changes to branch using following command: git push origin name-of-branch

6. ** Creating pull requests**

![image alt text](images/image_5.png?raw=true)

- create pull requests once changes in branch are ready to be reviewed

- include details regarding what the pull requests contains

![image alt text](images/image_6.png?raw=true)

- another team member must reviews, approve, and merge the pull request

![image alt text](images/image_7.png?raw=true)

7. **Reviewing, approving, and merging pull requests**

![image alt text](images/image_8.png?raw=true)

- open pull requests are under the Pull-requests tab

- click on pull request and review leaving comments

- approve pull request once comments (if applicable) have been addressed

- merge pull request

- delete branch once pull request has been merged

![image alt text](images/image_9.png?raw=true)

8. **Update your local repository after changes have been merged**

- communicate merges with team members

- do a git pull


9. **Resolving merge conflicts**

- PERSON 1 sees that pull request has a conflict

- PERSON 1 resolves conflict locally 

- PERSON 1 pushes another commit with the resolved code

- PERSON 2 reviews/approves, and merges to master


