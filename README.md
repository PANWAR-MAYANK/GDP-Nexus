# 🌍 GDP Dashboard - Streamlit Web App

An interactive and visually appealing web dashboard that allows users to explore and analyze GDP data of countries across different years. This project demonstrates the integration of data visualization, frontend interaction with Streamlit, and DevOps practices like containerization, CI/CD, and automated deployment.

---

## 📌 Features

- 📊 Interactive GDP line chart over the selected years
- 🌐 Multi-country selection support using country codes
- 📅 Year range filtering with dynamic slider
- 📈 GDP growth metric cards for selected countries
- 💾 Data sourced from World Bank Open Data
- 🚀 DevOps-enabled with Docker + CI/CD support

---

## 🖼️ Demo

Try it live (if deployed): [https://gdp-nexus.streamlit.app](https://gdp-nexus.streamlit.app)

![GDP Dashboard Screenshot](assets/demo.png)

---

## 🧰 Tech Stack

- Python 3.13
- Streamlit (for frontend UI)
- Pandas (for data handling)
- Docker (for containerization)
- Git & GitHub (for version control)
- GitHub Actions / CI pipeline (for automation)
- Streamlit Cloud (for deployment)

---
## 🚦 How It Works

The frontend of the app is powered by Streamlit. Here's how it flows:

1. 🎯 User selects a year range using the slider.
2. 🌐 User selects one or more countries from the dropdown.
3. 📉 A line chart shows GDP trends for selected countries across the chosen years.
4. 📈 Metric cards display the GDP values in billions and show growth (e.g., 2.3x).
5. 🧠 Data is read from a local CSV, reshaped using pandas melt, and cached using @st.cache_data for performance.

---

## ⚙️ DevOps Integration

✔️ Version Control:
- Project is tracked via GitHub or GitLab.

✔️ Containerization:
- Dockerfile included to ensure environment reproducibility.

✔️ CI/CD:
- GitHub Actions (example below) to auto-deploy app or test on every push.

✔️ Deployment:
- Easily deployable to Streamlit Cloud, Heroku, or cloud platforms using Docker.

---
