# F-Droid Repo

This is a repository of my apps to be used with F-Droid

## Repo 

https://ikas-mc.github.io/fdroid-repo

fingerprint:

A4F1C60EB4D3A8FDE4644DBAC9F9834E3C06B69E4EACF8A7FF5423339523071B

https://ikas-mc.github.io/fdroid-repo/?fingerprint=A4F1C60EB4D3A8FDE4644DBAC9F9834E3C06B69E4EACF8A7FF5423339523071B



## For dev
Setup an F-Droid App Repo

https://f-droid.org/zh_Hans/docs/Setup_an_F-Droid_App_Repo/

```
fdroid init

keytool -genkey -keystore ikas -alias your -keyalg RSA -keysize  4096 -sigalg SHA256 withRSA -validity  10000  -storetype pkcs12   -dname "CN=your" -J-Duser.language=en

vim config.yml 

fdroid update  -c --pretty  --rename-apks
```
