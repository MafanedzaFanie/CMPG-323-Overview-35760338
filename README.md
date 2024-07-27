# CMPG-323-Overview-35760338
This repository will store all the information about the planned schedule of CMPG 323 module, the projects due dates and the time it took to complete all projects.

## List of repositories that will be created for each project
+ CMPG 323 Overview 35760338: Project 1 - Agile and Scrum Semester plan
+ CMPG 323 Project 2 - 35760338: API Development
+ CMPG 323 Project 3 - 35760338: Patterns and Standards
+ CMPG 323 Project 4 - 35760338: Testing and RPA
+ CMPG 323 Project 5 - 35760338: Reporting and Monitoring

## Branching Strategy to be used in each project

My projects follows a modified Git Flow branching strategy:

+ Project 1:For an Agile and Scrum project, the branching strategy will align with Agile methodologies' iterative and incremental nature. It should support frequent releases, continuous integration, and collaborative development.
+ Project 2: Implementing a Git Flow branching strategy in your API development project is beneficial for maintaining a clean and organized codebase. Additionally, it promotes collaboration and guarantees the stability and reliability of your releases. By adhering to these practices, you can efficiently manage your project's development and deployment processes.
+ Project 3:For a "Patterns and Standards" project, the branching strategy should support the development, review, and implementation of coding standards, architectural patterns, and best practices.
+ Project 4:An effective branching strategy is crucial for the "Testing and RPA" (Robotic Process Automation) project. It will facilitate the development, testing, and deployment of automation scripts and testing frameworks.
+ Project 5: For the "Reporting and Monitoring" project, a branching strategy should support the development, testing, and deployment of reporting tools, monitoring systems, and dashboards.

## The use of .gitignore file within each project

+ Project 1: Not reqired.
+ Project 2: The .gitignore file is a crucial tool for managing an API development project. It helps maintain a clean repository by excluding unnecessary files, enhances performance by reducing the size of the repository, and improves security by preventing the accidental commit of sensitive information.
+ Project 3: On Patterns and Standards, .gitignore is a tool that prevents automatically generated code from being committed, focuses on core artifacts, and manages project structure by ensuring consistency in ignored files and directories across projects involving patterns and standards.
+ Project 4:.gitignore is a tool used in testing and RPA projects to protect test data, ignore test results, and manage environment-specific files, ensuring a clean repository and protection of sensitive data.
+ Project 5: In Reporting and Monitoring projects, .gitignore is a tool used for ensuring data protection, managing temporary files, and keeping the repository clean by excluding unnecessary files to maintain a focused project structure.

## The storage of credentials and sensitive information

To protect your code and version control, avoid storing sensitive information directly. Instead, use environment variables, secure configuration files, and specialized services like HashiCorp Vault or AWS Secrets Manager. Avoid committing files containing sensitive information to version control systems. Key principles include granting only the necessary permissions, storing only essential data for application functionality, encrypting sensitive data at rest and in transit, and conducting regular security audits to identify and address potential vulnerabilities. This will help maintain security and prevent potential breaches.
