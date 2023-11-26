# Tmux+shell+mytheme
## Back up for my linux and macos also you can get and use if u like <3

This include neovim, zsh shell, oh my zsh, tmux and omz plugins

- Some my picture of me on linux and macOS
- See HTML in the right
- ✨Magic ✨

## Features

- Using tmux terminal to have muti windows terminal
- Neo vim for quiz editor and using as IDE if you like
- Theme using pk10k u can custom as you want
- I have some basic plugins help using terminal more effective

## Installation

Basic required to install file from git repo is 
- zsh shell [zsh](https://www.zsh.org/)
- Tmux [tmux](https://github.com/tmux/tmux)
- Terminal app i using [alacritty](https://github.com/alacritty/alacritty) u can use what termial app u like
- [Brew](https://brew.sh/) for MacOs user

# Install on linux 
#---------- install zsh
### Step 1: Update the System Repository

Update the system package repository to get the latest program version available. Open the terminal and run the following command:

```bash
sudo apt update
```

### Step 2: Install Zsh
Run the following command to install Z Shell on Ubuntu:
```bash
sudo apt install zsh -y
```
### Step 3: Check Installation
After the installation finishes, check if it has been installed correctly by checking the program version. Run the following command:
```bash
zsh --version
```
### Step 3: Initial Configuration
Unlike Bash and other shells, Zsh requires initial configuration when you start it for the first time. To start Zsh, type the shell name in the terminal and press Enter:
```bash
zsh
```
- This will be run the init config for zsh config file usually file in ~/.zshrc alias /home/$USER/.zshrc
- The options will show up and reconmend using is number 2 type 2 and enter.

### Step 3: Set Zsh as Default Shell
1. Check which shell is the default one in your system:
```bash
echo $SHELL
```
If you default shell is not zsh so u need to change it using command
```bash
chsh -s $(which zsh)
```

#---------- install 

# Plugins




```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
