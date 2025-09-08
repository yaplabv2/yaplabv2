# 🔬 Cardiovascular Biomechanics and A.I. Laboratory
Yap Lab Website V2

📧 Welcome to connect with us: [c.yap@imperial.ac.uk](mailto:c.yap@imperial.ac.uk)

(This repository hosts the YapLab lab homepage, built with static HTML/CSS/JS.)

---

### 📂 1. Overall Structure
```bash
/ (root directory)
│── index.html / YapLab.htm       # Main landing page
│
├── Image/                        # Static image resources
│   ├── Imperial/                 # Logos, branding, institutional assets
│   ├── News/                     # News carousel images
│   ├── People/                   # Lab member portraits
│   └── Research/                 # Research-related figures
│
├── Research/                     # Research detail pages
│   ├── Image/                    # Figures for research subpages
│   ├── Code.htm                  # Code & Dataset page
│   ├── research-1-1(...).htm     # Deep Learning Image Registration & Segmentation
│   ├── research-1-3(...).htm     # Machine Learning in Biomechanics
│   ├── research-2-1(...).htm     # Heart Function Evaluation
│   ├── research-3-1(...).htm     # Fetal Heart Echo Processing
│   ├── research-3-2(...).htm     # Virtual Reality in Fetal Echo
│   ├── research-4-1(...).htm     # Embryonic Chick Heart Biomechanics
│   ├── research-4-2(...).htm     # Zebrafish Embryonic Heart Biomechanics
│   ├── research-5(...).htm       # Blood Pump Technologies
│   └── research-7(...).htm       # Placenta Biomechanics
```
---

### 2. Storage and Organization

- **Resource separation**  
  `/Image/` stores all images, further divided by purpose (`Imperial`, `News`, `People`, `Research`).  

- **Page grouping**  
  `YapLab.htm` serves as the main landing page with navigation.  
  `/Research/` stores all detailed research subpages, each linked from the homepage.  

- **Naming convention**  
  Research pages follow `research-[block]-[sub].htm` format for clarity.  
  Images follow `block-index.png` for quick correspondence with research modules.  

---

### 3. Modules in YapLab (Main Page)

YapLab.htm is the central hub and includes:

1. **Navigation (Nav bar)**  
   - Links: Research, Code & Dataset, People, Publications, Openings  

2. **Hero Section**  
   - Lab branding and mission statement  
   - Research focus chips (Biomechanics Simulation, AI, Ultrasound, etc.)  
   - News carousel (lab highlights, awards, press releases)  
   - Metrics (Publications, Open-source codes, Patents, Students)  

3. **Research Section**  
   - High-level research blocks (Machine Learning, Echocardiography, Fetal Heart, Embryonic Heart, Blood Pump, Hemostatic Materials, Placenta)  
   - Each block has “mini cards” linking to detailed `/Research/` pages  

4. **People Section**  
   - Faculty profile (PI with photo, titles, homepage link)  
   - Lab members grid (photos, role, research focus, contact info)  

5. **Publications Section**  
   - Publications organized by year, with a dropdown for quick navigation  
   - Each item lists title, authors, journal/conference, and external link  

6. **Openings Section**  
   - Recruitment info (PhD, Postdoc, Visiting Scientist)  
   - Contact link with pre-filled email subject  

7. **Footer**  
   - Copyright notice  
   - Contact email  

---

### 4. Modules in Research Folder

The /Research/ directory includes:
- **General resources**  
  - `Code.htm` → Page for open-source code & datasets  
  - `Image/` → Figures for detailed research pages  

- **Research detail pages**  
  - `research-1-1`: Deep Learning Image Registration & Segmentation  
  - `research-1-3`: Machine Learning Biomechanics (PINN, CFD, stress analysis)  
  - `research-2-1`: Heart Function Evaluation (EF correction, 2D vs 3D strain)  
  - `research-3-1`: Fetal Heart Echocardiography Processing  
  - `research-3-2`: Virtual Reality & Simulation in Fetal Echo  
  - `research-4-1`: Chick Embryonic Heart Biomechanics  
  - `research-4-2`: Zebrafish Embryonic Heart Biomechanics  
  - `research-5`: Blood Pump with Low Blood Damage  
  - `research-7`: Placenta Biomechanics & Placental Diseases  

Research Subpage Template (e.g., research-x-x)

```bash
research-x-x(Topic).htm
│── Top Nav (Back + anchors)
│── Hero (Title + Subtitle)
│── Section #1 (Method/Module A)
│    ├── Description
│    ├── Figures + Caption
│    └── Reference + Link
│── Section #2 (Method/Module B)
│── Section #3 (Method/Module C)
│── Footer (© Lab + Contact)
```
