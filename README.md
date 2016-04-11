


## command logs


```
npm install -g ionic@beta
ionic start cutePuppyPics --v2

npm install -g cordova
npm install -g ios-deploy
npm install -g ios-sim


cd cutePuppyPics
ionic serve
```


Xcodeをインストールすること。
Android Studio をインストールする。
また、`SDK Manager`でAndroid SDK のバージョン `Android 6.0` をインストールしておく。

XcodeもAndroid Studioも、インストール直後の状態だと動かない。
それぞれで、テストプロジェクトを作って、エミュレータが動く状態にしておく。
例えば、Android Studioでは `AVD` を作っておく必要がある。


## 各エミュレータでアプリを起動
Androidの場合は、 `ionic run android` してエミュレータを起動してから、アプリを起動しないとうまく表示されない。

```
ionic platform add ios
ionic emulate ios


ionic platform add android
ionic run android
ionic emulate android
```


```
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!! WARNING: You are on OS X 10.11 El Capitan, you may need to add the
!!!! WARNING:   `--unsafe-perm=true` flag when running `npm install`
!!!! WARNING:   or else it will fail.
!!!! WARNING: link:
!!!! WARNING:   https://github.com/phonegap/ios-deploy#os-x-1011-el-capitan
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
```



```
cd ../
ionic start MyIonic2Project tutorial --v2
cd MyIonic2Project/
ionic serve
```


