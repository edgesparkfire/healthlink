# HealthLink — Comprehensive Health Management System

All code for the HealthLink project is consolidated in this folder. This project includes a Flask backend, an Admin Dashboard, and a Patient-facing Dashboard.

## 📂 Project Structure

- **`server.py`**: The SQLite-powered Flask backend API.
- **`healthlink.db`**: The SQLite database (auto-created on first run).
- **`index.html`**: The Admin Dashboard (Management UI).
- **`style.css`**: Shared styles for the Admin Dashboard.
- **`script.js`**: Logic and API integration for the Admin Dashboard.
- **`patient-dashboard.html`**: The Patient-facing Dashboard.
- **`patient-dashboard.css`**: Styles specific to the Patient Dashboard.
- **`patient-dashboard.js`**: Logic and API integration for the Patient Dashboard.

## 🚀 How to Run

1. **Start the Backend**:
   ```powershell
   python server.py
   ```
   The server will run at `http://localhost:5000`.

2. **Open the Dashboards**:
   - Open `index.html` in your browser to access the Admin view.
   - Open `patient-dashboard.html` in your browser for the Patient view.

## 🛠 Key Features
- **SQLite Database**: Persistent storage for patients, appointments, and vitals.
- **Real-time Statistics**: Dashboard summaries for pending/confirmed appointments and critical alerts.
- **Audit Logging**: Every action is tracked in the database for security.
- **Input Validation**: Server-side checks for blood pressure formats, patient IDs, and physiological ranges.
