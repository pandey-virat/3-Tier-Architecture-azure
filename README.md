# 3-Tier Architecture Implementation on Azure

This repository presents the implementation of a 3-Tier Application Architecture on Microsoft Azure as part of my internship project at **Celebal Technologies**.

## 👨‍💻 Project Overview

This architecture consists of three logical tiers:

- **Web Tier**: A Windows IIS Server hosting an HTML page with a button to trigger the backend API.
- **App Tier**: A backend API developed using ASP.NET Core that handles the requests and logs them.
- **DB Tier**: A Microsoft SQL Server instance used to store data passed from the API.

Each tier is isolated in its own Virtual Network with strict NSG rules. Only required access was allowed as per project constraints.

## 📂 Submission Content

I have attached the following documents as part of this project:

- **Final Project Report (Word)**
- **Final Project Report (PDF)**

These documents contain the complete architecture explanation, step-by-step configuration details, screenshots, code snippets, and project justification.

## 🙋‍♂️ Author

**Virat Pandey**  
Intern @ Celebal Technologies

## 🔗 References

- [Microsoft Azure](https://portal.azure.com/)
- [Microsoft SQL Server Documentation](https://learn.microsoft.com/en-us/sql/)
- [ASP.NET Core Docs](https://learn.microsoft.com/en-us/aspnet/core/)
- [ChatGPT (Project Assistance)](https://chat.openai.com)
