# Simple Minds: Quiz Application

This project demonstrates a structured approach to building a GUI-based Java application, incorporating user interaction, file handling, and event management effectively.

## Goal of the Project:
- To enhance Java programming skills.
- To learn to contribute to open-source projects.
- To improve Object-Oriented Programming.

## Libraries Used:
```
Javax.swing
Java.awt
Java.awt.event
Java.io.*;
Java.util.ArrayList;
Java.util.List;
```

## Core Functions:

```
setBounds(), setContentPane(), setForeground(), setBackground(), add(), set.text(), setFont(), setLayout(), SetVisible(), actionPerformed(), getSource(), getSelection(), getActioncommand()
```

## Project Workflow:
### Start Screen:
- User enters their name in a text field.
- Two buttons: Rules (shows rules) and Exit (closes application).

### Rules Screen:
- Displays quiz rules in an HTML-styled text area.
- Two buttons: Start (begins quiz) and Back (returns to start screen).

### Quiz Screen:
- Displays 10 questions with four multiple-choice options each.
- Options use JRadioButton grouped by ButtonGroup.
- Three buttons: Next (proceeds to the next question), 50/50 Lifeline (removes two incorrect options, usable twice), Submit (ends quiz and shows score).

### Question Management:
- Questions, options, and correct answers are read from a text file using FileReader and BufferedReader.
- Questions, correct answers, and user answers are stored in arrays (q[][], ca[], ua[][]).

### Event Handling (actionPerformed):
- **Next**: Checks if the current question was answered, stores the answer, and moves to the next question.
- **50/50 Lifeline**: Disables two incorrect options.
- **Submit**: Finalizes answers, compares them with correct answers, and calculates the score.

### Scoring:
- Each correct answer awards 10 points.
- Total score is displayed at the end of the quiz.

## Technical Highlights:

- GUI designed using JFrame, JLabel, JButton, JTextField, and JRadioButton.
- Data stored and managed using arrays and lists.
- Event-driven programming using ActionListener.

## Credits
This project is a fork originally developed by Kunal Tyagi.
You can find the original project [here](https://github.com/kunaltyagi9/Quiz-Application-Using-Java).
