


# 👋 Hello World!

<!--
To Do:
Experience not jumping
In tab no icon coming
Put proof of share market app's first commit
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experience Calculator</title>
</head>
<body>
    <h2><span id="experience-years">(Calculating...)</span></h2>

<script>
        document.addEventListener('DOMContentLoaded', function () {
            const startDate = new Date('March 1, 2023');
            const currentDate = new Date();
            const experienceInMs = currentDate - startDate;
            const experienceInYears = (experienceInMs / (1000 * 60 * 60 * 24 * 365)).toFixed(1);
            document.getElementById('experience-years').textContent = `(${experienceInYears} Yrs)`;
        });
</script>
</body>
</html>


I'm **Anurag Sindhu**, a passionate **Backend Engineer** from 🇮🇳 **India**, currently living in the vibrant city of **Bangalore**!

- 🔭 I’m currently working at **👕 [Tmrw](https://www.tmrw.in)** (Aditya Birla Group).
- 🌱 I'm deeply involved with **[NodeJs](https://cutshort.io/certificate/6659)**, **[Javascript](https://cutshort.io/certificate/6660)**, **TypeScript**, **MySQL**, **MongoDB**, **GCP**, **AWS**, **NestJs**, **Docker**, and **Jest**.
- 👔 Previously worked at **[Medibuddy](https://www.medibuddy.in)**, **[Falabella](https://falabellaindia.com)**, and **[In Time Tec](https://www.intimetec.com)**.
- 📬 You can reach me at `sindhuanurag2@gmail.com` or connect on [LinkedIn](https://www.linkedin.com/in/-anurag-sindhu) 📧.
- 📄 **[Here’s my Resume](https://drive.google.com/uc?export=download&id=15veI8jB30BhXydOVDlUMsF4OSrmszacZ)**, only a click away! 📝
- 🎯 Check my coding activity on **[Leetcode](https://leetcode.com/anurag-sindhu)** and **[Hackerrank](https://www.hackerrank.com/anurag_sindhu)**! 💻

---

## 🛠️ **Languages & Tools**

### **🛠️ Core Technologies**
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS">
</p>

### **🗄️ Databases**
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
</p>

### **☁️ Cloud & DevOps**
<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900" alt="AWS">
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## Experience
<details>
<summary><b>👕 Tmrw (Aditya Birla Group)</b> - SDE-3 | Mar 2023 - Present</summary>

🔥 **Key Achievements**  
- 🗂️ Migrated **1.7** Crore User Data **(100 GB)** to **MariaDB** from **MySQL DB** via **LOAD DATA INFILE** with minimal downtime (< 10 minutes ⏲️).
- Engineered a **𝐁𝐥𝐨𝐨𝐦 𝐅𝐢𝐥𝐭𝐞𝐫𝐬** DSA to check user presence (**𝟏 𝐜𝐫𝐨𝐫𝐞** * **𝟐𝟎 𝐡𝐚𝐬𝐡** functions), optimizing for constant time complexity with a **𝟐𝟓 𝐌𝐁** memory trade-off, ensuring scalability for **𝟏𝟎-𝟏𝟓** years with 𝟐𝟎% growth.
- Integrated OTP sharing and login in under 𝟭 𝘀𝗲𝗰𝗼𝗻𝗱 via caching and Pub-Sub, achieving scalability to 𝟭 𝗠𝗶𝗹𝗹𝗶𝗼𝗻 TPS with 𝗽𝟵𝟵 latency.
-  **𝐁𝐮𝐢𝐥𝐝𝐢𝐧𝐠** a solution to display **𝐮𝐧𝐢𝐪𝐮𝐞** active users with **𝑯𝒚𝒑𝒆𝒓𝑳𝒐𝒈𝑳𝒐𝒈** DSA, using **𝘄𝗿𝗶𝘁𝗲-𝗯𝗲𝗵𝗶𝗻𝗱** caching to reduce latency.
- 🚀 Spearheaded the successful **MERN (From Rails) stack and MSA transition** at **Bewakoof.com** [Tmrw Acquisition], resulting in a remarkable **30% improvement** in scalability 📈, enhanced multi-tenancy capabilities, and a **25% increase** in overall system stability ⚖️.
- 🔑 Headed **OAuth** and **My Account**, implementing real-time user migration with **99% success**. Integrated OTP sharing and login in <1 second using **Redis**.
- 🛠️ Designed, structured, and deployed multiple **microservices** with **gRPC** and **Pub-Sub** communication, integrated with **Amazon SQS**. Achieved scalability up to **million TPS** with **p99 latency**.
- 🔥 Collaborated on **𝗡𝗘𝗦𝗧** Setup, integrated discount% functionalities, price changes, cart synchronization, and ratings/reviews for a seamless user experience🤝, while also owning and enhancing custom product features.
- ✅ Headed the **𝗮𝘂𝘁𝗵-𝗮𝘂𝘁𝗵𝘇** with session, my-account📒 along with implementing real-time user migration having a 𝟵𝟵% success rate
- ⚖ Oversaw cart synchronization between back-end systems, **F𝗮𝘂𝗹𝘁-T𝗼𝗹𝗲𝗿𝗮𝗻𝘁** enhancing user🤵🏻 experience and ensuring **serviceability**
- 🌈 Upgraded customer-related API calls to **𝗚𝗿𝗮𝗽𝗵𝗤𝗟** for high performance⚡️. Rerouted Shopify calls through a separate app for optimized resource utilization♻️
- 🚦Created templates for High-Level Design (**𝗛𝗟𝗗**) and Low-Level Design (**𝗟𝗟𝗗**) documentation to ensure standardized format
- 🔥 Headed OAuth and My Account, implementing real-time user migration with **𝟗𝟗%** success. Integrated OTP sharing and login in **<𝟏 second** using Redis.
- 📝 Integrated **ESLint**, **Husky** for code consistency, **Pino Logging** library, and robust error ❗ handling for asynchronous calls ↪, reducing errors by **35%**.  

🛠️ **Tech Stack**: Node.js, gRPC, Redis, GraphQL, AWS SQS  
</details>

<details>
<summary><b>👕 Medibuddy</b> - SDE-3 | Oct 2022 - Jan 2023</summary>

🔥 **Key Achievements**  
- 🛡️ Injected request validation to prevent SQL injection and enhance the system's security 🔐 and reliability.
- 📒 Replaced **𝐀𝐩𝐚𝐜𝐡𝐞 𝐙𝐨𝐨𝐤𝐞𝐞𝐩𝐞𝐫** with **𝐆𝐨𝐬𝐬𝐢𝐩 𝐏𝐫𝐨𝐭𝐨𝐜𝐨𝐥** for SMS, enhancing reliability, **𝐭𝐡𝐫𝐨𝐮𝐠𝐡𝐩𝐮𝐭**, and latency.
- ⚡ Achieved a **90% performance boost** in **Medibuddy Surgery's** inventory tool by refactoring **MySQL** queries for large-scale data control.
- 🍏 Improved the inventory tool of MediBuddy Surgery 💊 performance by **𝟵𝟬%**🎉 by refactoring **𝗠𝘆𝗦𝗤𝗟** queries.
- 🍔 Streamlined maternity👩‍🍼 appointment📆 reminders🎗️ by designing a system 💾 that sends What'sApp notifications, eliminating the need for **manual reminders**🎗️
- 🌐 Engineered a distributed system for efficient data synchronization in **Elasticsearch**, slashing manual intervention by **93%**. The upgraded system is now highly reliable, consistently performs, and noiselessly zips along, directly benefiting customers.
- 🔍 Corrected the map coordinates algorithm for each address by implementing an efficient zoom-in 🔎 approach.
- 💰 Reduced **Google Maps API** cost by **70%** by stitching a cache mechanism storage to avoid duplicate calls for large scaling.

🛠️ **Tech Stack**: Node.js, gRPC, Redis, GraphQL, AWS SQS  
</details>

<details>
<summary><b>👕 Falabella</b> - Senior Software Engineer | Dec 2019 - Sep 2022</summary>

🔥 **Key Achievements**  
- 🔧 Proprietorship of **Geo Data** and **Notification services**, which led to **>95% availability**.
- 🇦🇺 Led the full lifecycle🔄 development of My Account service, streamlining other services of my-account for enhanced user convenience. 1,5,10,25,50,75 to 𝟭𝟬𝟬% **conversion**.
- 👜 Designed and developed💻 springverify architecture from scratch. Exposed low latency, high volume, high availability, and performance **𝗥𝗘𝗦𝗧** API for mobile📱 and web 💻 apps.
- 🥇 Reduce latency by **𝟱𝟬%** with elevated coding, polished time complexity, pre-fetching data, algorithm enhancements🧹, leveraging problem-solving skills, new concepts, and achieving 𝟭𝟬𝟬% **𝘁𝗲𝘀𝘁 𝗰𝗼𝘃𝗲𝗿𝗮𝗴𝗲**💯 in unit, integration, and API testing.
- 🚀 Caching, revamped queries, eliminated redundant API calls, reducing API reply time from **850 ms to 510 ms**, enhancing performance.
- 📚 Streamlined onboarding using tools like **Postman**, **KT videos**, and **Swagger**, achieving a **20% reduction** in team integration time.
- 📊 Elevated code structure and implemented a prefetching algorithm, which reduced latency by **50%** and improved data retrieval efficiency ⏱️ by **30%**. Achieved **100% unit**, **integration**, and **API test coverage** for enhanced software stability 🧹.
- 💳 Integrated **Razorpay** for a **20% efficiency boost** in transaction processing, ensuring seamless and secure transactions.
- 🔄 Improved architecture for better throughput, responsiveness, reduced database costs, and sharpened CPU efficiency. Migrated frontend dependencies to the backend, fine-tuning database queries for significant performance gains and less transparency.
- 🤝 Partnered with vendors (e.g., **Flipkart**, **Razorpay**) to integrate **springverify API**.

🛠️ **Tech Stack**: Node.js, gRPC, Redis, GraphQL, AWS SQS  
</details>

<details>
<summary><b>👕 In Time Tec</b> - Software Engineer | Feb 2018 - Dec 2019</summary>

🔥 **Key Achievements**  
- 📚 Completed a professional development program "Learn and Code" focused on learning and coding! Acquired proficiency in valuable insights into the power of maintaining ⚙️ clean code in a productive environment.
- 🌱 Tackled a "Learn and Grow" 🌱 program focused on personal development, emphasizing both fostering 🪴 strong relationships and supervising time effectively.
- 🚀 Kicked off my journey toward proficiency in **JavaScript (JS)**, **TypeScript (TS)**, **Node.js**, **MySQL**, and **MongoDB**. Actively participated in a project where I authored API test coverages, successfully achieving **100% coverage** throughout my training! ☂️

🛠️ **Tech Stack**: Node.js, gRPC, Redis, GraphQL, AWS SQS  
</details>
  
## Personal Projects
  - [Stock Market App](#stock-market-app)

...


### 🌟 **Tech Skills**

| Technology        | Proficiency |
|-------------------|-------------|
| **JavaScript**    | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **NodeJs**        | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **TypeScript**    | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **MySQL**         | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **MongoDB**       | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **Express**       | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **Data Structures**| ⭐ ⭐ ⭐ ⭐ ⭐     |
| **Algorithms**    | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **Git**           | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **Testing**       | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **System Design** | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **JSON**          | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **REST**          | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **SQS**           | ⭐ ⭐ ⭐ ⭐ ⭐      |
| **Docker**        | ⭐ ⭐ ⭐ ★ ★      |

---

## 💼 **Personal Projects In Detail**

## [🚀 Stock Market App: A Passion Project Turned Profit Machine 💸](#stock-market-app)

- **🔥 Built a Killer Stock Market App**: Fueled by my passion for the markets, I created a custom Node.js application to dominate the game. 💪
- **📈 32% CAGR in 4 Years**: My app's performance speaks for itself, crushing the market average even after a shaky start (0% profit in the first 2 years!) 📉→📊.
- **🎯 Zerodha Master**: Leveraged the Zerodha platform to execute trades seamlessly – buy, track, sell, like a boss 🏹.
- **💻 Tech Stack to Make You Drool**: **MongoDB**, **MySQL**, **Redis**, **Node.js**, **React.js**, **AWS** – a symphony of powerful technologies 🎶.
- **🖋️ 23,000 Lines of Code**: Pure dedication and craftsmanship poured into this masterpiece 🎨.
- **⏳ Time Investment? Worth Every Second**: 4 years of continuous improvement to make this app sing 🎤.
- **💸 Profit Party**: Regularly exceeding **30% returns** in under a month* – this app is a money-making machine on autopilot! 🤑.
- **🤖 Automation Mastermind**: My portfolio runs on autopilot, freeing me up – currently requiring only **1 hour of work per week**! ⏱️.
- **📊 Market Maestro**: My app captures the perfect **timing (moment, price, quantity)** for every trade 🎯.
- **💼 Managing a Portfolio Empire**: Currently managing a staggering **3 portfolios**, and expanding! 🌍 **Pyramid Strategy**.

### **⚙️ Features**:

- **🕒 Daily Market Schedule**: The app starts working **daily when the market opens** and goes to sleep when the **market closes**, automating all tasks from buy orders to sell triggers.

#### **💡 Systematic Buy on Dips Investment Plan**:
- The app smartly creates **Trigger/GTT** setups, leveraging a strategy to buy shares on dips.
  - **📉 Dynamic Dip Percentage**: Automatically calculates a **custom dip percentage** for each share based on several factors, ensuring precision in decision-making.
  - **🧠 Intelligent Trigger/GTT Creation**:
    1. **Create Trigger/GTT** if any **new holding** enters the portfolio.
    2. **Deletes all local and remote GTTs/Targets** if the holding is no longer found, ensuring no unwanted triggers.
  - **🔄 Maintain Trigger Price Gap**: The app ensures that there is always a set **gap between the current price and the configured Trigger/GTT price** for each share, optimizing entry points.
  - **📦 Quantity Configuration**: Users can define **quantities** for each trade, and the app will execute accordingly.
  - **🔺 Auto-Quantity Increase**: Once a Trigger/GTT is hit, the app automatically **increases the number of shares** for the next trigger, following your strategy to maximize gains.

#### **💼 Target/Sell Feature**:
- **💰 Selling is as Important as Buying**: The app provides dynamic options for selling shares at the right moment. Users can specify **how much percentage** they wish to sell after the price reaches a certain threshold.
  - **⏳ Daily Sell Trigger Creation**: Every day, the app creates a **sell order/Trigger** with the user-defined sell percentage or the system’s **pre-defined percentage**, whichever is earlier.
    - **System’s Pre-defined Percentage** is calculated based on the stock price:
      - For a stock priced at ₹100, the pre-defined percentage would be around 13%.
      - For a stock priced at ₹500, it would be around 12%, and so on.
    - The idea is to catch sudden upward jumps in the stock price, book profits, or buy later to convert it into **Intraday** or **Sell Today Buy Tomorrow (STBT)**.
  - **📈 Selective Selling**: The user can **choose specific shares** that are up for sale, and the above actions will be applied only to the selected shares.
  - **📝 Personal Notes**: Users can **add personal notes** to track when and why they intend to sell particular shares, ensuring they never miss their planned exit strategy.
  - **🔍 Handles Sell Precision**:
    - If the **target percentage** is just **0.5% away** from the current market price, the app evaluates whether to proceed with the sell order.
    - If **no target percentage** is given, the system uses the pre-defined strategy to ensure timely exits based on market conditions.

### **📊 Movements/Tracker Feature**:
Keep a close eye on your favorite stocks with real-time tracking and alerts:

- **👀 Keep an Eye on Any Share**: The app allows you to **monitor any stock** and keep track of its movements.
- **📅 Track Share Movements**: Get a comprehensive movement status for a share over the last **n number of days (up to 150 days)**, helping you make better investment decisions.
- **🔔 Set an Alert Price**: Configure an **alert price** for any stock, and you'll receive a **WhatsApp alert** when the price is hit 📲.
- **📈 Alert Percentage**: Set a specific **percentage** increase/decrease to be monitored, and receive a **WhatsApp alert** when the stock matches your target percentage.
- **📝 Create Notes for Each Share**: Stay organized by adding **personal notes** for each stock, helping you remember important details or strategies.
- **🗑️ Remove Shares Anytime**: You can **remove any share** from your watchlist at any time with ease 🗑️.

### **📜 Investment Principles**:
The app follows a few golden principles to ensure disciplined and strategic investment:

1. **Buy when everyone else is selling and hold until everyone else is buying** – by Warren Buffet. 🦈
2. **Buy only those shares whose fundamentals and charts are very strong** (limited to **Nifty 50** and **Nifty Next 50** stocks). 📊

### **🔮 The Future is Bright**:
- **🌐 Multi-Broker Domination**: World domination? Maybe not. But integrating with other brokers is definitely on the horizon 🌟.
- **🎒 Strategy Arsenal Ever-Expanding**: My bag of tricks keeps growing, ensuring even greater returns in the future 📚.

### **💻 Code Links:**
- Backend Code (Market Explore): [GitHub Repository](https://github.com/anurag-sindhu/market_explore) 🔗
- Frontend Code (Market Explore UI): [GitHub Repository](https://github.com/anurag-sindhu/market_explore_ui) 🔗

**Note**: The code is private and will remain that way forever 🔒.

### **🖼️ Project UI**:
- ![UI Image 1](/AD_4nXeW0QiFNa0Iw500psL0jtZk97meXniVWxZcNAFSsvn9yuiAV8kv4IgrWOU7qr33LzxYfgWuLsJRd7ihovlubFb3puv1x4P_aGw-zbWmPxZXTooWFfGCDRw9.jpg)
- ![UI Image 2](/AD_4nXeqHATatTXFkI_-RyNf2Gu1bx9jprFYK5dsq3baU01c1Bhok7VD0B2Eonpr0GHxDW0lew6bTyXjK4vb2yDd2q316OniCmSs0V1caLuDTSDlHpsqeyGi9f4c.jpg)
- ![UI Image 3](/AD_4nXeqHATatTXFkI_-RyNf2Gu1bx9jprFYK5dsq3baU01c1Bhok7VD0B2Eonpr0GHxDW0lew6bTyXjK4vb2yDd2q316OniCmSs0V1caLuDTSDlHpsqeyGi9f4c.jpg)

---

Ready to unleash the power of code and automation in your investment journey? **[Let’s talk!](mailto:sindhuanurag2@gmail.com)** 📧.

---

<!-- ### **🛠️ [Add Your Next Project Here]**
This section is ready for you to add more projects in the future. Use the same structure to showcase your awesome work!


--- -->


## 📊 **GitHub Stats**

<a href="https://github.com/anurag-sindhu/anurag-sindhu">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anurag-sindhu&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21&langs_count=5" alt="Anurag's Most Used Languages" />
</a>
<a href="https://github.com/anurag-sindhu/anurag-sindhu">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=anurag-sindhu&show_icons=true&line_height=40&count_private=true&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" alt="Anurag's GitHub Stats" />
</a>

---

## 🔗 **Connect with Me**
<p align="left">
  <a href="https://www.linkedin.com/in/-anurag-sindhu" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="Anurag LinkedIn" height="30" width="40" />
  </a>
</p>

---

🚀 **Let’s build something amazing together!**
