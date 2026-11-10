SafeLoop 🛡️

Because Every Alert Deserves an Answer.

SafeLoop is an AI-assisted women's safety system designed to make emergency alerts harder to miss and easier to respond to.

Unlike systems that stop after sending an SOS notification, SafeLoop focuses on repeated alert escalation, response acknowledgement and safety monitoring.

Developed by Team Shakti for HERHACK 2026 – Artificial Intelligence Track.

---

🚨 The Problem

During an emergency, sending an alert does not guarantee that help will arrive.

- Emergency notifications can be missed.
- Trusted contacts may be busy, asleep or unavailable.
- Users may not have time to unlock their phones.
- A single SOS notification does not confirm that anyone has responded.

There is a need for a system that focuses not only on sending alerts but also on encouraging a timely response.

💡 Our Solution

SafeLoop introduces a persistent emergency alert mechanism.

Users can activate an SOS through a phone shake or a personal spoken code word while the application is open.

Once activated, the system shares the user's location and incident information with trusted contacts and a simulated emergency desk.

If nobody acknowledges the alert within the configured time, SafeLoop escalates notifications through available communication channels.

It also uses AI-assisted route anomaly detection to identify unusual travel patterns and prompt a safety check.

✨ Key Features

- Quick SOS Activation: Trigger an emergency alert through phone shake or a personal code word.
- Emergency Cancellation: A short cancellation window helps prevent accidental alerts.
- Live Location Sharing: Share the user's location with trusted contacts.
- Repeated Alert Escalation: Repeat alerts if nobody acknowledges the emergency.
- Response Acknowledgement: Display who has accepted responsibility for helping.
- Family Access Link: Allow trusted contacts to view emergency information without installing the application.
- AI-Assisted Safety Checks: Identify unusual travel patterns using anomaly detection.
- Emergency Dashboard: Display incoming alerts through a simulated emergency desk.

🧠 AI and Machine Learning

SafeLoop uses machine learning to support proactive safety checks.

Route Anomaly Detection: Isolation Forest identifies unusual patterns in travel trajectories, such as unexpected route deviations or unusually long stops.

Safety Check: When an unusual pattern is detected, the system prompts the user to confirm whether they are safe.

Speech Recognition: A spoken personal code word can activate an alert while the application is open.

An unusual route is treated as a reason to check in, not proof of danger.

🛠️ Technology Stack

Component| Technologies
Frontend| React.js, Vite, PWA
Maps| Leaflet, OpenStreetMap
Triggers| Browser Motion Sensors, Web Speech API, Web Audio API
Backend| Python, FastAPI
Real-time Communication| WebSockets
Database| PostgreSQL
Machine Learning| Scikit-learn, Isolation Forest
Scheduling| APScheduler
Alerts| Twilio (Trial), Web Push Notifications
Location & Police Data| Browser Geolocation API, Overpass API
Emergency Desk| Simulated Web Dashboard
Hosting| Vercel, Render

⚙️ How It Works

1. Setup: The user adds trusted emergency contacts and chooses a personal code word.
2. Monitoring: SafeLoop checks travel patterns for unusual changes.
3. Trigger: The user activates an SOS through a phone shake or spoken code word.
4. Cancellation: A short window allows the user to cancel an accidental alert.
5. Alert: Emergency information and location are shared with trusted contacts and the simulated emergency desk.
6. Escalation: If nobody acknowledges the alert within 60 seconds, the system repeats notifications.
7. Response: Contacts can acknowledge the alert, and the user can view the response status.

🔒 Privacy and Responsible AI

- Location sharing requires user permission.
- Voice input is used for code-word detection.
- SafeLoop does not save audio recordings.
- Browser-based speech recognition may use an online recognition service.
- Route anomalies trigger safety checks rather than automatic assumptions of danger.
- Emergency contacts receive information only as part of the authorised safety workflow.

📊 Project Status

SafeLoop is being developed as a hackathon prototype.

Prototype Scope:

- SOS activation and cancellation.
- Trusted-contact alerts.
- Location sharing and map interface.
- Repeated alert escalation.
- Response acknowledgement.
- Simulated emergency dashboard.
- Route anomaly detection.

Features will be marked as implemented only after they have been integrated and tested.

🚀 Future Scope

- Integration with authorised emergency response services.
- Improved route anomaly detection.
- More reliable background safety monitoring.
- Expanded voice-trigger capabilities.
- Improved emergency response coordination.

⚠️ Current Limitations

- The emergency desk is simulated and is not connected to actual police control rooms.
- Integration with India's 112 emergency response system is not currently available.
- Background monitoring and speech recognition depend on device and browser capabilities.
- Twilio trial services have usage restrictions.

👩‍💻 Team Shakti

Project: SafeLoop
Event: HERHACK 2026
Track: Artificial Intelligence

Team Member| Role
Shashi Bala| Team Leader
Shivani Garg| Team Member

---

Our Goal

No emergency alert should go unanswered. ❤️