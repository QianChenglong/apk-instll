# apk-install

Windows下双击`*.apk`文件，安装到手机！

# 安装

-   修改`install.reg`中的`adb.exe`路径

```reg
[HKEY_CLASSES_ROOT\AndroidPackage\Shell\Open\Command]
@="E:\\Programming\\SourceCode\\apk-install\\adb.exe install -r \"%1\""
```
-   双击`install.reg`即可
