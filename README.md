Yarn installation on Ubuntu 22.04

Step 1: Update system packages
$ sudo apt update

Step 2: Install curl
$ sudo apt install curl

Step 3: Import GPG key
$ curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

Step 4: Add Yarn repository
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

Step 5: Install Yarn
$ sudo apt install yarn -y

Step 6: Confirm Yarn version
$ yarn --version


Tips : 

If > $quasar serve > show:  404 | Page Not Found

try:

http://localhost:4000/dist/spa/index.html

