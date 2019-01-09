## Learn to code app
---

**Summary:**

This is the Core App of the LearnToCodeApp project. This project has been created to provide a focus for learning programming and working collaboratively. Everyone is encouraged to join in, whatever the level of their experience.

The overall aim is to produce office administration software. We intend to produce the software in a modular form, allowing developers to work on and duplicate individual parts of the project. Users should be able to pick and choose functionality by including or omitting modules.

The Core App is a generic module intended to help a business organize itself. In particular, the Core App will:

* Provide a contact database (including contact details)
* Provide a database of projects carried out for clients (which might otherwise be known as "files" or "accounts")

The Core App will be browser based.

----

**Getting started**

Please refer to our Github Wiki as to how to use the programme or get involved.

To speak to existing collaborators, please join the Discord conversation: https://discord.gg/BFNsDH2


**Technologies / Dependencies / Tools**

* Python 3
* Django 2.1.4
* Postgresql
* HMTL5 and CSS3
* Git
* Github
* Sphinx documentation module
* Readthedocs

**Setting up virtual environment for Django and Sphinx**

This project uses pipenv to manage it dependencies. To make sure the project runs smoothly on your local machine, be sure to execute the following commands in the terminal or powershell. These commands should work on all operating systems.

* Install pipenv using pip (If you have a preferred method of installing python modules which differs from the method demonstrated below, feel free to use it.)

```console
$ pip install pipenv
```

* Go to the directory where you have cloned the repository, make sure the directory contains "Pipenv" and "Pipenv.lock" files, and run the command below. This command will install all the dependencies for the project.

```console
$ pipenv install
```
* Once you have completed install, you can start this virtual environment by using the command

```console
$ pipenv shell
```
* To exit

```console
$ exit
```

* If the feature you are working requires you to add a new dependency to the virtual environment, then use the following command to add the new package.
```console
$ pipenv install package-name
```


**Contributing**

For technical details, please refer to our documentation: https://learntocodeapp.readthedocs.io/en/latest/. Before doing so, we recommend you read our Code of Conduct and make sure you agree with the terms of our licence.

If you would like to inform us of a problem, please go to the "issues" tab and use the template to submit a bug report.

If you would like to ask us to add a feature, change how the app works or give additional options, please go to the "issues" tab and use the template to request a feature.

**Collaborators**

* Will Mason (Django Will)
* sangar-happy (maRIne)
* Sagar Chavan(git: sagarc03)(discord: light#5379)
* Albin Warmlind (Niblet)
* sshimanath (shimnut)
* Rushik Subba (rand0mgam3r)

**Licence**

Please read the associated licence file for the terms under which this project may be used and/or distributed.


