# README #

This README would normally document whatever steps are necessary to get your application up and running.


### What is this repository for? ###

* Repo for devops project environment automatization 
* 1.0
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

You must to have a remote server image to do connection with ssh service and downloades sshkeyfile. 
In this case is devEnv.pem defined into hosts file

Remote repo firt needs to be updated, upgrated and installed python.

* 1.-Install ansible
* 2.-Download code from repo
* 3.-Define host ip, user, and ssh credentials server(keyfile), all this into hosts file defined on root repo path
* 4.- downloaded files into /opt directory... yuo must to download versions and tools defined 
*   into playbook.yml to copy from /opt/<tool> to remote server. *
* 5.-run playbook.yml
* $"ansible-playbook playbook.yml"
 
 
### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo admin
* Other community or team contact
