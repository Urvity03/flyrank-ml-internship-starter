# FlyRank Week 1 (FL-01) Setup & Submission Checklist

This checklist guides you through the manual setup in **Claude.ai**, running the pressure-test evaluation, capturing the required submission screenshots, and submitting your assignment on the FlyRank portal board.

---

## 1. Manual Setup in Claude.ai (5 Minutes)

Follow these exact steps in your browser:

1. **Log in to Claude**:
   - Open [https://claude.ai](https://claude.ai) and sign in.
2. **Create a New Project**:
   - In the left sidebar, click **Projects** $\rightarrow$ **New Project** (or **Create Project**).
   - Enter the Project Name:
     ```text
     Urvi-AI-Portfolio-Tutor
     ```
   - Description (Optional):
     ```text
     AI Portfolio Tutor and Technical Reviewer for ML Engineer portfolio development.
     ```
3. **Configure Custom Instructions**:
   - In your project settings, click **Set Custom Instructions**.
   - Copy the complete system prompt from [`claude-project-prompt.md`](claude-project-prompt.md#2-project-custom-instructions-system-prompt) and paste it into the custom instructions box.
   - Click **Save Instructions**.
4. **Add Project Knowledge (Optional but Recommended)**:
   - Click **Add Content** / **Upload Files**.
   - Upload your resume (`Urvi_Tyagi_Resume_Final.tex` or PDF) and the [`sitemap.md`](sitemap.md) file so Claude has direct access to your ground-truth background.

---

## 2. Running the Pressure-Test Evaluation

1. Inside your `Urvi-AI-Portfolio-Tutor` project, click **Start a new chat**.
2. Copy the entire prompt from [`pressure-test-prompt.md`](pressure-test-prompt.md) and paste it into the message box.
3. Send the message and review Claude's structured 6-point evaluation.

---

## 3. Required Submission Evidence & Screenshots

Before submitting on the FlyRank portal board, capture these 4 screenshots:

| # | Required Evidence Item | What to Capture | File Name Suggestion |
|---|---|---|---|
| **1** | **Claude Project Overview** | Browser screenshot of the `Urvi-AI-Portfolio-Tutor` project dashboard showing the project title and knowledge files. | `01_claude_project_dashboard.png` |
| **2** | **Custom Instructions Screen** | Screenshot showing the custom instructions editor with the candidate proof statement and role guidelines saved. | `02_custom_instructions_editor.png` |
| **3** | **Pressure-Test Execution** | Screenshot of the active chat conversation in Claude displaying the pressure-test prompt and Claude's detailed critique. | `03_pressure_test_critique.png` |
| **4** | **Sitemap Artifact / Sketch** | Rendered image or screenshot of the visual sitemap diagram from [`sitemap.md`](sitemap.md). | `04_portfolio_sitemap_sketch.png` |

---

## 4. Final Submission Card Verification Checklist

Ensure every item below is verified before marking FL-01 as complete:

- [ ] **One Target Audience Defined**: Technical Hiring Managers & Senior ML Engineers (explicitly stated in sitemap & prompt).
- [ ] **One Primary Action Defined**: In-depth review of a technical case study and direct interview contact.
- [ ] **Proof Statement Grounded in Reality**: Covers real verified projects (MLCopilot, WEGOTCHU, FlyRank ML, VeriMedia, Termstory).
- [ ] **Sitemap Justification Complete**: Written rationale for why every section earns its place and eliminates recruiter friction.
- [ ] **Claude Project Created**: `Urvi-AI-Portfolio-Tutor` configured with authentic candidate context.
- [ ] **Pressure-Test Completed**: Audit executed and reviewed against the 30-second hiring manager scan test.
- [ ] **All Files Stored in Folder**: All markdown and evidence files organized in `FL-01-Draw-the-Path/`.
