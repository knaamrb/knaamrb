<div align="center">

# Ken Aryo Bramantyo

**Cyber Security Student @ BINUS University**

<a href="https://www.linkedin.com/in/ken-aryo/"><img src="https://img.shields.io/badge/LinkedIn-Ken%20Aryo%20Bramantyo-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:knabramantyo@gmail.com"><img src="https://img.shields.io/badge/Email-knabramantyo%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/knaamrb"><img src="https://img.shields.io/badge/GitHub-knaamrb-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>

<br>

<a href="#profile-summary">Profile</a> &nbsp;|&nbsp;
<a href="#education">Education</a> &nbsp;|&nbsp;
<a href="#skills">Skills</a> &nbsp;|&nbsp;
<a href="#achievements">Achievements</a> &nbsp;|&nbsp;
<a href="#projects">Projects</a> &nbsp;|&nbsp;
<a href="#experience">Experience</a>

</div>

---

## Profile Summary

Cyber Security undergraduate at BINUS University focused on DevSecOps
and web security. Built a containerized web service with a secured
GitHub Actions pipeline (pip-audit, CodeQL, Trivy image scanning).
Finalist in the IT Festival 2026 CTF and practicing web exploitation
through CyLab Security Academy. Comfortable with Git, the Linux
command line, Docker, Python, and PHP/Laravel. Also led a 35-person
event committee and managed a budget of up to IDR 28 million.

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>

---

## Education

| Degree | Institution | Period | GPA |
| --- | --- | --- | --- |
| **Bachelor of Computer Science, Cyber Security** | BINUS University | 2024 – Expected 2028 | 3.37 / 4.00 |

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>

---

## Skills

<!-- <p>
<a href="https://en.wikipedia.org/wiki/C_(programming_language)"><img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C"></a>
<a href="https://www.java.com"><img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"></a>
<a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"></a>
<a href="https://www.php.net"><img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"></a>
<a href="https://laravel.com"><img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel"></a>
<a href="https://www.mysql.com"><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"></a>
<a href="https://github.com/features/actions"><img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"></a>
<a href="https://www.docker.com"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></a>
</p> -->

| Category | Technologies |
| --- | --- |
| **Security** | Web exploitation (CTF), pip-audit, CodeQL, Trivy |
| **DevOps & Infrastructure** | Docker, Docker Compose, GitHub Actions, GitHub Container Registry, Nginx, Git, Linux (basic command line) |
| **Programming** | Python, PHP, Java, C, HTML |
| **Frameworks & Databases** | Laravel, MySQL |

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>

---

## Achievements

**Finalist, Capture The Flag, IT Festival 2026**
Organized by HIMAVO Micro IT, IPB University | Team of 3

Member of team "bubar". Attempted challenges across categories, with a focus on web exploitation, and studied the team's solutions to build hands-on security knowledge.

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>

---

## Projects

### B64 Translator: Containerized Web Service with Secured CI Pipeline

*Server & Network Administration course project · Team of 4 · Feb 2026 – Jun 2026*

*My contribution: Docker setup and the CI pipeline. The application code was AI-generated.*
[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/knaamrb/b64-translator)

- Containerized the web app with Docker Compose: Nginx reverse proxy in front of a Python API, with the backend isolated on a private bridge network. Only Nginx is exposed to the host, and config files are mounted read-only.
- Hardened the Dockerfile: Gunicorn instead of the dev server, a non-root user, cached dependency layers, and build tooling removed from the final image.
- Added healthchecks and restart policies.
- Built a GitHub Actions pipeline running pip-audit, a Docker build with API smoke tests, and CodeQL analysis in parallel.
- Gated image publishing: Trivy scans the image, and it is pushed to GitHub Container Registry only if the scan passes on `master`.
- Used least-privilege workflow permissions and pinned the Trivy action to a commit SHA.
- Fixed two HIGH-severity CVEs flagged by Trivy by removing build tooling from the final image.

**Stack:** Docker, Docker Compose, Nginx, Gunicorn, GitHub Actions, GHCR, Trivy, CodeQL, pip-audit (application: AI-generated Python/Flask)



### Capture The Flag (CTF)

Practice platform. Completed 23 beginner-level challenges, mostly web exploitation.
[![View Profile](https://img.shields.io/badge/CyLab%20Security%20Academy-M4sbro-1F2937?style=flat-square)](https://learn.cylabacademy.org/users/M4sbro)

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>

---

## Experience

| Role | Organization | Period |
| :--- | :--- | :--- |
| Project Manager, Eid al-Adha Event | MT Al-Khawarizmi | Mar 2026 – May 2026 |
| Logistics Staff, PMB Expo | MT Al-Khawarizmi | Jul 2026 – Sep 2026 |
| Member Development (Kaderisasi) Staff | MT Al-Khawarizmi | Feb 2026 – Present |
| Sponsorship Staff, TechFest | HIMTI | Apr 2026 – Jul 2026 |
| Technical Equipment, Transportation & Security (PTTK) Staff, Hishot 2025 | HIMTI | Apr 2025 – Sep 2025 |
| Web Development Activist | HIMTI | 2024 – 2025 |

<details open>
<summary><b>Project Manager, Eid al-Adha Event</b> &nbsp;·&nbsp; MT Al-Khawarizmi &nbsp;·&nbsp; Mar 2026 – May 2026</summary>

<br>

- Coordinated the media, public relations, program, equipment, and catering divisions, along with volunteers.
- Managed a committee of 35 members and a budget of up to IDR 28 million.
- Liaised with BINUS staff and campus security.
- Responsible for ensuring the event ran smoothly and on schedule.

</details>

<details>
<summary><b>Logistics Staff, PMB Expo</b> &nbsp;·&nbsp; MT Al-Khawarizmi &nbsp;·&nbsp; Jul 2026 – Sep 2026</summary>

<br>

- Prepared the supplies and equipment needed for the expo and spent a budget of IDR 300,000.
- Staffed the booth and invited expo visitors to join the organization.

</details>

<details>
<summary><b>Member Development (Kaderisasi) Staff</b> &nbsp;·&nbsp; MT Al-Khawarizmi &nbsp;·&nbsp; Feb 2026 – Present</summary>

<br>

- Helped prepare circle time sessions.
- Helped organize Friday prayer.

</details>

<details>
<summary><b>Sponsorship Staff, TechFest</b> &nbsp;·&nbsp; HIMTI &nbsp;·&nbsp; Apr 2026 – Jul 2026</summary>

<br>

- Responsible for documenting meeting notes from sponsorship client meetings.

</details>

<details>
<summary><b>Technical Equipment, Transportation & Security (PTTK) Staff, Hishot 2025</b> &nbsp;·&nbsp; HIMTI &nbsp;·&nbsp; Apr 2025 – Sep 2025</summary>

<br>


- Guided attendees to prayer facilities and supervised the seminar room, ensuring attendees returned safely and on time.
- Kept the seminar orderly, maintained the planned seating layout, and handed out microphones when needed.
- Contributed to planning attendee entry and exit flow, as well as the emergency procedure.
- Served on the documentation team for the online seminar.

</details>

<details>
<summary><b>Web Development Activist</b> &nbsp;·&nbsp; HIMTI &nbsp;·&nbsp; 2024 – 2025</summary>

<br>
- Built an Events page in HTML as a practice project assigned by the
  web development coordinator (not deployed to the live site).

</details>

<div align="right"><a href="#ken-aryo-bramantyo">↑ Back to top</a></div>
