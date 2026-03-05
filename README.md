# Terdroid
Make An Android apk Project easily with termux

some libraries had to be patched for this to work on termux like `AAPT2`

# Requirements
- Android Sdk, Gradle
  ```bash
  export ANDROID_HOME=$HOME/Android/Sdk
  export ANDROID_SDK_ROOT=$ANDROID_HOME
  export PATH=$PATH:$ANDROID_HOME/platform-tools
  export PATH=$PATH:$ANDROID_HOME/cmdline-tools/latest/bi
    n
  ```
  ```bash
  pkg install gradle
  ```

# Installation
```bash
 bash <(curl -Lf https://raw.githubusercontent.com/banyadm/terdroid/main/setup)
```
