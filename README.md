# 🧠 AlgoArena – Coding Contest & Evaluation Platform

AlgoArena is a MERN-based coding contest platform designed for **college-level implementation**, enabling institutions to **track real-time coding performance** and ensure **academic integrity** during online contests. Built with a strong focus on **proctoring**, **fair evaluation**, and **detailed reporting**, AlgoArena provides students with a secure environment to demonstrate their coding skills.

---

## 🚀 Features

### 🧑‍💻 Secure Coding Contests

* Real-time coding environment similar to traditional coding platforms.
* Students cannot **switch windows** during contests.
* **Face detection** and **mobile detection** through the webcam.
* System gives:

  * ⚠️ 2 warnings for violations (e.g., phone detection, face absence).
  * ⛔ Auto-exit on the 3rd violation.

### 📊 Post-Contest Reports

* Detailed performance reports after every contest.
* Breakdown of:

  * Submissions
  * Test case pass/fail results
  * Code efficiency and time taken

### 🧪 Test Case Management

* Each problem includes **10 test cases**:

  * **3 Public Test Cases**: Visible to the user for debugging.
  * **7 Private Test Cases**: Hidden to prevent hard-coded solutions.

### ⚙️ Local Code Judging with Judge0

* Deployed **Judge0 locally** to avoid the high cost of Judge0’s public API.
* Secure, fast, and cost-efficient code execution and evaluation.

---

## 🌍 Live Demo  
🚀 **[Click here to visit the live site](https://algo-arena-lilac.vercel.app/)**

---

## 📷 Outcomes

<p align="center">
  <img src="https://i.postimg.cc/5jQ0JrBG/1.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/SnkNWNBF/2.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/N5h0jxb0/3.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/pmCVkMv9/4.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/gnv2X6BH/5.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/yJN1bp6L/6.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/Q99XXBT5/7.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/wtbq857g/8.png" width="600" />
</p>
<hr/>

<p align="center">
  <img src="https://i.postimg.cc/dkbJDq2f/9.png" width="600" />
</p>

---

## 🛠 Tech Stack

* **Frontend**: React.js
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Code Judging Engine**: Locally deployed [Judge0](https://github.com/judge0)
* **Proctoring Tools**: Face & object detection using Web APIs and ML models

---

## 🧑‍🏫 Target Audience

AlgoArena is built for **colleges and universities** that wish to:

* Conduct secure online coding contests.
* Track student behavior and performance.
* Prevent malpractice and ensure fair grading.

---

## 📦 Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/zohadurrjafri/AlgoArena.git
cd AlgoArena
```

2. **Install Backend Dependencies**

```bash
cd backend
npm install
npm run dev
```

3. **Install Frontend Dependencies**

```bash
cd frontend
npm install
npm start
```

4. **Setup Local Judge0 (Optional but Recommended)**
   Follow the [official Judge0 self-hosting guide](https://github.com/judge0/judge0) to run the judge locally.

---

## 🔍 How It Works

1. **Login/Register** as a student or admin.
2. **Start a contest** and solve coding problems.
3. **System monitors** webcam activity during the contest.
4. After submission, code is run against:

   * 3 Public Test Cases (shown to user)
   * 7 Private Test Cases (hidden)
5. **Admin Panel** shows reports for all participants post-contest.

---

## 🤝 Contributing

We welcome contributions!

1. Fork this repository.
2. Create a new branch: `feature/your-feature-name`
3. Commit your changes and push the branch.
4. Open a Pull Request.

---

## 📢 Future Enhancements

* Leaderboard with live rankings
* Admin panel with problem upload support
* Plagiarism detection integration
* Code editor improvements with IntelliSense support

---

## 📬 Contact

For any queries or suggestions, feel free to reach out via email or open an issue.

