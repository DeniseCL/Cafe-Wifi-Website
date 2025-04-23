# ☕ Cafe Wi-Fi Finder

A small Flask web app to find and submit cafes with good Wi-Fi, power outlets, and coffee quality — perfect for remote work and studying.

## 🚀 Features

- Add new cafes with details like:
  - Google Maps link
  - Opening/Closing hours
  - Coffee, Wi-Fi, and Power ratings
- View a list of all submitted cafes in a clean, styled table
- Password-protected access to the "Add Cafe" page

## 🛠 Built With

- Python & Flask
- WTForms + Flask-WTF
- Bootstrap 5 (CDN)
- CSV-based data storage

## 🔐 Access Control

To prevent public submissions, the `/add` route is protected by a simple password check. You must enter a secret key to submit new cafes.

## 📁 Project Setup

1. Create a virtual environment and activate it:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
