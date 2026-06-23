# Car Dealership Full‑Stack Application

**Repository:** `github.com/yourusername/car-dealership-fullstack`

**Project Name:** Cloud‑Native Car Dealership Application  

This project is the capstone for the IBM Skills Network **Full‑Stack Development** course. It combines a Django back‑end that serves REST APIs with a React front‑end that provides a modern user interface for browsing dealers, viewing car inventory, and posting reviews. The application is containerised, CI/CD‑enabled with GitHub Actions, and deployed on IBM Cloud Kubernetes Service.

---

## Features

- **Dealer Management** – List all dealers, filter by state, view dealer details.
- **Car Inventory** – Retrieve makes and models from the external Cloudant database.
- **User Authentication** – Register, login, and logout using JWT tokens.
- **Review System** – Submit reviews for dealers with sentiment analysis.
- **Responsive UI** – Built with React, Bootstrap, and custom CSS.
- **CI/CD Pipeline** – Automated testing, linting, and deployment via GitHub Actions.

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/car-dealership-fullstack.git
cd car-dealership-fullstack

# Start the Django server
cd server
docker compose up -d  # or python manage.py runserver

# Start the React front‑end
cd ../frontend
npm install
npm start
```

For full setup instructions, see the `docs/SETUP.md` file.