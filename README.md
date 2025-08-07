## Kotlin Beginner's Toolkit: Hello World with GenAI
Objective: Learn Kotlin from scratch using AI prompts and create a simple "Hello World" program.

## 1. Title & Objective
**Title: "Getting Started with Kotlin – A Beginner’s Guide"**
**Why Kotlin?**
- Modern, concise, and fully interoperable with Java.
- Official language for Android development.
- Used by companies like Google, Netflix, and Uber.

Goal: Write, compile, and run a Kotlin "Hello World" program.

## 2. Quick Summary of Kotlin
What is Kotlin? 
A statically typed JVM language developed by JetBrains.
Use Cases: Android apps, backend services, multiplatform apps
Real-World Example: Pinterest, Trello, and Evernote use Kotlin.

## 3. System Requirements
# Features
- Simple "Hello World" output
- Demonstrates Kotlin's concise syntax
- Shows function declaration and string templates
- Ready-to-run template for beginners

# Prerequisites
- [JDK 8+](https://adoptium.net/) (Recommended: JDK 17)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) (2023.2+)
- Kotlin 1.8+ (Bundled with IntelliJ)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Michelle-Mungai/Hello_World_Kotlin

2. Open in IntelliJ:
Select File → Open and choose the project folder
Wait for Gradle/Kotlin plugins to sync (automatic in IntelliJ)

## Command Line
Usage
Running in IDE
Open src/main/kotlin/Main.kt
Click the green ▶️ Run button next to main()

# Compile to JAR
kotlinc src/main/kotlin/Main.kt -include-runtime -d hello.jar
# Execute
java -jar hello.jar

## Project Structure
kotlin-hello-world/

├── src/
│   └── main/kotlin/
│       └── Main.kt      # Main application file
├── .gitignore           # Standard Kotlin/JVM ignores
└── README.md            # This file

## Sample Code
fun main() {
    println("Hello, Kotlin World!") 
    greet("Developer")  // Demonstrates function call
}

/** 
 * Greets a user with Kotlin's string templates
 * @param name The person to greet
 */
fun greet(name: String) {
    println("Welcome, $name!")  // String interpolation
}

## Troubleshooting
# Error	                                Solution
Unresolved reference: println       	Ensure file is in src/main/kotlin/
Kotlin not installed	                Install via IntelliJ or sdk install kotlin
JDK not found	                        Set JDK path in File → Project Structure → SDKs
NoClassDefFoundError	                Use -include-runtime when compiling JARs

## 🚨 Common Errors During Setup

### 1. Git Integration Issues
**Error:**  
`Cannot Run Git: No such file: git.exe`

**Solution:**  
- **Install Git** from [git-scm.com](https://git-scm.com/downloads)  
- Configure path in IntelliJ:  
  **File → Settings → Version Control → Git** → Set path to:  
  - Windows: `C:\Program Files\Git\bin\git.exe`  
  - Mac/Linux: `/usr/bin/git`  
- Verify installation in terminal:  
  ```bash
  git --version
  
## Contributing
1. Fork the project
2. Create your feature branch (git checkout -b feature/improvement)
3. Commit changes (git commit -m 'Add new feature')
4. Push to branch (git push origin feature/improvement)
5. Open a Pull Request
