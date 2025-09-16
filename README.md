# Bored
💤 I’m Bored – Activity Suggestion App

A fun and interactive web app built with Node.js, Express, and EJS, powered by the Bored API.
Whenever you’re bored, this app suggests random activities or lets you filter activities by type and number of participants.

⸻

✨ Features

✅ Random Activity Generator – get a surprise activity every time you visit.
✅ Filter Options – choose activity type (e.g., Education, Recreational, Social, Music, DIY, etc.) and number of participants.
✅ Dynamic Results – activities are fetched live from the Bored API.
✅ Error Handling – user-friendly message when no matching activities are found.
✅ Responsive UI – clean form, activity cards, and error display.
✅ Server-side Rendering – built using EJS templates.

⸻

🛠️ Tech Stack
	•	Backend: Node.js, Express
	•	Templating: EJS
	•	API: Bored API (App Brewery endpoint)
	•	Styling: CSS (custom styles in /public/styles/main.css)
	•	HTTP Requests: Axios

⸻

🚀 How It Works
	1.	Homepage (GET /)
	•	Fetches a random activity from the API and displays it.
	2.	Form Submission (POST /)
	•	User selects type + participants.
	•	Fetches filtered activities from the API.
	•	Shows a random one from the matching results.
	3.	Error Handling
	•	If no activities match, displays:
"No activities that match your criteria."

⸻

📷 Demo Preview

(Here you can add screenshots of your website UI — form, activity card, error message, etc.)
