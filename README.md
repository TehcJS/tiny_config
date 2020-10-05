# Tiny Config
The configuration API used by the Proton mod. You can use it too if you want.

## How to use:

### Import as a dependency:
Gradle Groovy:
```groovy
repositories {
    maven {
        name = "Jitpack"
        url = "https://jitpack.io/"
    }
}

// ...

dependencies {
    implementation("com.github.ProtonMC:tiny_config:master-SNAPSHOT")
}
```

Gradle Kotlin:
```kotlin
repositories {
    maven {
        name = "Jitpack"
        setUrl("https://jitpack.io/")
    }
}

// ...

dependencies {
    implementation("com.github.ProtonMC", "tiny_config", "master-SNAPSHOT")
}
```

This is planned to be moved into @HeyItsMeNobody\'s maven repo soon.
