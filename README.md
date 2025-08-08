# Job Recommendation System (Django Project)

##  Overview
This project is a *Job Recommendation System* built using *Django*, HTML, CSS, and JavaScript.  
It helps users *find jobs, **save them for later, **get personalized recommendations, and **set job alerts*.

---

##  Features

### 1️ Recommended Jobs
- Displays all available jobs from the database.
- Each job card has:
  - Title, skills, location, salary
  - *Save Job* button with JavaScript alert for confirmation
- Hover effects and modern UI for better user experience.

---

### 2️ Saved Jobs
- Shows jobs the user has saved from the recommended or personalized sections.
- Users can:
  - View saved jobs in a separate page
  - *Remove jobs* from saved list instantly

---

### 3️ Personalized Job Recommendations
- Lets the user *enter their skills* and *preferred location*.
- Matches jobs based on:
  - Skills (icontains search for partial matches)
  - Location
- Displays only jobs relevant to the user.
- *Save Job* button to quickly add to Saved Jobs list.

---

### 4️ Job Alerts
- User can *set a job alert* for specific skills & location.
- When jobs matching that criteria appear, they are shown in the alert results.
- JavaScript confirmation when alert is successfully set.

---

##  Tech Stack
- *Backend:* Django 5.2.4
- *Frontend:* HTML5, CSS3, JavaScript
- *Database:* SQLite3 (default Django database)
- *Styling:* Custom CSS with hover effects (and optional TailwindCSS support)
- *Templates:* Django Template Language (DTL)

---

## 📂 Project Structure
