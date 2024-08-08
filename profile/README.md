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
![image](https://github.com/user-attachments/assets/a6fb8904-0590-4ed7-9910-6d19772cf8f1)

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
![image](https://github.com/user-attachments/assets/0544ebf2-51c3-435d-94fe-4bfa447b57c0)
