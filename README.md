# Text Cleaner Tool

A simple yet powerful **Java console application** that allows users to clean, format, and modify text with ease. Designed for developers, students, writers, or anyone who deals with messy text, this tool offers multiple text editing operations directly in the console without any external dependencies.

---

## 🚀 Features

- **Remove Extra Spaces**: Converts multiple spaces into a single space and trims the text.
- **Remove Extra Lines**: Deletes empty lines to produce clean, compact text.
- **Convert Text Case**:  
  - Lowercase  
  - Uppercase  
- **Capitalize First Letter of First Line**: Quickly formats the beginning of your text for readability.
- **Supports Multi-line Input**: Paste paragraphs or long text blocks directly in the console.
- **Interactive Console Menu**: Choose which operations to apply step by step.

---

## 💻 Tech Stack

- **Java** – programming language for application logic
- **Java Standard Library** – string manipulation and console input/output
- **JDK** – to compile and run the application
- **Git & GitHub** – version control and repository hosting

Optional / Future Enhancements:  
- JavaFX for GUI  
- Android Studio + Java for mobile version  

---

## 🔎 Installation & Setup

1. **Clone the repository**
git clone https://github.com/YourUsername/TextCleanerTool.git

2. Navigate to the src folder
cd TextCleanerTool/src

2. Compile the Java program
javac TextEditorTool.java

4. Run the program
java TextEditorTool

## 💎 Demo Usage

Enter your text (type 'END' to finish):
> This  is    some    messy text.

> It has extra spaces, empty lines, and inconsistent case.
> END

Remove extra spaces? (0-No, 1-Yes): 1
Remove extra lines? (0-No, 1-Yes): 1
Convert to lowercase? (0-No, 1-Yes): 0
Convert to uppercase? (0-No, 1-Yes): 0
Capitalize first letter of first line? (0-No, 1-Yes): 1

Here is your edited text:

This is some messy text.
It has extra spaces, empty lines, and inconsistent case.
