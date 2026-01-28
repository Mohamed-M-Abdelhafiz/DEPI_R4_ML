\documentclass[12pt]{article}

\usepackage[a4paper, margin=1in]{geometry}
\usepackage{setspace}

\onehalfspacing

\title{Employee Data Management System}
\author{}
\date{}

\begin{document}

\maketitle

\section*{Project Overview}

This is a simple Employee Management System built using Python.
The program allows the user to manage employee records using a menu-based command-line interface.

The project is designed to practice core Python concepts such as Object-Oriented Programming (OOP),
dictionaries, CSV file handling, and basic data validation.

\section*{Project Features}

\begin{itemize}
    \item Add a new employee (ID, Name, Position, Salary, Email)
    \item View all employees
    \item Update employee details using employee ID
    \item Delete an employee by ID
    \item Search for an employee by ID
    \item Save all data in a CSV file
    \item Load data automatically when the program starts
\end{itemize}

\section*{Technologies Used}

\begin{itemize}
    \item Python 3
    \item csv module
    \item Dictionary for in-memory storage
    \item Command Line Interface (CLI)
\end{itemize}

\section*{How the Program Works}

\begin{enumerate}
    \item When the program starts, employee data is loaded from \texttt{employees.csv}.
    \item The user chooses an option from the menu.
    \item The selected operation is performed (add, update, delete, search, or view).
    \item Any changes are saved back to the CSV file.
    \item The program continues running until the user chooses Exit.
\end{enumerate}

\end{document}
