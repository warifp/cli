# OGCheckr CLI

### About
This is a script I made a while back to check the availability of OG words as handles on the various social media platforms. For the most part, it works with any site that has web-based profile pages.

### Known Supported Services
- ~~Minecraft~~ - For your Minecraft checking needs, check out [this](http://www.mc-market.org/resources/4480/) awesome checker instead!
- Twitter (currently broken)
- Instagram (currently broken)
- Steam ID URLs
- Steam Group URLs
- Mixer (formerly Beam.pro)
- Soundcloud
- Github
- About.me
- YouTube (partial support)
- Pastebin


### Known Unsupported Services
- Snapchat
- Kik

### Comptability
Version `1.4-1.9+` is only compatible with Python 3+

Version `1.0-1.3` is compatible with Python 2 & 3

### Pre-Requisites
Please be sure to run the appropriate Python 3 [installer](https://www.python.org/downloads/) before preceding with the installation.

On the following screen of the installer, be sure the checkbox next to `Add Python to environment variables` is **checked** like so...
![screenshot](https://d.pr/i/JNFcQT+)

### Installation

1. Download the zip or clone the repo with Git on your local machine.

2. Install the dependencies using the following command inside Command Prompt (Windows) or Terminal (Mac). If you use `Python.exe`, it will **not** work.

    ```
    python -m pip install -r requirements.txt
    ```

4. Edit the `config.ini` inside your favorite text editor. I have put lots of comments to explain what each option does.

5. Now you need to make your terminal know where to find the checker files, so type the following command in Command Prompt or Terminal.

```
cd path
```

_Note:_ Do not type the actual word `path`. Instead, type the direct path to the username checker folder you downloaded and extracted.

6. Run the script via command line using the following command

    ```
    python og.py
    ```
If it says the file cannot be found, you are using an outdated version of this program. Either change the command as follows or download the latest version.

```
python OGCheckr.py
```

If you still need help, please join the [CrocBuzz Studios Discord community](https://discord.gg/hpbQayV) for free support :)

### Contributing 
As this is just a personal side project, I only work on it when I have time, so I would love your help to make improvements! Just make a pull request and I'll review the changes as soon as I can. 

If you are not a developer, you can also help me greatly by opening issues with bugs you encounter while running the script.

If you would like to see further improvements and updates for free, please consider donating a few dollars as it really helps me to set aside time out of my busy schedule to work on improving the script. All contributions are great appreciated! 🙂

[PayPal](https://paypal.me/croc)

[Square Cash](https://cash.me/$croc)

For additional information and installation instructions, view the wiki.
https://github.com/crock/cli-checker/wiki/
