# gspemirror
GSPE Mirror


clone this project to your raspberry



## Installation

### Raspberry Pi

#### Automatic Installation (Raspberry Pi only!)

*Electron*, the app wrapper around MagicMirror², only supports the Raspberry Pi 2/3. The Raspberry Pi 0/1 is currently **not** supported. If you want to run this on a Raspberry Pi 1, use the [server only](#server-only) feature and setup a fullscreen browser yourself. (Yes, people have managed to run MM² also on a Pi0, so if you insist, search in the forums.)

Note that you will need to install the lastest full version of Raspbian, **don't use the Lite version**.

Execute the following command on your Raspberry Pi to install MagicMirror²:

```bash
bash -c "$(curl -sL https://raw.githubusercontent.com/yasir16/gspemirror/master/installers/raspberry.sh)"
```

#### Manual Installation

1. Download and install the latest *Node.js* version.
2. Clone the repository and check out the master branch: `git clone https://github.com/MichMich/MagicMirror`
3. Enter the repository: `cd MagicMirror/`
4. Install and run the app with: `npm install && npm start` \
   For **Server Only** use: `npm install && node serveronly` .
