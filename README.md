# Entity-Relation Diagrams for Homework 2

## Overview
This repository contains the Quarto HW2 for Homework 2 of CMSC 608 - Spring 2025. The HW2 presents ER diagrams for three selected scenarios, modeled using both Chen and Crow’s Foot notations. Additionally, it includes relation schemas and design choices for each scenario.

## Repository Structure
```
Advance_db/
│── README.md  # This file
│── HW2.qmd  # Quarto source file for the HW2
│── diagrams/  # Directory containing ER diagrams inside the HW2.wmd
│── output/  # Directory containing generated HTML/PDF HW2s
```

## Selected Scenarios
The following three scenarios are covered:

1. **Library Management System**  
   A library needs to manage books, members, and loans. Each book has a unique book ID, title, and author. Members have a member ID, name, and membership date. A member can borrow multiple books, but each loan is associated with only one book and one member. The system must track loans and ensure books are returned on time.

2. **Real Estate Listing System**  
   A real estate agency manages property listings, agents, and clients. Each property has a property ID, address, and listing price. Agents have an agent ID, name, and contact details. Clients have a client ID, name, and budget. Agents handle multiple properties, but each property is listed by a single agent. Clients can express interest in multiple properties, and each property can have multiple interested clients.

3. **School Course Enrollment System**  
   A school tracks courses, students, and enrollments. Each course has a unique course ID, title, and credit value. Students have a student ID, name, and enrollment date. A student can enroll in multiple courses, and each course can have multiple enrolled students. The enrollment entity captures additional details such as enrollment date and grade.

## ER Diagram Notations
- **Chen Notation**: Created using Graphviz DOT.
- **Crow’s Foot Notation**: Created using Mermaid.js.

## How to View the HW2
To generate and view the HW2, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/mohammedt2/Advance_db.git
   ```
2. Install Quarto if not already installed: [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)
3. Render the HW2:
   ```sh
   quarto render HW2.qmd
   ```
4. Open the generated HTML/PDF file from the `output/` directory.

## Dependencies
Ensure you have the following installed:
- **Quarto** (for rendering the HW2)
- **Graphviz** (for generating Chen notation diagrams)
- **Mermaid.js** (for Crow’s Foot notation diagrams, embedded in Quarto)

## Author
Taher Hussain Mohammed

## License
This project is for educational purposes as part of CMSC 608 - Spring 2025.
