**This is just a simple example for connecting to facebook with OAUTH2.
With this you can do all the reading and writing stuff to facebook.
See the Koala Docs for more.**

### GETTING STARTED

1. Clone the repository
2. Run bundle inside the folder
3. Change APP_ID, APP_SECRET (get this from facebook by registering an app)
4. Add an URL like local.myapp.com pointing to 127.0.0.1 in your `/etc/hosts` file
5. Add local.myapp.com to your App Domains list on facebook
6. Set a long and random string as cookie secret (Line: 12)
7. Start your Server with

``` bash
$ shotgun
```

8. point your browser to `http://local.myapp.com:9393/` and click login

### PROPS

Made with the help of this two awesome gems:
* Sinatra -> http://www.sinatrarb.com/
* Koala   -> http://github.com/arsduo/koala

### LICENSE

THE BEER-WARE LICENSE

ben [at] nerdlabor [dot] de wrote this file. As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return Benjamin Knofe


