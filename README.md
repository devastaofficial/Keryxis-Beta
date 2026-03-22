# 🌌 Keryxis-Beta

"We don't want your data, we have our own."

Keryxis is a performance-first, privacy-hardened OS built for the hardware modern systems left behind. No telemetry. No background bloat. No forced features. Just a clean, purple-blue engine that respects your machine—whether it’s a 2010 potato with 2 GB RAM or a 5 GHz workstation.

***

### ⚡ The Philosophy

Most operating systems slow down because they waste your CPU cycles. We don't. We also didn't want to spend ten years writing a custom file system that Windows and Mac can read (we're developers, not masochists), so we took the best existing tech and tuned it for speed.

🧠 Use only what’s needed: Minimalist by design.

🔒 Zero Leaks: We don't want your data. Period.

⚙️ Predictable Load: Zero background "indexing" or hidden spikes.

🚫 No Bloat: We cut the abstractions that turn a 1 GHz CPU into a paperweight.

***

### 🏗️ Architecture: The RAM-Resident Edge

Unlike Windows, which "thrashes" your disk, Keryxis is a RAM-Resident Hybrid.

The Boot: At startup, the core system image is loaded entirely into RAM.

The Result: System calls and UI transitions happen at memory speeds. 1 GHz feels like a Threadripper.

The Drive: Your disk is for your data—not for the OS to play with. This keeps the bus open for what matters.

### 🎯 Design Goals

Instant UI: A custom Ring 3 compositor themed in deep Purple & Blue.

The  App Launcher: One button, 25% of the screen, all your apps. No folders, no "suggested" junk.

"Everything" Search: Integrated kernel-level indexing. Scan once at boot, search instantly forever.

***

### 💾 Storage & Compatibility

We didn't write our own file system. Instead, we use a high-performance hybrid stack to give you the best of both worlds:

🚀 System Partition (F2FS): The OS lives on a Flash-Friendly File System. It’s ultra-fast, optimized for SSD/NVMe, and keeps your Ring 3 security tight. (Note: Windows can't see this, which keeps your system files safe from "accidental" Microsoft meddling).

🤝 Data Partition (exFAT): Keryxis automatically creates a secondary partition formatted in exFAT. Since every OS on earth speaks exFAT, you can plug your drive into a Windows PC or a Mac and your "homework" will be right there.

***

### 🛡️ Hardware Requirements

No artificial restrictions. No TPM nonsense. No "minimum version" checks.

Minimum (The "Closet Laptop")	

CPU	1 GHz+ 64-bit	

L3 Cache	2 MB 

RAM	1 GB	

Storage	4 GB Partition	

Basic Display Output	

Recommended (The "Flying" Tier)

Any "relevant-in-this-era" components, preferrably at least 4 GB RAM(since 8 GB is the bare-minimum nowadays)

The more you give, the more we optimize—leaving more than enough for your “homework.” Yup, we’re looking at you. 🫵

***

### 🧩 Compatibility & Legal

The Kernel: Keryxis utilizes a modified Linux kernel (GPLv2). Source code is available in the /kernel directory. Everything other than the kernel(which is already custom-stripped down by us for our needs) is proprietary and owned by us, but is completely free to use

#### DISCLAIMER:
Keryxis does not support kernel-level anti-cheats (e.g., Riot Vanguard). These drivers are hardcoded for Windows. Running them on Keryxis may result in bans because of the game flagging the kernel as unsigned. Use native-supported games for the best experience for gaming.

***

### 🚧 Project Status & Contribution

Keryxis is currently in Early Beta.
It is openly under passionate development and is more than happy to include more developers in this software movement.

Join the Team:

If you know your way around an MFT or a syscall table, open a PR. Let's show the world what optimized software actually looks like.

"Runs on anything. Flies on everything."
