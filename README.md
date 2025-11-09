
# Project Report: System Monitor Tool

## 1. Title
**System Monitor Tool (Console-based, Linux)**  
An interactive terminal-based system monitor similar to `top` that shows overall CPU/memory usage and lists running processes with per-process CPU% and memory% and supports killing processes.

---

## 2. Codes
Below is the main source file used for the project.

```cpp
// See attached file: system_monitor.cpp
// (Full code saved in system_monitor.cpp in repository)
```

> For convenience the full code file `system_monitor.cpp` is included alongside this report.

---

## 3. Full screenshots
Include the following screenshots in this section (replace placeholders with actual images):
1. Compilation screenshot: `g++ system_monitor.cpp -o monitor -std=c++17 -O2`
   - [Insert screenshot: compile.png]
2. Running screenshot showing system stats and process list
   - [Insert screenshot: run1.png]
3. Example of killing a process: issued `k <pid>` and confirmation
   - [Insert screenshot: kill_example.png]

> **How to take screenshots:** Run the program and use your terminal/screenshot tool (e.g., GNOME Screenshot or `import`) to capture the output. Save images into `/screenshots` folder and upload to GitHub.

---

## Build & Run Instructions

1. Clone repository (after you push code to GitHub):
   ```
   git clone <your-repo-url>
   cd System-Monitor-Tool
   ```

2. Compile:
   ```
   g++ system_monitor.cpp -o monitor -std=c++17 -O2
   ```

3. Run:
   ```
   sudo ./monitor
   ```

   (Some process info or kill operations may require elevated privileges depending on system policies.)

---

## GitHub Repository Structure (suggested)

```
System-Monitor-Tool/
├─ system_monitor.cpp
├─ Readme.md
├─ monitor
├─ system_monitor_tool.pdf
├─ screenshots/
│  ├─ compile.png
│  ├─ run1.png
│  └─ kill_example.png
```

---

## Notes & Extension Ideas (highlight if extended)
If you extended the project (e.g., added network monitoring, CSV logs, web UI), rename title to **Advanced System Monitor Tool** and highlight the new title in **yellow** in the final submitted PDF.

Possible extensions:
- Export metrics periodically to CSV/JSON.
- Add terminal UI library (ncurses) for better interactivity.
- Add filters/sort and search by process name.
- Add TCP/UDP per-process socket info.

---

## Submission
- Push code and report to a **public GitHub repo**.
- Upload the report and screenshots.
- Provide the repo link in the Google Form for submission.
