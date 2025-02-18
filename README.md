# Tax Calculator

## Live Demo

The project is live and can be accessed here:
[**Visit Tax Calculator**](https://overtaxedonline.com)  

---

A **Tax Calculator** built with Django to help users calculate and manage their taxes efficiently. This project is designed to make determining tax obligations simple.
* The state calculator works only for the state of Maryland so far.
---

## Features

- **Customizable Federal and State Tax Calculations**: Allows users to calculate taxes based on income and other parameters.
- **Dynamic Tax Rates**: Support for dynamic tax rates to accommodate different scenarios.
- **User Input**: Accepts relevant inputs such as income, expenses, and tax credits.
- **Summary Reports**: Displays breakdown of taxable amounts, deductions, and final taxes owed.
- **Extensible**: Easily customizable for specific tax rules or user requirements.

---
## Screenshots
![OverTaxed Home](src/static/graphics/home_preview.png)
![Federal Calculator Preview](src/static/graphics/federal_preview.png)
---
## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTMX + Tailwind CSS + DaisyUI for dynamic, lightweight interactions.
- **Database**: PostgreSQL.
- **Deployment**: Hosted on a digital ocean droplet with docker and [**caddy**](https://caddyserver.com/) (URL above).

---

## Roadmap
- [ ] Add support calculating estimated payments for self-employed users.
- [ ] Allow users to save tax estimations.
- [ ] User authentication for personalized estimation management.

---

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---
