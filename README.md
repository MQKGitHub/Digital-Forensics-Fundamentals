### 🛡️ Digital Forensics Fundamentals

**Room:** [Digital Forensics Fundamentals — TryHackMe](https://tryhackme.com/room/digitalforensicsfundamentals)  
**Status:** ✅ Completed  
**Date:** *09 June 2025* 

### 🎯 Objective
Understand the core concepts, phases, and tools used in digital forensics. Gain practical skills in identifying, acquiring, and analysing digital evidence, with a focus on Windows forensics and basic metadata investigation.

---

### 🗝️ Key Concepts  
- **Digital Forensics** — Investigating digital devices to uncover evidence of cyber crime or policy violations.  
- **NIST Methodology** — The process is split into four phases: Collection, Examination, Analysis, and Reporting.  
- **Types of Forensics** — Includes Computer, Mobile, Network, Database, Cloud, and Email forensics.  
- **Chain of Custody** — A document that tracks evidence handling to prove its integrity.  
- **Write Blockers** — Prevent accidental modification of data during acquisition.  
- **Windows Forensics** — Involves disk and memory image acquisition for investigation using tools like FTK Imager, Autopsy, DumpIt, and Volatility.  
- **EXIF Data** — Metadata stored in image files, which can include GPS coordinates and device information.

---

### 🛠️ Tools Used
- **FTK Imager** — Used for capturing and viewing disk images from Windows systems.  
- **Autopsy** — Open-source tool for analysing disk images (file metadata, deleted files, etc.).  
- **DumpIt** — Used to create memory images of Windows machines.  
- **Volatility** — Framework for analysing RAM dumps with specific plugins.  
- **pdfinfo** — Extracts metadata from PDF documents (creator, dates, etc.).  
- **exiftool** — Reads metadata (including GPS) from images, used to locate where photos were taken.

---

### ⚠️ Challenges Faced
- Interpreting and converting GPS coordinates into map search format required attention to detail.
- Understanding the differences between volatile and non-volatile memory took some rereading to fully grasp.

---

### 🧠 What I Learned
- Learned how digital evidence is collected and processed legally and technically.
- Understood the critical importance of preserving the integrity of evidence.
- Gained hands-on experience in reading metadata from documents and photos to extract key details like creation tools, timestamps, and location data.
- Realised how almost any digital action leaves behind a trace that can be analysed.

---

### 🌐 Real-World Application:
> These fundamentals are key for roles in cyber crime investigation, incident response, and legal digital evidence handling. Whether working in a SOC or for law enforcement, understanding how to extract and analyse digital evidence is essential for tracing events and supporting legal action.

---

### 💭 Reflections:
- This room gave a great overview of both theory and practical work in forensics. Analysing EXIF data to find the photo’s location was surprisingly powerful.
- I’m now more interested in learning how to use Autopsy and Volatility on real cases.
- Digital forensics could be a career path I'd like to explore further alongside SOC Analyst work.
