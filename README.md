# Multi-App Docker Stack

![Project Diagram](https://jcadima.dev/posts/main-domain-subdomain.png)

A lightweight Docker Compose setup for running multiple PHP/Laravel applications with shared Nginx and isolated MySQL databases.  
This environment is designed for local development and makes it easy to manage multiple projects in one stack.

## Features
- 🚀 Multiple Laravel/PHP apps (`main`, `subdomain1`, `subdomain2`, `subdomain3`)  
- 🌐 Shared Nginx reverse proxy for subdomains  
- 🗄️ Separate MySQL databases for each app  
- ⚡ Queue worker support for background jobs  
- 🔄 Auto-restart and persistent volumes  

Fevelopers who want a simple, reproducible local dev environment for multi-app projects.