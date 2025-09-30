📝 To-Do List App (Java Swing)

A simple desktop To-Do List application built using Java Swing (JDK 17).
This project demonstrates the basics of GUI development with JFrame, JButton, JTextField, and JList in a modular Java project.

🚀 Features
Add new tasks
Delete selected tasks
Enter key shortcut to add tasks
Scrollable task list
Input validation (no empty tasks)

🛠️ Tech Stack
Language: Java 17
GUI Toolkit: Swing (javax.swing, java.awt)
IDE: Eclipse / IntelliJ IDEA (Community Edition)

📂 Project Structure
ToDoAppProject/
 ├── src/
 │    └── todoapp/
 │         ├── ToDoApp.java
 │         └── module-info.java


module-info.java → declares requires java.desktop;
ToDoApp.java → main class with Swing UI code

▶️ How to Run
Install JDK 17 and an IDE (Eclipse/IntelliJ).
Clone this repository:
git clone https://github.com/thulasikumar023/Java-GUI-ToDoApp.git

Import the project into your IDE.
Make sure module-info.java includes:

module todoapp {
    requires java.desktop;
}
Run ToDoApp as a Java Application.

🎯 Learning Outcome
Understanding Java Swing basics
Event handling with ActionListener
Managing tasks with DefaultListModel and JList
Setting up and running a modular Java project on JDK 17
