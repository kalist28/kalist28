```kotlin
val DmitryKalistratov = human {
    about {
        name = "Dmitry Kalistratov"
        role = Developer(Android, iOS)
    }

    tech {
        day("Kotlin", "app creation")
        night(".*".toRegex())
    }

    links {
        telegram = "@kalist28"
        email = "dmitry@kalistratov.ru"
    }
}
```
