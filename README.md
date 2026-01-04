**🎯 Quiz Game Application (Java + SQLite)**

A console-based Quiz Game application developed using Java and SQLite that allows users to answer quiz questions, calculate scores, and store results persistently in a database.

**📌 Features**

Interactive quiz game via console

Multiple-choice questions

Automatic score calculation

Persistent score storage using SQLite

Displays scoreboard/history of quiz attempts

**🛠️ Tech Stack**

Language: Java

Database: SQLite

JDBC: SQLite JDBC Driver

IDE: IntelliJ IDEA / Eclipse / VS Code (any Java-supported IDE)

**📂 Project Structure**

Quiz-Game/
│
├── QuizGame.java        # Main quiz logic
├── Scoreboard.java      # Score handling and display
├── quiz_scores.sqbpro   # SQLite database file
├── sqlite-jdbc-3.49.1.0.jar  # JDBC driver
└── README.md

**⚙️ How to Run the Project**

1️⃣ Clone the Repository
git clone https://github.com/your-username/quiz-game-java.git
cd quiz-game-java

2️⃣ Add SQLite JDBC Driver

Download the SQLite JDBC .jar file

Add it to your project’s classpath / libraries

3️⃣ Compile the Code
javac QuizGame.java Scoreboard.java

4️⃣ Run the Application
java QuizGame

**🗄️ Database Details**

Database Name: quiz_scores.sqbpro

Purpose: Stores user scores and quiz history

Integration: Connected using JDBC

**🎯 Learning Outcomes**

Hands-on experience with Java console applications

Understanding JDBC and database connectivity

Implementing persistent storage using SQLite

Writing modular and maintainable Java code
