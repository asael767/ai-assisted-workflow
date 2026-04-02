# AI‑Assisted Workflow Setup (Cursor, Claude Code & Codex)

## 1) Tools Installed
- **Cursor IDE** (Windows)
- **Claude Code** (Anthropic) — installed via Cursor Extensions
- **Codex – OpenAI’s coding agent** — installed via Cursor Extensions
- **Git for Windows (x64)** — added to PATH (“Git from the command line and 3rd‑party software”)
- **GitHub** — public repository: `https://github.com/asael767/ai-assisted-workflow`

---

## 2) Steps Completed
1. **Installed Cursor IDE** and launched it successfully.  
   - On first run Windows suggested updating **WSL**; identified it as **optional** for this workflow and skipped it to avoid unnecessary setup.

2. **Installed Claude Code** (Anthropic) from Extensions.  
   - **Validated access** by sending a simple prompt in the side panel and receiving a response (no auth errors).

3. **Installed Codex – OpenAI’s coding agent** from Extensions.  
   - On **Windows**, Codex does **not** show a visible sign‑in button; treated this as platform‑specific behavior and **validated access functionally** (extension active, no auth warnings).

4. **Created a public GitHub repo** named `ai-assisted-workflow` (no auto‑README, no .gitignore, no license — full control of first commit).

5. **Installed Git for Windows**, restarted Cursor, and **cloned** the existing GitHub repository **from Cursor** (not “Initialize Repository”).  
   - Verified remote linkage:
     ```bash
     git remote -v
     # origin https://github.com/asael767/ai-assisted-workflow.git (fetch)
     # origin https://github.com/asael767/ai-assisted-workflow.git (push)
     ```

6. **Created this `README.md`** inside the cloned repo to document setup and decisions.

---

## 3) Problems Encountered & How I Solved Them
- **WSL prompt on first Cursor launch**  
  *Diagnosis:* Not required for this assignment.  
  *Action:* Skipped update; proceeded with native Windows environment.  
  *Result:* Avoided unnecessary complexity; Cursor worked as expected.

- **Git commands unavailable at first**  
  *Diagnosis:* Git wasn’t installed/detected.  
  *Action:* Installed **Git for Windows (x64)**, kept defaults (PATH enabled), restarted Cursor.  
  *Result:* `Git: Clone` and Source Control became available.

- **Git default editor not allowing VS Code selection**  
  *Diagnosis:* VS Code option unavailable in installer.  
  *Action:* Selected **Notepad++** as Git’s default editor to avoid CLI editors like Vim; continued using **Cursor** as main IDE.  
  *Result:* No friction for commits/merges; stable setup.

## Additional Evidence
Screenshots from the setup process are available in the `screenshots` folder for reference.

``
## Research Project - Topic #3: AI-Driven SEO Content Production (B2B SaaS)

**Chosen topic:** #3 AI-Driven SEO Content Production

**Why I chose this topic:**  
My hands-on experience producing landing pages, copy, and lifecycle email sequences using Claude/Grok (Bakery La Familia and Overcoming) + my Microsoft Career Essentials Generative AI certification. This project lets me demonstrate using AI with strong personal judgment, not as a crutch.

**Expert selection criteria:**  
I selected 10 high-signal practitioners (not just theorists) who actively publish and implement AI-driven SEO strategies for B2B SaaS in 2026. I prioritized people with measurable case studies, recent content, and proven results in AEO/GEO, zero-click content, and generative AI content production.

**Sources:**  
See `/research/sources.md` for the full list with LinkedIn links.

**Next steps in this research:**  
- Collect recent LinkedIn posts from each expert (using Claude Code / Codex)  
- Obtain YouTube transcripts via free API  
- Organize everything in `/research/linkedin-posts/` and `/research/youtube-transcripts/`

This research will serve as the foundation for creating a real, actionable playbook (as requested by the role).