# Cordova Plugin NativeStorage Example

## Steps

**1. Clone Repo**

  ```
  $ git clone git@github.com:erisu/cordova-plugin-nativestorage-example.git
  ```

**2. Add Your Signing Information**

Edit file `build.json`.

**3. Update Bundle ID**

Search for `com.foobar.hogehoge` and relace with your bundle id. Should find in files:
* `config.xml`
* `package-lock.json`
* `package.json`

**4. Add Platform**

  ```
  $ cordova platform add ios@4.5.5
  ```

  **5. Test On iPhone Device**

  ```
  $ cordova run ios --device
  ```

## Notes

* `build.json` contains a workaround that will be fixed in `cordova-ios@5.0.0`.