# React Native with Redux example


### Possible problems

- [Lexycally nested](https://github.com/facebook/react-native/issues/11389)
- The user limit on total number of inotify watches was reached - [issue](https://github.com/facebook/watchman/issues/163)
```shell
echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_watches && echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_queued_events && echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_instances && watchman shutdown-server
```

### How to use

install

```shell
# Install react native cli globally (Use yarn if you want)
npm install -g react-native-cli

# Local dependencies (Use yarn if you want)
npm i
```

Change your Sdk folder on `local.properties` in `android` folder

Boots up your emulator and run `react-native run-android` and soon after `npm start`
