# Dotivra Prototype — Client Demo Guide

This repo provides a **clickable front‑end prototype** and maps the **exact demo flow shown in your colleague’s video** so clients can follow along without confusion. It also explains how to run the site via **VS Code (Live Server)** and lists **direct URLs** to key pages.

---

## 1) Introduction to the Prototype

- **What this is:** A static, front‑end prototype (HTML + Tailwind CDN) for a **Project Workspace** that organizes documentation for two domains: **Clinic** and **Bank**.
- **Quick Start:** Use the new `startup.html` at the repo root for a one-stop navigation to all features and demo pages. This page lets you review every available prototype feature with direct links.
- What it demonstrates:
  - A **Project Overview** launchpad
  - **Document libraries** by role (Developer, Backend, Frontend, PM, QA, User)
  - An **“Add Document”** flow with **AI‑assisted templates** vs **blank templates**
  - **Rich editor** pages with toolbar, status chips, and a **collaboration/lock simulation**

---

## 2) How to Start (VS Code)

### Option A — VS Code + Live Server (Recommended)
1. Install **VS Code** and the extension **_Live Server_** (by Ritwick Dey).
2. Open the repository folder in VS Code (it should contain: `startup.html`, `Project Root Interface/`, `Clinic Project/`, `Bank Project/`, `action/`, `oldmodel/`).
3. In the Explorer, right‑click **`startup.html`** → **Open with Live Server**.
4. Your browser should open `http://127.0.0.1:5500/startup.html`.  
   (If the port differs—e.g., `5501`—that’s fine.)
5. Use the **Startup & Feature Navigator** to access all demo pages and features.

---

## 3) Demo Flow

> This mirrors the colleague’s walkthrough so a client can replicate the exact path.

### A. From Project Overview → Choose a Workspace
1. Open **Project Overview**  
   **Path:** `Project Root Interface/projectOverview.html`
2. Observe quick links (recent items / template gallery).
3. Click **Clinic Management System** (you can repeat similar steps later for **Bank Management System**).

### B. Clinic Workspace — Document Library & Add Document
4. Land on **Clinic Document List**  
   **Path:** `Clinic Project/clinic-document-list.html`  
   - Use **search** and **filter by role** (Developer, Backend, Frontend, PM, QA, User).
5. Click **Add document** (top right). A modal opens:
   - Select a **Role** (e.g., **Developer**).
   - Select a **Template** (e.g., **API Documentation**).
   - Choose either:
     - **Use AI** → routes to a **filled** template editor; or
     - **Don’t Use AI** → routes to a **blank** template editor.

### C. Clinic Editors — Explore the Rich Editor
6. If **Use AI** was chosen (example pages):
   - **API (template):** `Clinic Project/clinic-template/apiTemplate.html`
   - **Developer Manual (template):** `Clinic Project/clinic-template/developer-manual-template.html`
   - **SRS (template):** `Clinic Project/clinic-template/srsTemplate.html`
   - **System Summary (template):** `Clinic Project/clinic-template/summarySystem.html`
   - **User Manual (template):** `Clinic Project/clinic-template/user-manual-template.html`
7. If **Don’t Use AI** was chosen (blank templates):
   - **API (blank):** `Clinic Project/clinic-blank-template/api-blank-temp.html`
   - **Developer Manual (blank):** `Clinic Project/clinic-blank-template/developer-manual-temp.html`
   - **SRS (blank):** `Clinic Project/clinic-blank-template/srs-blank-template.html`
   - **Summary (blank):** `Clinic Project/clinic-blank-template/summary-blank-template.html`
   - **Empty page:** `Clinic Project/clinic-blank-template/empty-blank-temp.html`
   - **Commit log (blank):** `Clinic Project/clinic-blank-template/commit-blank-template.htm`
8. In the editor, demonstrate:
   - Toolbar actions (formatting, headings, lists)
   - **Status chips** (Draft/In Review)
   - **Comments/annotations** (if shown in the video)
   - **Collaboration/Lock simulation** (multi‑user indicator)

### D. Bank Workspace — Parallel Flow
9. Return to **Project Overview**, select **Bank Management System**.  
   **Path:** `Bank Project/bank-document-list.html`
10. Explore cards by roles (**SE/Backend/Frontend/PM/QA/User**).
11. Use **Add Document** (focused page / modal).  
    **Path:** `Bank Project/action/addDocument.html`
12. Open an editor and showcase UX:
    - **Developer Manual Editor:** `Bank Project/bank-template/bank-management-editor.html`

### E. Shared Actions (Optional, if time in video)
13. **Editor V2 (shared):** `action/editor-Edit.html`
14. **Multi‑user Lock Simulation:** `action/multiUser_locked_simulated.html`

> **End State:** Return to **Project Overview**, recap the two workspaces and creation/editing flows.

---

## 4) Direct URLs (when hosted locally with Live Server)

### Main Entry Point
- **Startup & Feature Navigator:**  
  `http://127.0.0.1:5500/startup.html`

### Home
- Project Overview:  
  `http://127.0.0.1:5500/Project%20Root%20Interface/projectOverview.html`
- Template Gallery:  
  `http://127.0.0.1:5500/Project%20Root%20Interface/template.html`

### Clinic
- Document List:  
  `http://127.0.0.1:5500/Clinic%20Project/clinic-document-list.html`
- Templates (filled):  
  - API: `http://127.0.0.1:5500/Clinic%20Project/clinic-template/apiTemplate.html`
  - Developer Manual: `http://127.0.0.1:5500/Clinic%20Project/clinic-template/developer-manual-template.html`
  - SRS: `http://127.0.0.1:5500/Clinic%20Project/clinic-template/srsTemplate.html`
  - Summary: `http://127.0.0.1:5500/Clinic%20Project/clinic-template/summarySystem.html`
  - User Manual: `http://127.0.0.1:5500/Clinic%20Project/clinic-template/user-manual-template.html`
- Blank templates:
  - API: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/api-blank-temp.html`
  - Developer Manual: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/developer-manual-temp.html`
  - SRS: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/srs-blank-template.html`
  - Summary: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/summary-blank-template.html`
  - Empty: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/empty-blank-temp.html`
  - Commit: `http://127.0.0.1:5500/Clinic%20Project/clinic-blank-template/commit-blank-template.htm`

### Bank
- Document List:  
  `http://127.0.0.1:5500/Bank%20Project/bank-document-list.html`
- Editors:  
  - Developer Manual: `http://127.0.0.1:5500/Bank%20Project/bank-template/bank-management-editor.html`
- Add Document:  
  `http://127.0.0.1:5500/Bank%20Project/action/addDocument.html`

### Shared
- Editor V2: `http://127.0.0.1:5500/action/editor-Edit.html`
- Multi‑user Lock Simulation: `http://127.0.0.1:5500/action/multiUser_locked_simulated.html`

---

## Notes & Limitations
- **Static prototype**: no backend; page refresh may reset state.
- **CDN required**: Tailwind & Font Awesome load via CDN.
- **Spaces in paths**: URLs encode spaces as `%20`.
- **Tested** on latest Chrome/Edge.

---

## Troubleshooting
- **Blank/unstyled pages** → Check internet (for CDNs) and verify you’re serving via HTTP (Live Server / `http.server`).
- **Links 404** → Confirm you launched from the **repo root**, keep folder names intact.
- **Different port** → Update `5500` in URLs.

---

**Enjoy the demo!** For GitHub, consider adding screenshots/GIFs and linking the demo video from the repo home for quick orientation.
