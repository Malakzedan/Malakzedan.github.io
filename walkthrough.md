# Portfolio Redesign Walkthrough

The portfolio has been fully redesigned to create a premium, interactive, recruiter-ready website targeting Big Tech hiring managers.

## Key Changes Made

### 1. Visual & Theme System
- **Modern Typography**: Integrated **Outfit** (for headers), **Inter** (for body copy), and **JetBrains Mono** (for system logs and terminal commands).
- **Responsive Layout**: Designed a layout using CSS Grid and Flexbox that transitions smoothly from extra-large screens to mobile devices.
- **Light/Dark Toggle**: Implemented a theme-switching system using CSS variables that remembers the visitor's choice in local storage.

### 2. Interactive CLI Terminal (Hero Section)
- Upgraded the static terminal simulator into a **real-time interactive terminal**.
- Captures key strokes using a hidden text input to allow users to interact.
- Commands supported:
  - `help`: list commands.
  - `about`: display Malak's background summary.
  - `skills`: list categorized skills.
  - `projects`: summary of key systems built.
  - `experience`: display professional roles.
  - `cv`: triggers the resume modal.
  - `clear`: clears terminal buffer.

### 3. System Design Showcase (Graduation Project - IISS)
- Created an interactive layer explorer for the **Intelligent Interview Simulation System (IISS)** (no public repository link).
- Recruiters can click through layers (Client, Gateway, AI Engine, Database) to see specific tech stacks, data flow parameters, and core engineering challenges solved (like frame rate throttling and model inference latency).

### 4. Project Showcase & Live Domain Integration
Structured the project cards grid, resume modal, and terminal commands to match all seven of Malak's projects:
- **CompilationPipeline** (Java): Compiler design demonstrating lexical scanning, LL/LR parsing, AST parsing, and static type audits. **[Linked to GitHub]**
- **sentimentiq** (Python): NLP sentiment analysis system optimized with TF-IDF and GridSearchCV tuning. **[Linked to GitHub]**
- **User-merchant-portal** (JS): Secure portals built during the AAIB internship containing customer checkouts and merchant management APIs. **[Linked to GitHub]**
- **Master Builder Company Platform** (JS): Dual-sided digital platform combining project discovery, dynamic service requests, and content moderation dashboards. **[Linked to live website]**
- **Secure Enterprise Infrastructure**: VM pools, private subnets, cloud firewalls, and isolated public route tables on Microsoft Azure. **[Showcased without GitHub link]**
- **Clinical Disease & MRI Classification**: CNN and Autoencoder classifiers for Alzheimer MRI tissue maps and classical ML models on medical indicator datasets. **[Showcased without GitHub link]**

### 5. DSA Algorithm Playground (ECPC Highlight)
- Demonstrates strong algorithmic capabilities directly in-browser.
- **Binary Search**: Displays a sorted array with pointer overlays representing `Left (L)`, `Right (R)`, and `Middle (M)`. Updates step-by-step to show the log(N) reduction path.
- **Bubble Sort**: Generates random visual bars and animates the sorting comparisons and swaps, coloring states dynamically (comparing, swapped, sorted).

### 6. Professional Resume Modal
- Integrated a resume popup containing a copy of Malak's CV.
- Includes a direct download link targeting [Malak_Zedan_CV.pdf](file:///d:/Malukk/CV/Malak_Zedan_CV.pdf).
- **Privacy Update**: Removed the phone number (`01111921892`) from the CV header in the resume modal to protect candidate privacy.

### 7. STAR-Formatted Descriptions & SEO
- Re-phrased the bullet points for **Jelecom**, **ECPC**, and **AAIB** using the STAR methodology, highlighting key performance metrics and engineering details.
- Added Open Graph (OG) tags for optimized previews on LinkedIn.

## Verification Details

- **Link Checking**: Checked the GitHub URLs:
  - `https://github.com/Malakzedan/CompilationPipeline`
  - `https://github.com/Malakzedan/sentimentiq`
  - `https://github.com/Malakzedan/User-merchant-portal`
- **Link Removal**: Confirmed that the "Azure Cloud Infrastructure" and "Clinical Disease & MRI AI" cards in the projects grid, the resume modal, and IISS do not display GitHub link icons or invalid link targets.
- **Responsive Testing**: Checked all blocks, grids, and flex components; they adapt cleanly on smaller viewports.
- **Command execution**: Verified terminal inputs correctly match actions.
- **Theme toggle**: Verified dark mode default works and switches to light mode without layout shifts.
