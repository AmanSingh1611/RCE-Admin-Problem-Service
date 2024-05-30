# Remote Code Executor Problem Setting service

This project provides a web-based platform for users to practice and solve problems using their preferred programming language. It acts as a remote code executor, allowing users to write, execute, and view the output of their code directly on the website.

--------------------------------------------------------------------------------------------

# High Level Design Of Project

![Remote-Code-Executer-Project (2)](https://github.com/AmanSingh1611/Final-Year-Major-Project/assets/78806052/138bbbbc-ef1e-4375-b98d-6dee5c0e2850)

--------------------------------------------------------------------------------------------

## How routing is working in the project

 - /api/v1/problems/ping
    - because the route starts with /api
        /api      -> /v1      -> /problems     -> /ping
        apiRouter -> v1Router -> problemRouter -> problemController -> service layer
