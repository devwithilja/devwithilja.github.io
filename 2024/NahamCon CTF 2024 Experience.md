## NahamCon CTF 2024 Experience

From May 25th to 26th, I had the pleasure of participating in NahamCon 2024's 48-hour Capture The Flag (CTF) event. It was an exhilarating and challenging experience that tested and honed my cybersecurity skills.

### Team Performance
Our team secured the 153rd position out of over 3,800 teams and 7,200 players, which was a remarkable achievement given the scale and competitiveness of the event.
![TeamPlacement](https://github.com/devwithilja/devwithilja.github.io/blob/main/2024/NahamCon_2024_images/NahamCon-CTF.png)

### Challenges
The CTF featured 70 diverse challenges. One of the highlights for me was the "Curly Fries" challenge, a privilege escalation task that involved:

- Leveraging `.bash_history` to switch users.
- Discovering a cleartext password used as a command line argument.

This challenge provided a valuable lesson in system vulnerabilities, specifically how using the `curl` command with the `-o` option and root or sudo rights can overwrite any file while preserving the original file's permissions. This insight raises important questions about the potential risks, such as overwriting critical system files like `/etc/passwd` or `/etc/sudoers`.

### Learning and Resources
For those interested in the challenges, they can be viewed [here](https://ctf.nahamcon.com/challenges). They may also be available later on [HackingHub](https://app.hackinghub.io/).

I've also compiled some notable write-ups from the event:
- [Magic RSA writeup by Mukund Kedia](https://medium.com/@mukundkrkedia/nahamcon-ctf-2024-crypto-writeup-magic-rsa-encryption-server-6edd1cd9704f)
- Mobile challenge write-ups by [_blackb3ard (aka avila)](https://hackmd.io/@avila-pwn-notes/r183kzlEA)
- Malware write-ups by [sp34rh34d](https://github.com/sp34rh34d/CTF-writeups/tree/main/NahamCon2024)
- Comprehensive write-ups of various challenges and past CTF events by [LazyTitan33](https://github.com/LazyTitan33/CTF-Writeups/tree/main/Nahamcon-2024)

### Team Building and Infrastructure
Building and leading the team was a significant part of the experience. I set up and managed our infrastructure using Discord and Notion, ensuring smooth communication and collaboration. Key activities included:

- Identifying team members' strengths and suggesting challenges suited to their skills.
- Actively engaging with teammates to understand ongoing challenges and provide support, even when unfamiliar with the topic. This often helped clear our minds and find solutions more effectively.

### Reflection
Participating in NahamCon 2024's CTF was a profound learning experience. It underscored the importance of teamwork, continuous learning, and proactive problem-solving in cybersecurity. I am eager to apply these insights to future challenges and contribute to the cybersecurity community.
