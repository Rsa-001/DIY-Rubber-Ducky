# DIY-Rubber-Ducky

Project name: DIY Rubber Ducky (Homebuilt)

Category: Hardware / Physical Access Payload Delivery

Owner: RSA

Documentation link: https://rsas-book.gitbook.io/rsas-book/projects/rubber-ducky-homemade-version

---

### What this project is?

A practical, homebuilt “Rubber Ducky”-style USB device that emulates a keyboard (HID) to execute a scripted sequence on a target workstation. The goal is to learn the full end‑to‑end workflow: building the device, writing payloads, safely testing them in a lab, and documenting the results in a clean, repeatable way.


### Why I built it?

This project is about making physical-access attacks real and testable. It’s one thing to read about HID injection, this makes it hands‑on: device setup, timing quirks, OS behavior differences, payload reliability, and the operational details that matter in real environments.

-----------

### ⛏️WORKFLOW 

Build & flash the device (microcontroller + HID firmware)

Create payload scripts (keystroke sequences + timing)

Host supporting files (optional: local web server for downloads)

Execute in a controlled lab (Windows test VM, snapshots enabled)

Validate outcomes (what ran, what artifacts were created)

Document (steps, failures, fixes, and final reliable version)

----

### 💻Lab environment

Target: Windows workstation VM (snapshots enabled)

Attacker/support: Kali Linux VM for hosting files (HTTP) and analysis

Network: Isolated lab network / NAT-only as needed

Verification: Logs/artifacts collected after each run (timestamps matter)
