# 🏙️ CivicSense AI

A smart city web platform that empowers citizens to report civic issues, engage with city services, and track the resolution of community problems — all powered by an AI assistant.

---

## 📌 Overview

CivicSense AI is a full-stack web application built with **Flask** and **HTML/CSS/JavaScript** that bridges the gap between citizens and city administration. Users can register, report local issues (potholes, broken streetlights, waste management, etc.), track submission status, and interact with an AI-powered assistant for guidance. Admins get a dedicated dashboard to manage users, view analytics, and respond to reports.

---

## ✨ Features

### 👤 Citizen Portal
- **Register & Login** — Secure user authentication with bcrypt password hashing
- **Report an Issue** — Submit civic complaints with descriptions and supporting details
- **My Submissions** — Track the status of all reported issues
- **AI Assistant (CivicSense AI)** — Chat with a Gemini-powered assistant for help navigating city services
- **Feedback** — Submit feedback about the platform
- **Help & Support** — Access guidance and FAQs
- **My Profile** — Manage personal account details

### 🛠️ Admin Portal
- **Admin Login** — Separate secure admin authentication
- **Admin Dashboard** — Overview of all reports and platform activity
- **User Management** — View and manage registered citizens
- **Issue Reports** — Browse, filter, and update civic issue submissions
- **Analytics** — Visual insights into issue trends and resolution rates
- **User Feedbacks** — Review citizen feedback
- **Manage About Us** — Update platform information
- **Admin Profile** — Manage admin account

### 🤖 AI Assistant
- Powered by **Google Gemini** (`google-generativeai`)
- Guides users through reporting civic issues
- Answers questions about city services and departments
- Falls back to general assistant mode for off-topic questions

---

## 🗂️ Project Structure

```
subbaReddy/
├── Main.html                   # Landing / home page
├── login.html                  # Citizen login
├── register.html               # Citizen registration
├── dashboard.html              # Citizen dashboard
├── report-issue.html           # Issue submission form
├── my-submissions.html         # User's submitted issues
├── my-profile.html             # User profile page
├── analytics.html              # Citizen-facing analytics
├── feedback.html               # Feedback submission
├── help-support.html           # Help & support page
├── admin_login.html            # Admin login
├── admin_dashboard.html        # Admin control panel
├── admin_analytics_page.html   # Admin analytics
├── admin_profile.html          # Admin profile
├── issue_reports.html          # Admin issue management
├── report_view.html            # Detailed report view
├── manage_about_us.html        # Manage platform info
├── user_management.html        # Admin user management
├── user_feedbacks.html         # Admin feedback viewer
├── female_avatar.png           # Default user avatar
├── AI_Prompt.txt               # System prompt for AI assistant
├── app.log                     # Application logs
└── requirements.txt            # Python dependencies
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| Frontend | HTML, CSS, JavaScript |
| Database | MySQL (`mysql-connector-python`) |
| Authentication | bcrypt |
| AI Assistant | Google Gemini (`google-generativeai`) |
| Image Handling | Pillow |
| QR Codes | qrcode |
| PDF Generation | reportlab |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- MySQL Server

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/subbareddychilaka/subbaReddy.git
   cd subbaReddy
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the database**
   - Create a MySQL database for the project
   - Update your Flask app's database connection settings with your MySQL credentials

4. **Set up the Gemini API key**
   - Obtain an API key from [Google AI Studio](https://aistudio.google.com/)
   - Set it as an environment variable or in your app configuration:
     ```bash
     export GEMINI_API_KEY=your_api_key_here
     ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. Open your browser and navigate to `http://localhost:5000`

---

## 📦 Dependencies

```
Flask
mysql-connector-python
bcrypt
Pillow
google-generativeai
qrcode
reportlab
```

Install all at once:
```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source. Add a license file to specify usage terms.

---

## 👨‍💻 Author

**Subba Reddy Chilaka**
- GitHub: [@subbareddychilaka](https://github.com/subbareddychilaka)
