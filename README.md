# TutorialCommentFeedbackSystem
# Tutorial Comment & Feedback System

[![Java](https://img.shields.io/badge/Java-17-blue)](https://www.java.com/) 
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A **Java console application** that allows users to manage tutorials and interact with them through comments and ratings. This project demonstrates **object-oriented programming (OOP)** concepts, including classes, arrays, and basic CRUD operations.

---

## Features

| Feature | Description |
|---------|-------------|
| **Add Tutorials** | Create new tutorials with a unique ID, title, and description. |
| **Add Comments** | Users can comment on tutorials with username, comment text, and rating (1-5). |
| **View All Tutorials** | Display all tutorials along with their comments and ratings. |
| **Search Tutorial by ID** | Quickly find a tutorial using its unique ID. |
| **Update Comments** | Modify an existing comment's text and rating. |
| **Delete Comments** | Remove a comment from a tutorial. |
| **Interactive Console Menu** | Easy-to-use menu for managing tutorials and comments. |

---

## Project Structure

- `Comment` – Represents a single user comment with username, text, and rating.  
- `Tutorial` – Represents a tutorial with multiple comments and methods to manage them.  
- `TutorialCommentFeedbackSystem` – Main class that provides the console interface for the system.

---

## Usage Example

```java
// Adding a new tutorial
Tutorial t = new Tutorial(1, "Java Basics", "Introduction to Java");
t.addComment(new Comment("Alice", "Very helpful!", 5));
t.displayTutorial();
