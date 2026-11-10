# Hello there 👋

I'm Hari Srinivasan. More about me and what I build at **[harisrinivasan.dev](https://harisrinivasan.dev)**.

```kotlin
#!/usr/bin/env kotlin
@file:Suppress("EXPERIMENTAL_API_USAGE")

import kotlinx.coroutines.*

object SoftwareEngineer {
    val name = "Hari Srinivasan"
    val role = "Software Developer"
    val languagesUsed = listOf("Kotlin", "Python", "Go", "C", "BASH")

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

[![My Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/Haz3-jolt?cardType=level&theme=github-dark&fontFamily=&preferLogin=false)](https://git.io/awesome-stats-card)
