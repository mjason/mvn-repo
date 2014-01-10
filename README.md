mvn-repo
========

```
repositories {
    mavenCentral()

    maven {
        url "https://github.com/mjason/mvn-repo/raw/master"
    }
}

dependencies {
    compile "cn.glassx:NGDK:0.0.1@aar"
}
```