<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00D9FF&center=true&vCenter=true&width=720&lines=Hey%2C+I'm+Sarvan+Singh+%F0%9F%91%8B;Backend+%26+Full-Stack+Developer;Concurrency%2C+Databases+%26+REST+APIs;Open+to+Internships+2027" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/sarvan-singh-6b3b27390/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:singhsarvan2006@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Sarvan-Singh7">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 👋 About Me

I'm **Sarvan Singh**, a Computer Science student at **Chitkara University** (batch of 2028). I like building backend systems where correctness matters, and I learn by building projects and testing them properly.

- 🔒 Currently building **ParallelLock**, a ticket-booking backend that never sells the same seat twice
- 🗄️ Interested in databases, transactions and concurrency
- 🌱 Open source contributor
- 💼 Open to **software engineering internships (2027)**

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,cpp,c,python,js,react,nodejs,express,postgres,mysql,mongodb,firebase,docker,git,github,linux,html,css,netlify,postman&perline=10"/>
</p>

---

## 🚀 Featured Projects

### 🎟️ ParallelLock: Concurrency-Safe Movie Ticket Booking System

**Stack:** `Node.js` • `Express` • `PostgreSQL` • `React` • `Docker`

Many users trying to book the same seat at the same moment is the classic booking problem. ParallelLock lets PostgreSQL decide: the requested seats are locked with `SELECT ... FOR UPDATE` inside one transaction, in a fixed order, so every request gets **all** of its seats or **none**, and deadlocks cannot happen.

- 🔐 JWT authentication, Argon2 password hashing, request validation and ownership checks
- ⏱️ Seat holds expire after 8 minutes; expired holds count as free inside queries, so no background job is needed
- 💳 Mock payment behind a Strategy and Factory interface, so new payment methods can be added
- 🧪 Concurrency tests: 500 simultaneous requests for one seat gave exactly one success, and 300 rounds of opposite-order requests gave no deadlocks
- ⚠️ A deliberately lock-free demo script reproduces the race condition the locking prevents

**Status:** Phase 1 is built. **Planned next:** idempotency keys, payment gateway integration in test mode, payment webhooks, and Redis for caching and rate limiting.

<p>
<a href="https://github.com/Sarvan-Singh7/ParallelLock">
<img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github"/>
</a>
</p>

---

### 🏥 College Dispensary Management System

**Stack:** `MERN` • `Docker` • `JWT` • `REST APIs` • `Nodemailer`

A team project that replaces paper prescriptions and manual scheduling with a role-based platform.

- 👥 3 portals (Admin, Staff, Student) with role-based access control
- 🔌 27 REST API endpoints and 7 data models
- 📅 Appointment management and medicine inventory
- 🔒 JWT authentication and OTP-based password reset

> **Note:** the live demo runs on a free plan, so the first load can take about a minute. The OTP email step may not work on it because free hosting blocks outbound email (it works locally).

<p>
<a href="https://github.com/Sarvan-Singh7/Dispensary-Management-MERN">
<img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github"/>
</a>
<a href="https://dispensary-frontend.onrender.com">
<img src="https://img.shields.io/badge/Live_Demo-46E3B7?style=for-the-badge&logo=render&logoColor=white"/>
</a>
</p>

---

### ⌨️ TypoNinja: Real-Time Typing Speed Analytics

**Stack:** `React` • `Firebase` • `Chart.js`

- ⚡ Live WPM and accuracy scoring
- 📈 Performance analytics and typing history
- 🔐 Authentication with Firebase
- 🛡️ Found and fixed a Firestore security rule flaw that allowed cross-user data access, and verified the fix in the Rules Playground

<p>
<a href="https://github.com/Sarvan-Singh7/React-Typing-App-TypoNinja-">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
</a>
<a href="https://typoninja7.netlify.app/">
<img src="https://img.shields.io/badge/Live_Demo-00C7B7?style=for-the-badge&logo=netlify"/>
</a>
</p>

---

### 🔗 Other work

- [Custom URL Shortener](https://github.com/Sarvan-Singh7/URL-SHORTENER): Node.js, Express and MongoDB, with cookie-based sessions

---

## 🤝 Open Source

**Open Source Diversity:** merged [Pull Request #183](https://github.com/opensourcediversity/opensourcediversity.org/pull/183), which fixed accessibility (a11y) issues by improving DOM structure and image attributes for screen readers.

---

## 🎯 Highlights

- 🧠 500+ data structures and algorithms problems solved, mostly in Java
- 🥉 4th place among 400+ participants in a college coding competition (Code2Chill, Chitkara University)
- 🏅 Nominated as Team Leader for Smart India Hackathon 2025
- 🐧 Completed Red Hat System Administration I and II courses

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sarvan-Singh7&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sarvan-Singh7&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>
</p>

---

<h3 align="center">⭐ Thanks for visiting! ⭐</h3>

<p align="center">
Building reliable software, learning continuously, and contributing to open source.
</p>
