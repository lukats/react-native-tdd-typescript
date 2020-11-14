## need

`node` `detox-cli` `cocoapods` `yarn`

##

### commands

```
sudo gem install cocoapods
brew tap wix/brew
brew install applesimutils
yarn global add detox-cli
```

#### pre-start

```
yarn install
cd ios && pod install && cd ..
```

#### start

##### ios

```
npx react-native run-ios
```

##### android

```
npx react-native run-android
```

##

### e2e test commands

#### for ios

```
detox build -c ios.sim.debug
detox test -c ios.sim.debug
```

##### or

```
detox build -c ios.sim.release
detox test -c ios.sim.release
```

#### for android

```
detox build -c android.emu.debug
detox test -c android.emu.debug
```

##### or

```
detox build -c android.emu.release
detox test -c android.emu.release
```
