![Solstice Software logo](https://github.com/user-attachments/assets/a0ae6bfb-f484-4757-bdc2-2ad2199e6353)


# Secure Solutions: Cleanly Engineered

[Solstice Software](https://solstice.software/ "Our primary website") is a tiny security research "firm" (emphasis on the air quotes) which seeks to make a few ripples in the vast cybersecurity lake through independent security research, software engineering, and occasional consulting services.

It produces high-quality projects for public and private use of its own and that of others.

Solstice Software will always be:
- 🏃‍♂️ **Active & Reachable**: Drop a line any time at _services[@]solstice.software_.
- 📂 **Open-Source**: Proprietary software is _really_ 1995. Projects work best when the greatest and most passionate minds freely collaborate.
- 🔍 **Meticulous & Clean**: Focused on detail and quality in all things, not just "where it counts".
- 📈 **Innovating through R&D**: It Just Works™️ is not good enough.


## What's Cooking Lately?
This section is occasionally updated to include interesting information about Solstice Software's latest endeavors.


### MFTAH
![MFTAH Project Art](https://private-user-images.githubusercontent.com/31320277/329797836-bf749e83-d0b6-4a02-99cf-c97e17c3501a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjMwNzY0MTMsIm5iZiI6MTcyMzA3NjExMywicGF0aCI6Ii8zMTMyMDI3Ny8zMjk3OTc4MzYtYmY3NDllODMtZDBiNi00YTAyLTk5Y2YtYzk3ZTE3YzM1MDFhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA4MDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwODA4VDAwMTUxM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNhZmY5N2FiNzZiYzU0OTkyM2ZiNWJmN2UxMzVjNTEyNWExOWRhZDEyMjdhMGZkMzc5OWU5ZmIwYTNlY2I2NDAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.WfyxmG0J8tq7Q9aUbWeT3syl5KoJdqLxyhoZoTIWZ4I)

"MFTAH" stands for Media For Tamper-Averse Humans. As its name suggests, it creates a media device containing one or more bootloaders, each using an encryption mechanism that make it resistant to subversive tampering.

Its acronym and "artwork" are both inspired by the Arabic word for "_key_".

This project was motivated by two desires:
1. Is it possible to **FULLY ENCRYPT** an operating system, including its own bootloader?
2. With a fully encrypted system and bootloader, can the Evil Maid attack be mitigated?

The answer to question 1 is a resounding _Yes_! This project is already working for primary Solstice Software development workstations and miscellaneous laptops (running various flavors of Linux).

The answer to question 2 has yet to be fully determined, and will require more red-teaming after project completion.

#### What comes with it?
- The source to make the EFI application for booting.
- A full toolkit to create, decrypt, and modify MFTAH drives.
  - GUI for Windows in C#.
  - TUI for Unix systems in C (with ncurses).
- A host of CLI scripts to perform more detailed and careful MFTAH maintenance.

#### How does it work?
![MFTAH Workings](https://private-user-images.githubusercontent.com/31320277/329801386-b0606ca5-172d-4121-b4ff-980183821308.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjMwNzY0MTMsIm5iZiI6MTcyMzA3NjExMywicGF0aCI6Ii8zMTMyMDI3Ny8zMjk4MDEzODYtYjA2MDZjYTUtMTcyZC00MTIxLWI0ZmYtOTgwMTgzODIxMzA4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA4MDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwODA4VDAwMTUxM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJhYTM4YWIxNjY1NTc5ZmY2N2U0YzA3NGM4N2JjNWE2NzU1ZmE1YTYxZjZkYmUyZGE0NmQ3YzkzNGU1YWU5YjcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.M-qNet9qF6yJrDM3OT0ng1yW-KDiK-4tQ-7mqpDMd_o)

