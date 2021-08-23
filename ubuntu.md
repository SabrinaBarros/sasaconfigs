# 🐧 Ubuntu Configs ⚙️

![Linux vs GitHub](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wlqz1ybvil42fg9ysbtz.gif)

- [Terminal](#💲-Terminal-🏴‍☠️)
  - [Package Manager](#Package-Manager) 
    - [NPM](#npm)
    - [SNAP](#snap)
  - [GIT](#git-🔗)
  - [Node](#Node-🥝)
- [Dev App's](#🖥-Dev-app's-📃)
  - [VS Code](#VS-Code-👁️)
- [Utilities](#-🎧-Utilities-🎲)
  - [Discord](#Discord-👺)
  - [Spotify ](#Spotify-🎶)

# 💲 Terminal 🏴‍☠️

![Soft Tired](https://data.whicdn.com/images/325724253/original.gif)

## Package Manager 🗃

### NPM

```
$ sudo apt install npm
```

### SNAP

```
$ sudo apt-get install snapd snapd-xdg-open
```

### YARN

- NPM

```
sudo npm install yarn -g
```

- Curl (*recommended*)

```
$ curl -o- -L https://yarnpkg.com/install.sh | bash
```

<hr>

## GIT 🔗

```
$ apt-get install git
```

## Node 🥝

- Install

```
$ sudo apt install node
```

- Remove

```
$ sudo apt remove node
```

# 🖥 Dev app's 📃

![Dev Girl](https://steamuserimages-a.akamaihd.net/ugc/90470964761468233/EBE96184DD5BD1AFD12E7550B87CE0E24D9772AB/)


## VS Code 👁️

- Install

```
$ sudo snap install --classic vscode
```

- Att

```
sudo snap refresh vscode
```

- Remove

```
sudo snap remove vscode
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