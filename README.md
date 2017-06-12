# FreeBSD Node.js builds for nvm
> For development purposes only, do not use in production environment!


### Basic system informations

```sh
$ uname -a
FreeBSD Node.js-dev 11.0-RELEASE-p9 FreeBSD 11.0-RELEASE-p9 #0: Tue Apr 11 08:48:40 UTC 2017     
```

```sh
$ nvm --version
0.33.2
```


### Download and install Node.js into npm

```sh
wget -qO- https://github.com/honzahommer/freebsd-nodejs-build/archive/v8.1.0.zip | tar -xvzf -C pretty_name -
mv freebsd-nodejs-build-8.1.0 $NVM_DIR/versions/node/v8.1.0
nvm user v8.1.0
```


### How install npm on FreeBSD

See my public Gist https://gist.github.com/honzahommer/dbb1a44a80a9b6becacb4da437ad59c8#file-nvm-md for more informations.
