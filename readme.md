<p align="center">
    <h1 align="center">Phone Book 📞</h1>
</p>

<p align="center">
	<img src="https://img.shields.io/github/license/AlecDr/Phone-Book?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/AlecDr/Phone-Book?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/AlecDr/Phone-Book?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/AlecDr/Phone-Book?style=flat&color=0080ff" alt="repo-language-count">
</p>

<br>

##### 🔗 Table of Contents

- [📍 Overview](#-overview)
- [👾 Features](#-features)
- [🎨 Design Patterns](#-design-patterns)
- [📂 Repository Structure](#-repository-structure)
- [🧩 Modules](#-modules)
- [🚀 Getting Started](#-getting-started)
    - [🔖 Prerequisites](#-prerequisites)
    - [📦 Installation](#-installation)
    - [🤖 Usage](#-usage)
    - [🧪 Tests](#-tests)
- [📌 Project Roadmap](#-project-roadmap)
- [🤝 Contributing](#-contributing)
- [🎗 License](#-license)
- [🙌 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

The Phone Book application is a simple console app built using .NET with Entity Framework (Code-First Approach) that allows users to manage contact information (add, delete, update, and read contacts). The app interacts with a SQL Server database and performs operations such as input validation, ensuring that contacts are stored correctly.

---

## 👾 Features

- **Add Contact**:
  Users can add new contacts with fields such as Name, Email, and Phone Number, ensuring proper validation.

- **Update Contact**:
  Modify existing contact information, ensuring data integrity and valid input formats.

- **Delete Contact**:
  Delete existing contacts from the database.

- **List Contacts**:
  Retrieve and display all stored contacts.

- **Email & Phone Validation**:
  Ensures that emails follow standard formats and phone numbers are properly formatted.

- **Entity Framework Integration**:
  Utilizes EF’s Code-First approach for database schema creation and interaction with SQL Server.

- **Categories**:
  Contacts are categorized into groups like Family, Friends, and Work.

- **Unit Testing**:
  The service and repository layers are tested with unit tests. Database calls will be mocked to simulate different scenarios.

---

## 🎨 Design Patterns 

TODO

---

## 📂 Repository Structure

TODO

---

## 🧩 Modules

TODO

---

## 🚀 Getting Started

### 🔖 Prerequisites

**CSharp**: `version 8.0`
**Microsoft SQL Server**: `version 16.0.0`

### 📦 Installation

Build the project from source:

1. Clone the Phone Book repository:
```sh
❯ git clone https://github.com/AlecDr/Phone-Book
```

2. Navigate to the project directory:
```sh
❯ cd Phone Book
```

3. Install the required dependencies:
```sh
❯ dotnet build
```

### 🤖 Usage

To run the project, execute the following command:

```sh
❯ dotnet run
```

### 🧪 Tests

Execute the test suite using the following command:

```sh
❯ dotnet test
```

---

## 📌 Project Roadmap

- [ ] **`Task 1`**: Implement a basic contact class with properties like `Id`, `Name`, `Email`, and `PhoneNumber`.
- [ ] **`Task 2`**: Set up Entity Framework using the Code-First approach and SQL Server for database integration.
- [ ] **`Task 3`**: Implement `Create` operation to add new contacts to the database.
- [ ] **`Task 4`**: Implement `Read` operation to retrieve contacts from the database.
- [ ] **`Task 5`**: Implement `Update` operation to modify existing contact details in the database.
- [ ] **`Task 6`**: Implement `Delete` operation to remove contacts from the database.
- [ ] **`Task 7`**: Add validation for `Email` and `PhoneNumber` to ensure valid formats before saving to the database.
- [ ] **`Task 8`**: Implement user-friendly error messages when validation fails.
- [ ] **`Task 9`**: Create functionality to categorize contacts (Family, Friends, Work, etc.).
- [ ] **`Task 10`**: Add the ability to send emails to contacts directly from the application.
- [ ] **`Task 11`**: Implement SMS sending functionality for contacts.
- [ ] **`Task 12`**: Write unit tests for the repository and service layers.
- [ ] **`Task 13`**: Implement exception handling for database operations and network failures.

---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/AlecDr/Phone-Book/issues)**: Submit bugs found or log feature requests for the `Phone-Book` project.
- **[Submit Pull Requests](https://github.com/AlecDr/Phone-Book/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/AlecDr/Phone-Book/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/AlecDr/Phone-Book
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/AlecDr/Phone-Book/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=AlecDr/Phone-Book">
   </a>
</p>
</details>

---

## 🎗 License

This project is protected under the [MIT](https://choosealicense.com/licenses/mit/) License. For more details, refer to the [LICENSE](https://github.com/AlecDr/FlashCards/blob/master/LICENSE.txt) file.

---

## 🙌 Acknowledgments

- Idea taken from [C# Academy](https://www.thecsharpacademy.com/), nice location to learn C#.

---