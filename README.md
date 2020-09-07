# JUnique 

Helps in preventing multiple instances of the same application. Fork of: [JUnique](http://www.sauronsoftware.it/projects/junique/). Source code was left unchanged, only build system was replaced.

# Using in your own project

Add the repository to your repositories section:
```groovy
repositories {
    maven {
        url = uri('https://maven.pkg.github.com/tomasz-herman/JUnique')
        credentials {
            username = "token"
            password = "\u0033\u0038\u0038\u0063\u0034\u0034\u0062\u0039\u0037\u0034\u0032\u0035\u0065\u0061\u0036\u0065\u0064\u0066\u0031\u0065\u0030\u0033\u0039\u0032\u0066\u0063\u0064\u0031\u0064\u0065\u0031\u0039\u0036\u0039\u0038\u0064\u0064\u0039\u0039\u0061"
        }
    }
}
```
Then add the dependency:
```groovy
dependencies {
    implementation 'it.sauronsoftware:junique:1.0.4'
}
```

# License

JUnique is **Free Software** and it is licensed under **LGPL**.