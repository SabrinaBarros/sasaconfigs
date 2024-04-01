# 🐧 Ubuntu Configs ⚙️

![Linux vs GitHub](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wlqz1ybvil42fg9ysbtz.gif)

- [Terminal](#💲-terminal-🏴‍☠️)
  - [GIT](#git-🔗)
    - [SSH Auth](#ssh-auth)
  - [Package Manager](#package-manager-🗃)
    - [NPM](#npm)
  - [Node](#Node-🥝)
    - [Node Version Manager](#node-version-manager)
      - [N](#n)
- [Dev App's](#🖥-dev-app's-📃)
  - [VS Code](#vs-code-👁️)
- [Utilities](#🎧-utilities-🎲)
  - [Discord](#discord-👺)
  - [Spotify ](#spotify-🎶)
  - [Krita](#krita-🎨)

# 💲 Terminal 🏴‍☠️

![Computer error](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vts1hgq2ijfx8ierix34.gif)

## GIT 🔗

- Install

```shell
$ apt-get install git
```

- Configs

```shell
$ git config --global user.name "Sabrina Barros"
$ git config --global user.email sabrina.barros2045@gmail.com
```

```shell
$ git config --global init.defaultBranch main
```

### SSH Auth

- Generate Key

```shell
$ ssh-keygen -t ed25519 -C "sabrina.barros2045@gmail.com"
```

- Add to SSH Agent

```shell
$ eval "$(ssh-agent -s)"
```

```shell
$ ssh-add ~/.ssh/id_ed25519
```

- Access SSH Key

```shell
$ cat ~/.ssh/id_ed25519.pub
```

## Package Manager 🗃

### NPM

```shell
$ sudo apt install npm
```

## Node 🥝

- Install

```shell
$ sudo apt install nodejs
```

- Verify Node Version

```shell
$ nodejs -v
```

### Node Version Manager

#### N

```shell
$ npm install -g n
```

# 🖥 Dev app's 📃

![Dev Girl](https://steamuserimages-a.akamaihd.net/ugc/90470964761468233/EBE96184DD5BD1AFD12E7550B87CE0E24D9772AB/)


## VS Code 👁️

- Download [.deb package (64-bit)](https://code.visualstudio.com/docs/setup/linux)

- Install

```
$ sudo apt install ./vsc.deb
```

# 🎧 Utilities 🎲

![Coke](https://static.tumblr.com/c7d92aa4aa7ee45c01aab1de252875ff/ulxonxw/bmnomc2jy/tumblr_static_tumblr_static_bg6546zyo3s4gks4ww8k00w4g_focused_v3.gif)

## Discord 👺

```
$ wget https://dl.discordapp.net/apps/linux/0.0.12/discord-0.0.12.deb
```

```
$ sudo apt install ./discord-0.0.12.deb
```

## Spotify 🎶

```
$ snap install spotify
```

## Krita 🎨

- Add repository

```
sudo add-apt-repository ppa:kritalime/ppa
```

- Update APT

```
sudo apt-get update
```

- Install

```
sudo apt-get install krita
```