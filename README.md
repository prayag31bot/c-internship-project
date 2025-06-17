---

# Trip App Internship Work Plan

---

## Introduction

The Trip Management Application is a console-based software developed in C to facilitate the management of users and their associated travel trips. This project aims to provide an intuitive interface for performing CRUD (Create, Read, Update, Delete) operations on user and trip data via terminal commands. It serves as an educational tool to apply core C programming concepts and fundamental software engineering practices such as data persistence, input validation, and modular programming. The app is designed to handle user information with unique identifiers and trip details linked to respective users, ensuring data consistency and ease of management.

---

## Methodology

The project was structured over four weeks, starting with foundational learning of C language constructs, file handling, and version control using Git. The development proceeded with implementing the User CRUD module, focusing on robust file-based storage and input validation. The Trip CRUD module followed, emphasizing relational integrity by validating trip-user associations. Each module was designed with modular code practices to promote maintainability.

File I/O operations were conducted using text files formatted in CSV style to store and retrieve records efficiently. Command-line arguments facilitated interaction with the application, enabling users to execute operations directly from the terminal. Comprehensive testing and error handling ensured the application behaves reliably under various input scenarios. Documentation and version control supported project transparency and reproducibility.

---

## Conclusion

The Trip Management Application successfully demonstrates how fundamental C programming techniques can be applied to build a functional terminal-based CRUD system. Through the development process, key skills such as struct management, file I/O, and command-line parsing were reinforced. The project highlights the importance of input validation and error handling in creating reliable software. While the application serves as a basic prototype, it lays the groundwork for more advanced features such as database integration, user authentication, and interactive menus. This project provides a solid foundation for further exploration of systems programming and software development best practices.

---

### Week 1: Learning & Setup

**Goal:** Get comfortable with C basics, file handling, and version control.

| Task                               | Details                                                                        | Status  |
| ---------------------------------- | ------------------------------------------------------------------------------ | ------- |
| Learn C basics                     | Variables, data types, control flow, functions                                 |  Done   |
| Practice structs and arrays        | Define User and Trip structs, experiment with arrays                           |  Done   |
| Learn file I/O in C                | Read/write files using `fopen`, `fgets`, `fprintf`                             |  Done   |
| Set up project structure           | Create folders: `/src`, `/data`, add `.gitignore`, `README.md`, and `Makefile` |  Done   |
| Initialize Git repo                | `git init`, create `.gitignore`, make initial commit, push to GitHub           |  Done   |
| Write README with project overview | Include project goals, basic usage, and folder structure                       |  Done   |

---

### Week 2: User CRUD Module

**Goal:** Implement all user management features with file persistence.

| Task                                | Details                                                         | Status  |
| ----------------------------------- | --------------------------------------------------------------- | ------- |
| Design User file format             | CSV with fields: id,name,email,phone,isActive                   | Pending |
| Implement auto-increment ID system  | Maintain last user ID in a counter file                         | Pending |
| Create User                         | Add new user, check for duplicate emails, assign unique ID      | Pending |
| Read User                           | Retrieve user by ID, name (partial/exact), or email             | Pending |
| Update User                         | Modify all fields except ID, validate email uniqueness          | Pending |
| Delete User                         | Remove user by ID or email                                      | Pending |
| Create CLI commands for User module | Add command-line parsing and execute appropriate user functions | Pending |
| Test User CRUD thoroughly           | Verify all operations and file integrity                        | Pending |

---

### Week 3: Trip CRUD Module

**Goal:** Build trip management features linked to users.

| Task                             | Details                                                         | Status  |
| -------------------------------- | --------------------------------------------------------------- | ------- |
| Design Trip file format          | CSV with fields: id,userId,destination,startDate,endDate,cost   | Pending |
| Implement auto-increment trip ID | Similar to user ID counter file                                 | Pending |
| Create Trip                      | Validate userId exists, add trip details                        | Pending |
| Read Trip                        | Retrieve by trip ID or list all trips for a user                | Pending |
| Update Trip                      | Update any trip field except trip ID, validate user ID and data | Pending |
| Delete Trip                      | Remove trip by trip ID                                          | Pending |
| Add CLI commands for Trip module | Command-line parsing and trip functions                         | Pending |
| Test Trip CRUD thoroughly        | Verify correctness and file consistency                         | Pending |

---

### Week 4: Finalization & Documentation

**Goal:** Polish, test, and document the project thoroughly.

| Task                                    | Details                                                                               | Status  |
| --------------------------------------- | ------------------------------------------------------------------------------------- | ------- |
| Comprehensive testing                   | Test all User & Trip operations including edge cases and invalid input                | Pending |
| Improve error handling                  | User-friendly messages and input validations (email format, phone, dates, cost, etc.) | Pending |
| Refactor code                           | Modularize, remove duplication, add comments                                          | Pending |
| Enhance CLI usability                   | Add `--help` command, usage examples, maybe interactive menu                          | Pending |
| Write detailed README                   | Include compilation instructions, CLI usage examples, file format description         | Pending |
| Prepare sample data files               | Provide example `users.txt` and `trips.txt`                                           | Pending |
| Final review and submission preparation | Check all files, push final commit                                                    | Pending |

---

If you want, I can also generate **starter code snippets** or **shell scripts** to automate some tests. Just ask!
