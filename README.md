# Hello there 👋

```kotlin
#!/usr/bin/env kotlin
@file:Suppress("EXPERIMENTAL_API_USAGE")

import kotlinx.coroutines.*

object SoftwareEngineer {
    val name = "Hari Srinivasan"
    val role = "Software Developer"
    val languagesUsed = listOf("Kotlin", "Python", "BASH", "C")

    suspend fun sayHi() = coroutineScope {
        launch {
            delay(500)
            println("Thanks for dropping by, hope you find some of my work interesting.")
        }
    }

    fun showStack() {
        println("Currently building cool things with: ${languagesUsed.joinToString(", ")}")
    }
}

suspend fun main() {
    SoftwareEngineer.sayHi()
    SoftwareEngineer.showStack()
}

```



## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=haz3-jolt&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)

