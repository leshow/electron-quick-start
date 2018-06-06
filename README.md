# electron-quick-start

Repo for replicating issue w/ `electron` 2.0.2 and native-modules using `node-pre-gyp`

Follow the steps here **EXACTLY**:

```bash
# Clone this repository
git clone https://github.com/leshow/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install --arch=ia32
# set native module deps
export npm_config_target=2.0.2
export npm_config_arch=ia32
export npm_config_target_arch=ia32
export npm_config_disturl=https://atom.io/download/electron
export npm_config_runtime=electron
export npm_config_build_from_source=true
#install lzma-native
npm i lzma-native@3.0.8
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
