# Minecraft-Discord-Phisher-Bot

## 📜 Disclaimer

**This tool is intended strictly for educational, ethical research, and authorized testing purposes only.**  
Any use of this project for malicious activity—including phishing, unauthorized access, or disruption of services—is strictly forbidden.

Using this tool without explicit, informed, and written consent from all participants may be considered illegal and is a direct violation of this project’s intent.

By using this software, **you agree to take full responsibility** for how it is used. The authors and contributors **assume no liability** for any misuse, harm, or legal consequences.

---

> 🛑 **Note:** Let’s not misuse this. Respect laws, ethics, and each other. ❤️

---

## ❔What Does It Do?
In theory, a malicious actor could create a Discord bot designed to mimic legitimate Minecraft services, with the goal of deceiving users into sharing sensitive account details. Such a bot might claim to require a Minecraft username and email address for purposes like account verification, server access, or rewards.

If a user unknowingly provides this information, the attacker could potentially exploit Microsoft’s authentication system. For example, by initiating a login and requesting an alternative verification method (such as email-based codes), an attacker could gain unauthorized access to the victim's account—if the user unknowingly shares the verification code with the attacker.

This scenario highlights the importance of never sharing authentication codes and being cautious when interacting with unofficial bots or services. Understanding how such tactics could theoretically work is essential for improving personal cybersecurity and developing better anti-phishing defenses.


## 🧾 Help
If you need futher help there is a link to a discord server below.<br>

[Help Server Link](https://discord.com/invite/SwjR85RGUA)<br>


## 🛠️ How to Run

1. **Download Python**: [Download Python](https://www.python.org/downloads/release/python-3110/)
2. **Create Your Bot**:
    - Generate your bot token and grant it all intents.
3. **Get MailSlurp API For Auto Secure**:
   - Visit [MailSlurp](https://www.mailslurp.com/) and copy the API key.
4. **Get Hypixel API For Stats**(You can skip this step):
   - Visit [Hypixel Dashboard](https://developer.hypixel.net/) and register for a account.
5. **Configure the Bot**:
    - Place the token Hypixel API, MailSlurp API into `config.py`.
    - Open bot.py and add your Discord ID in the line `self.admins = [YOUR DISCORD ID]`.
6. **Install Requirements**:
    - Open Command Prompt in the project folder and run `pip install -r requirements.txt`.
7. **Run the Bot**:
    - Execute the bot with the command `python bot.py`.
8. **Sync Commands**:
    - In your Discord server, type `!sync global`.
9. **Set Up Webhook**:
    - Use `/webhook` and enter the destination for your logs.

## What It Looks Like

### Logs Interface<br>
![Logs Interface](https://i.imgur.com/7ycbJLp.png)

### CMD Interface<br>
![CMD Prompt Interface](https://i.imgur.com/Hp0rAh4.png)

### Victim's Point of View<br>
(The profile picture of your bot may differ)<br>
![Victim's POV](https://i.imgur.com/s91N2fp.png)


(These Images Are No Longer Accurate I Will Update Soon)
