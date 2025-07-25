### IPL Dashboard App

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/ipl-dashboard-output-v2.gif" alt="ipl dashboard output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

## 🚀 Features

- 📌 **Home Page with All Teams**  
  Displays IPL teams as stylish cards fetched from the API. Click any team to explore its recent matches.

- 🔄 **Dynamic Team Matches Route**  
  Loads match data using the team’s ID and navigates to `/team-matches/:id`.

- 🔍 **Loader Integration**  
  Displays a loader during every API call for enhanced user feedback.

- 🧠 **Latest & Recent Match Breakdown**  
  View detailed info of the latest match and summaries of recent matches, including:
  - Match status
  - Man of the match
  - Innings breakdown
  - Venue, date, and result
---

## 🛠️ Tech Stack

- **React.js**
- **React Router DOM**
- **JavaScript (ES6+)**
- **CSS Modules**
- **Loader Spinner (`react-loader-spinner`)**
- **Live REST APIs (CCBP IPL API)**

---

## 📦 Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/ipl-dashboard.git
cd ipl-dashboard

# 2. Install dependencies
npm install

# 3. Start development server
npm start
