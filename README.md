# Hospital_Shift_Management_System_n8n
This project is a fully automated Doctor Timetable Scheduling System built using n8n, Google Sheets, and Grok (xAI). It eliminates manual scheduling by converting  text messages into structured data and storing it automatically in Google Sheets.


## 🏗️ System Architecture

### Three Main Workflows:
1. **Weekly Scheduling** - AI-powered shift generation
2. **Availability Collection** - Form-based input system
3. **Cancellation Management** - Automatic replacement handling

### Database Structure:
- **Doctors Sheet**: Doctor master data
- **Availability Sheet**: Weekly availability records
- **Schedule Sheet**: Published weekly schedules

## ⚙️ Installation & Setup

### Prerequisites
- n8n instance (cloud or self-hosted)
- Google Sheets API access
- Gmail SMTP credentials
- Groq API key

### Quick Start
1. Import workflows into n8n
2. Configure Google Sheets credentials
3. Set up email service (Gmail)
4. Configure AI model credentials
5. Deploy and activate workflows

## 🔧 Configuration

### Required Credentials:
- Google Sheets OAuth2
- Gmail SMTP/OAuth2
- Groq API Key 

## Author
Muhammad Umair 
umair786uet@gmail.com
