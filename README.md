# Setup local development environment

```
$ source $(brew --prefix nvm)/nvm.sh
$ nvm install v6.10.0
$ nvm use --delete-prefix v6.10.0
$ npm install http-server
$ ./node_modules/.bin/http-server
``` 

# Region Code Standards

* ISO 3166
* ISO 3166-1
* ISO 3166-1 alpha-2 
* ISO 3166-1 alpha-3
* ISO 3166-1 numeric 
* ISO 3166-2
* ISO 3166-2:TW
* ISO 3166-2:CN
* ISO 3166-2:US

# Note

* google geochart does not support region: TW, resolution: provinces
