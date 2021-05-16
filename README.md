#nodejs-github-webhook

## How to use

##### 1. Specify port and secret key from _index.js_

```javascript
var secret  = 'amazingkey';
var port    = 8081;
```

##### 2. Specify the git repository from _hook.sh_

```shell
#DIRECTORY TO THE REPOSITORY
REPOSITORY="./myrepository"
```

##### 3. Run the server

```
$ npm start
```

##### 4. Configure Webhook at Github repository Settings  
  
Payload URL is http://ADDRESS:PORT/push  
Enter the secret key that you have entered in index.js
