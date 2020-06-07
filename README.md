![alt text](https://vectr.com/gary_uwu/b2K0MUG2ZU.png?width=447.7&height=96.36&select=fFVlrD4Eq,b1GpdLDr62,acLmi0UyC,bfQeq0AS9,bboBmp9BJ,j37nqilXSl,b2GisM3yT,e4t6Ninn4Y,a4Ki4MauRc&source=selection)

![alt text](https://img.shields.io/github/license/Lumax-Official/lumax-junitalinux)
![alt text](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FLumax-Official%2Flumax-junitalinux%2F)
![alt text](https://img.shields.io/github/forks/Lumax-Official/lumax-junitalinux)
![alt text](https://img.shields.io/github/issues/Lumax-Official/lumax-junitalinux)



### Installation

You can install Junita by using sudo

```sh
$ sudo apt install junita-desktop
$ sudo upgrade
$ junita-desktop --install /DRIVE LETTER
```

Or by using npm

```sh
$ npm install junita-desktop
$ junita-desktop --install /DRIVE LETTER
```

### Archives

Generating pre-built zip archives for distribution:
```sh
$ sudo apt install junita-desktop-arch
$ sudo upgrade
$ junita-desktop-arch --install /DRIVE LETTER
```
Once done, run the commands below to complete the build of the installation medium

```sh
$ junita-desktop --dis /DRIVE LETTER
```
After it's complete, you can run the command to begin the verification process
```sh
$ junita-desktop --verif-web start
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```


