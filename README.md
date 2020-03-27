# c9setup

[![CircleCI](https://circleci.com/gh/kluto/c9setup.svg?style=svg)](https://circleci.com/gh/kluto/c9setup)

1. create new cloud9 env 
2. generate rsa key 'ssh-keygen -t rsa' and add public key to github account
3. update git config in cloud9 env
	git config --global user.name ""
	git config --global user.email ""
4. clone repo to c9 env cd into it
5. create new venv "python3 -m venv ~/.name" and source it
6. create alias for quick activation
7. touch Makefile + requirements.txt + app.py
8. git commit & push
