# Electron wrapper for Outlook Web App

This wraps the Outlook Web Application (OWA) in an Electron container for easy desktop usage. It adds features like auto-login, desktop notifications and S/MIME support.

**This is a work in progress, is lacking many features and is most certainly not ready for productive use.**

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/Doccrazy/electron-owa
# Go into the repository
cd electron-owa
# Install dependencies
npm install
# Run the app
npm start
```

## Package executable

To create an executable package of Electron OWA for your platform, run:

```bash
# Package for Windows
npm run package-win
# Package for Linux
npm run package-lin
```
