# Hello there 👋

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



## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=Haz3-jolt&show_icons=true&theme=tokyonight&hide_border=true" />
