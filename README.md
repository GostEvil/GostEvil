## Hi, I'm Nuno 👋
Computer engineering student at UPB (Polytechnic University of Bragança), Portugal, graduating in July 2027. Erasmus at Cracow University of Technology, Kraków, Poland, in 2026.

I build backends and infrastructure, and most of what I build ends up running on servers I set up and secure myself. I'm focused on cybersecurity and applied AI: honeypots and log analysis on one side, LLM agents, OCR and vision models on the other.

Looking for a junior internship in cybersecurity, AI or backend — available immediately, from February 2027, or as a summer 2027 intern.

## 🌐 Links
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/nuno-s) [![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/Gost_Evil) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:nunos@nunos.dev)

<!-- [![Portfolio](https://img.shields.io/badge/Portfolio-nunos.dev-000000?logo=googlechrome&logoColor=white)](https://nunos.dev) [![CV](https://img.shields.io/badge/CV-Download-2E7D32?logo=adobeacrobatreader&logoColor=white)](https://nunos.dev/cv.pdf) -->

## 🔧 Projects
**SSH/HTTP Honeypot** - in development Medium/high-interaction SSH and HTTP honeypot written from scratch in Python (asyncio). It records credentials tried, commands, user agents and SHA-256 hashes of attempted malware downloads, maps attacker behaviour to MITRE ATT&CK techniques and groups campaigns across different IPs. Nothing is ever executed: the service runs sandboxed, with a read-only filesystem and no outbound traffic. Public dashboard with session replay and a real-time 3D attack globe. `Python` `asyncio` `MITRE` `ATT&CK` `Linux hardening` `three.js`

**UPBot / NEEI Bot** - AI student verification and exam archive · in production Discord bot for my university's computer engineering student association. It verifies students automatically by extracting text from enrollment certificates (pypdf, or Tesseract OCR on scans) and matching name, student number and academic year, tolerating accents and common OCR errors. Exams are classified by an LLM agent that returns structured JSON, falling back to vision models when the extracted text is weak. Four-level permission system, action logging, tested with pytest and deployed as a systemd service. Python discord.py `Tesseract` `OCR` `LLM APIs` `vision models`

**ZARCO · personal life manager** - in production Full-stack app I use every day, where an AI layer does the work I don't want to do by hand: it reads receipts and categorises expenses on its own, watches my Garmin health data for changes and proposes what caused them, and turns loose ideas into concrete to-dos. Around it sit modules for calendar, notes, habits, sleep, trips, investments and screen time, plus a refereeing module that works out fuel costs, compares motorway against national roads and tracks match earnings. FastAPI and SQLAlchemy 2 over PostgreSQL 16 with Alembic migrations, React frontend, self-hosted on an Oracle Cloud VPS with Docker Compose and Caddy for automatic HTTPS, plus update, backup, restore and health-check scripts. `Python` `FastAPI` `PostgreSQL` `React` `TypeScript` `Docker` `Caddy`

<!-- **Second brain UPB · local-first search engine for course material** - in development Search engine over my own course material from the university Moodle, with an inverted index and BM25 ranking implemented from scratch, running entirely in the browser. Privacy by design: each student indexes only what they already have access to, and private documents never leave the device. `JavaScript` `IndexedDB` BM25` `Moodle` `API` -->

**Homelab** — self-hosted development server An old laptop turned into a Proxmox host that I reach over Tailscale to run coding agents remotely, keeping my main machine free. SSH for day-to-day work, systemd services, all on free tiers. `Proxmox` `Debian` `Tailscale` `SSH`


## 💻 Tech Stack
 
**Languages**
 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
 
**Backend**
 
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
 
**Frontend & 3D**
 
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Three.js](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white&style=for-the-badge) ![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
 
**Databases**
 
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white)
 
**Backend-as-a-Service**
 
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
 
**Cloud & Infrastructure**
 
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![OVH](https://img.shields.io/badge/ovh-%23123F6D.svg?style=for-the-badge&logo=ovh&logoColor=#123F6D) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
 
**Networking & Security**
 
![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black) ![WireGuard](https://img.shields.io/badge/wireguard-%2388171A.svg?style=for-the-badge&logo=wireguard&logoColor=white) ![Tor](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)
 
**IoT & Embedded**
 
![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) ![PlatformIO](https://img.shields.io/badge/PlatformIO-%23222.svg?style=for-the-badge&logo=platformio&logoColor=%23f5822a) ![Mosquitto](https://img.shields.io/badge/mosquitto-%233C5280.svg?style=for-the-badge&logo=eclipsemosquitto&logoColor=white) ![Node-RED](https://img.shields.io/badge/Node--RED-%238F0000.svg?style=for-the-badge&logo=node-red&logoColor=white)
 
**AI & Data**
 
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
 
**Tools**
 
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)
 


