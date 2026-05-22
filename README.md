# WebView APK 项目

## 你需要改的地方

### 1. 网站链接
打开：
`app/src/main/java/com/example/webviewapp/MainActivity.java`

找到：
```java
private final String WEBSITE_URL = "https://example.com";
```

改成你的网站：
```java
private final String WEBSITE_URL = "https://你的域名.com";
```

### 2. App 名字
打开：
`app/src/main/AndroidManifest.xml`

找到：
```xml
android:label="My App"
```

改成你的 App 名字。

## GitHub 自动打包方法

1. 注册/登录 GitHub
2. 新建 repository
3. 上传本项目全部文件
4. 进入 Actions
5. 点 Build APK
6. 点 Run workflow
7. 编译完成后，在 Artifacts 下载 APK

生成的文件叫：`app-debug.apk`
