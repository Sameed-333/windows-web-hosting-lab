# Windows Web Hosting Lab (IIS)

This mini-project demonstrates hosting a website on a Windows machine and validating access from client systems over the network. It includes host-side web configuration and browser-based verification from User1 and User2 machines.

**Course:** System & Network Administration (SNA Lab)  
**Tool Used:** IIS (Internet Information Services)  
**Focus:** Windows web hosting, LAN access verification, multi-client testing

---

## Tools & Technologies
- Windows (host + client machines)
- IIS (Internet Information Services)
- Web browser (client-side validation)

---

## Project Files
- `report/` (lab report / documentation)
- `assets/` (screenshots: host configuration + client access proof)

---

## What’s Demonstrated
- Configuring web hosting on the host machine (IIS setup / site configuration)
- Hosting a website on the LAN
- Validating access from multiple clients:
  - User1 accessing the hosted website
  - User2 accessing the hosted website

---

## Key Learning
- How to publish a basic website from a Windows host using IIS
- How to validate hosted content from other machines on the same network
- How to document hosting setup and client-side verification as lab evidence

---

## Screenshots
Evidence is available in `assets/`:
- `01-host-web-configuration.png`
- `02-user1-accessing-hosted-website.png`
- `03-user2-accessing-hosted-website.png`
- `04-host-site-files-or-root.png`

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Sameed-333/windows-web-hosting-lab.git
```

2. Navigate to the project folder:
```bash
cd windows-web-hosting-lab
```

3. Review documentation and evidence:
- Open the report inside `report/`
-  Review screenshots in `assets/`

4. Validate (high-level):
- Configure the website on the host machine using IIS
- From client machines (User1/User2), open a browser and access the hosted website
- Confirm the hosted page loads successfully from both clients

## Disclaimer
This project is for educational purposes only as part of a university SNA lab. It demonstrates basic IIS web hosting in a controlled environment and is not intended as a complete production hosting guide.
