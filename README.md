# Kotlin Hello World Project

A minimal Kotlin project to demonstrate basic setup and execution.

## 🚀 Quick Start

### Prerequisites
- JDK 8+ ([Download](https://adoptium.net/))
- IntelliJ IDEA (or VS Code with Kotlin plugin)

### Running the Project
1. **Using IntelliJ:**
    - Open `src/main/kotlin/Main.kt`
    - Click the green ▶️ "Run" button next to `main()`

2. **Via Command Line:**
   ```bash
   # Compile and run (if using the JAR method)
   kotlinc src/main/kotlin/Main.kt -include-runtime -d hello.jar
   java -jar hello.jar
   ```

## 📁 Project Structure
```
kotlin-hello-world/
├── src/
│   └── main/kotlin/
│       └── Main.kt      # Main Kotlin file
└── README.md            # This file
```

## 🛠 Troubleshooting
| Error | Solution |
|-------|----------|
| `Unresolved reference` | Ensure file is in `src/main/kotlin/` |
| `Kotlin not installed` | Install via IntelliJ or `sdk install kotlin` |

## 📚 Resources
- [Kotlin Docs](https://kotlinlang.org/docs/)
- [IntelliJ Guide](https://www.jetbrains.com/help/idea/getting-started-with-kotlin.html)