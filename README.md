# Cloud Resume Challenge – Frontend

## Overview

This is the frontend component of my [Cloud Resume Challenge](https://cloudresumechallenge.dev), a project designed to showcase practical cloud engineering skills using real-world technologies.

The site is built in HTML, CSS, and JavaScript, and is hosted on **Netlify** using a custom domain:  
🔗 **[rhysgoonan.com](https://www.rhysgoonan.com)**

The frontend connects to an Azure Function API that increments and displays a live visitor count using Cosmos DB as a backend store.

---

## Features

- Clean, responsive resume layout
- Hosted on Netlify with automated deployment
- Connected to a serverless API (Azure Function)
- Live visitor counter displayed via JavaScript
- Fully version-controlled through Git
- Deployed with CI/CD using GitHub Actions

---

## Technologies Used

- HTML5 / CSS3 / JavaScript
- Netlify (static site hosting + custom domain)
- GitHub Pages (fallback)
- GitHub Actions (frontend deployment automation)
- Azure Functions (API)
- Azure Cosmos DB Table API (data storage)

---

## Deployment

The frontend is deployed automatically to Netlify when changes are pushed to the `main` branch of this repository.

Netlify also manages:
- SSL certificate and HTTPS
- Custom domain routing for `rhysgoonan.com` and `www.rhysgoonan.com`

---

## Backend Integration

The frontend connects to an Azure Function App hosted at:

'https://crc-function-app.azurewebsites.net/api/VisitorCounter'


This API is called via JavaScript on page load to increment and display the current visitor count.

---

## Skills Demonstrated

- Static site development and optimisation
- Custom domain setup with Netlify
- CI/CD pipeline integration with GitHub Actions
- RESTful API consumption via JavaScript
- Serverless architecture integration (Azure Functions)
- Live data interaction from a static frontend

---

## Licence

This project is licensed under the [MIT Licence](LICENSE).
