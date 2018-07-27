![simplinnovation](https://4.bp.blogspot.com/-f7YxPyqHAzY/WJ6VnkvE0SI/AAAAAAAADTQ/0tDQPTrVrtMAFT-q-1-3ktUQT5Il9FGdQCLcB/s350/simpLINnovation1a.png)

# A Simple Authentication App Using Express & MongoDB

![simplinnovation_exp_auth](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUFxJ1ez-eBv_9E3dctQFS0Sq-5E0b3uT3_ptUXYLoXvNUYJH2)

#### 1. Activate your MongoDB server, then create a database, database user & collection on MongoDB:

```shell
  $ use signin

  $ db.createUser({user: 'lintang', pwd: '1234', roles: ['readWrite', 'dbAdmin']})
    
  $ db.createCollection('users')
```

#### 2. Clone the project from my repo:

```shell
  $ git clone https://github.com/LintangWisesa/Express-MongoDB-Authentication.git
```

#### 3. Go to the repo then install all packages needed:

```shell
  $ cd Express-MongoDB-Authentication

  $ npm install
```

#### 4. Edit Express app route on _routes/router.js_! Make sure there is no error on your app by running _app.js_. Server will be running by default on localhost:3210!

```shell
  $ node app
```

#### 5. Open *localhost:3210* via browser. If everything goes well, the response will be similar to the picture below:

![simplinnovation_auth1](
https://raw.githubusercontent.com/LintangWisesa/Express-Authentication/master/picture/auth1.png)

#### 6. Try to signup, check on your database, then try to login. Have fun :sunglasses: !

![simplinnovation_auth2](
https://raw.githubusercontent.com/LintangWisesa/Express-Authentication/master/picture/auth2.png)

![simplinnovation_auth3](
https://raw.githubusercontent.com/LintangWisesa/Express-Authentication/master/picture/auth3.png)

![simplinnovation_auth4](
https://raw.githubusercontent.com/LintangWisesa/Express-Authentication/master/picture/auth4.png)

![simplinnovation_auth5](
https://raw.githubusercontent.com/LintangWisesa/Express-Authentication/master/picture/auth5.png)

#

#### Lintang Wisesa :love_letter: _lintangwisesa@ymail.com_

[Facebook](https://www.facebook.com/lintangbagus) | 
[Twitter](https://twitter.com/Lintang_Wisesa) |
[Google+](https://plus.google.com/u/0/+LintangWisesa1) |
[Youtube](https://www.youtube.com/user/lintangbagus) | 
:octocat: [GitHub](https://github.com/LintangWisesa) |
[Hackster](https://www.hackster.io/lintangwisesa)
