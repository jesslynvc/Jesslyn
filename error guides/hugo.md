## dart-sass-embedded not found
Got a strange error when trying to run HUGO on developers-site

Error: Error building site: TOCSS-DART: failed to transform "sass/jp/style.scss" (text/x-scss). You need dart-sass-embedded in your system $PATH.: this feature is not available in your current Hugo version, see https://goo.gl/YMrWcn for more information

Cause: dart-sass-embedded could not be found

Failed Solutions:
- Tried brew install dart-sass-embedded but PUB GET couldn't find the file

Solutions: 
We download it from github and set the path.  
STEPS:
- download the latest file from https://github.com/sass/dart-sass-embedded/releases , unzip it and put it to wherever you want (I put it in )
- go to your home directory from terminal
```
cd /Users/jesslyn002642 
```
- open .zshrc in vscode
```
code .zshrc 
```
and add the downloaded dart-sass-embedded to path
```
export PATH="$PATH:/Users/jesslyn002642/Documents/dart-sass-embedded"
```
save and close
- Quit terminal and restart it. Check if your new path is successfully added. You can also check the version.
```
echo  $PATH
dart-sass-embedded --version
```
- Done. Go back to dev site and try
```
hugo server
```
