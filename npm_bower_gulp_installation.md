##1. Install npm
```
curl https://raw.github.com/creationix/nvm/master/install.sh | sh
```

##2. Running Gulp

```
workon syapse_apps
npm install //automatically updating the package.json
gulp
//you will see a list of gulp command in the Gulpfile.js
```
##3. Install bower

```
npm install -g bower
workon syapse_apps
bower install PACKAGENAME --save // save the new lib and update the bower.json
bower install PACKAGENAME —save-dev (auto updating bower.json in the devDependencies category)
bower uninstall jquery --save
```
