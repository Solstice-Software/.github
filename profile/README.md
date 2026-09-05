![Solstice Software logo](https://github.com/user-attachments/assets/a0ae6bfb-f484-4757-bdc2-2ad2199e6353)


# Secure Solutions: Cleanly Engineered

[Solstice Software](https://solstice.software/ "Our primary website") is an American security research and development company that seeks to make a few ripples in the vast cybersecurity lake. Our endeavors include independent security research, meticulously curating powerful security software-as-a-service products, and occasional consulting services.

It produces high-quality projects for public and private use of its own and that of others.

Solstice Software will always be:
- 🏃‍♂️ **Active & Reachable**: Drop a line any time to _services[@]solstice.software_.
- 📂 **Open-Source**: Proprietary software is _really_ 1995. Projects work best when the greatest and most passionate minds freely collaborate.
- 🔍 **Meticulous & Clean**: Focused on detail and quality in all things, not just "where it counts".
- 📈 **Innovating through R&D**: It Just Works™️ is not good enough.


## What's Cooking Lately?
This section is occasionally updated to include interesting information about Solstice Software's latest endeavors.


### EquiKnox
Turn hours of manual application sandboxing and security review into a repeatable, machine-generated security contract.

At its heart, _EquiKnox_ is a compiler that derives and enforces the behavioral security contract of software.

Today, putting an unfamiliar application into a restrictive sandbox can require a highly skilled security engineer to determine:

- What files does it need?
- What directories does it write?
- What processes does it execute?
- What network destinations does it contact?
- What privileges/capabilities does it need?
- What changes between application releases?
- Which accesses are legitimate versus unexpected?
- What can safely be denied?

_EquiKnox_ turns that into:

> **binary** &rarr; **analysis** &rarr; **security contract** &rarr; **human review** &rarr; **enforcement**

The most attractive use case may be third-party or opaque software, where the customer doesn't control the source code and therefore has difficulty determining what privileges the software genuinely requires and thus should be able to exercise.

It is not:

- "AI antivirus"
- generic anomaly detection
- EDR
- "learn what the program normally does and block anomalies"
- a simple syscall monitor
- a simple Linux sandbox
- a simple AppArmor/seccomp frontend

Stay tuned as the product is being developed and evaluated for commercial viability.
