# AI Exercise Generator

## Description

The AI Python Programming Exercise Generator is designed for Computer Science undergraduate students to practice Python programming through a variety of exercise types. The tool features an intuitive design, allowing students to log in, continue their progress, and track their history in a MySQL database. Each type of exercise is hosted on a different webpage with a unique layout:

1. **Coding Exercises**: A VS Code-like coding interpreter with a robust keystroke data collection backend for behavior analysis and learning trajectory tracking.
2. **Troubleshooting Exercises**: A coding interpreter where students can debug dysfunctional code, also featuring keystroke data collection.
3. **Parsons Problems**: A drag-and-drop interface to arrange code blocks in the correct order.
4. **Multiple Choice Questions (MCQs)**: Radio buttons for selecting the correct answer for each question.
5. **Fill in the Blanks**: Text boxes for students to write their answers.

The tool connects to a MySQL database containing 11,700 exercises across 78 unique topics from the "Introduction to Python Programming" course catalog. These exercises span 5 different types and 3 difficulty levels, with 10 unique exercises per difficulty level. The database tracks student activity, including exercises retrieved, attempted, coding history, and keystrokes.

![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Webapp%20Flowchart.jpg)

## Technology Stack

### Client End
- **Nuxt.js**: Framework for creating Vue.js applications
- **Vue 3**: JavaScript framework for building user interfaces
- **Vue Router 4**: Official router for Vue.js

### Back End
- **Flask**: Micro web framework for Python
- **Flask-SocketIO**: Socket.IO integration for Flask applications
- **Flask-CORS**: Handling Cross-Origin Resource Sharing (CORS)
- **MySQL**: Database management system
- **Knex.js**: SQL query builder for JavaScript
- **Monaco Editor**: Code editor for the web

### Additional Dependencies
- **bcryptjs**: Library for hashing passwords
- **ifvisible.js**: Library to detect page visibility
- **marked**: Markdown parser and compiler
- **next-auth**: Authentication for Next.js
- **safe-await**: Handling promises safely
- **socket.io-client**: Real-time bidirectional event-based communication
- **sqlite3**: SQLite database library
- **ts-node**: TypeScript execution environment
- **vuetify-nuxt-module**: Vuetify module for Nuxt.js

## Video Demo
Box Video: https://usu.box.com/s/bpwfmknfnypi79o09s29bif2pbvct374

## Screenshot Demo
### Authentication
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Sign%20In%20Page.png)
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Registration%20Page.png)

### Dashboard & User Progress
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Dashboard.png)

### Coding Exercises with AI Feedback
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Coding%20Exercise%20Page%20%28AI%20Feedback%20Full%29.png)

### Troubleshooting Exercises
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Troubleshooting%20Page%20%28AI%20Feedback%29.png)

### Parsons Problem
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/Parsons%20Page%20%28Correct%20Solution%29.png)

### Multiple Choice Questions (MCQ)
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/MCQ%20Page%20%28Interacted%29.png)

### Fill in the Blanks
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/FIB%20Page%20%28Default%29.png)
![](https://github.com/mfawadakbar/CodeClimberAI/blob/53d3a751e0080074210846f917359af22ff87ce6/FIB%20Page%20%28Interacted%29.png)

