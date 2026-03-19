# 🎨 AI Image & Video Portfolio
### Prompt Engineering Portfolio — Ayomal Weerasinghe

> A structured showcase of AI-generated creative assets produced using **Google Imagen (ImageFX)**, **Google Flow**, and complementary tools. This repository documents not just the outputs, but the **prompt engineering methodology** behind each result — demonstrating iterative refinement, creative direction, and commercial-grade thinking.

---

## 📁 Repository Structure

```
📦 ai-image-video-portfolio
 ┣ 📂 CATEGORY 1 - Product Hero Shots
 ┣ 📂 CATEGORY 2 — Ad Creative Banners
 ┣ 📂 CATEGORY 3 — Conceptual & Illustrative
 ┣ 📂 CATEGORY 4 — AI Video Prompts (Google Flow)
 ┣ 📂 CATEGORY 5 - Iteration Methodology
 ┗ 📄 README.md
```

---

## 🧠 Prompt Engineering Methodology

The most important principle in this portfolio:

> **First outputs are starting points, not deliverables.**

Every asset in this repository went through a minimum of 3 prompt iterations before being accepted. The process follows a consistent framework:

### The 4-Stage Iteration Framework

```
STAGE 1 — Base Prompt
Define the core subject and intent. Keep it minimal.
Evaluate: Does the output understand what I'm asking?

STAGE 2 — Style & Context Layer  
Add lighting, mood, setting, camera simulation.
Evaluate: Does it feel like the right aesthetic?

STAGE 3 — Composition & Detail Control
Add negative prompts, spatial instructions, color palettes.
Evaluate: Is the composition usable for its intended format?

STAGE 4 — Commercial Refinement
Add use-case context (ad format, text overlay space, CTA zones).
Evaluate: Would this work in a live campaign without modification?
```

---

## 📋 Iteration Showcase (Category 5)

This section demonstrates the prompt engineering process from first attempt to final output. This is the core skill — not the images themselves.

---

### Example: Mobile App Lifestyle Ad

#### ❌ Version 1 — Base Prompt
```
A person using a mobile app on their phone.
```
![Generation Version 1](CATEGORY%205%20-%20Iteration%20Methodology/v1.png)

**Result:** Generic stock photo feel. Overly posed. Unusable for paid ads.
**Decision:** Rejected — restart with intent.

---

#### ⚠️ Version 2 — Style Layer Added
```
Young professional using a mobile banking app, 
lifestyle photography, natural light, authentic.
```
![Generation Version 2](CATEGORY%205%20-%20Iteration%20Methodology/v2.png)

**Result:** Improved authenticity but background too busy. 
Expression still feels staged. Depth of field too deep.
**Decision:** Rejected — add composition control.

---

#### ⚠️ Version 3 — Composition Control Added
```json
{
  "subject": "young South Asian male professional, mid-20s",
  "action": "casually checking phone",
  "setting": "modern apartment, morning",
  "lighting": "soft natural morning light from left window",
  "style": "authentic lifestyle photography, not stock",
  "negative": "no fake poses, no forced smile, no generic office"
}
```
![Generation Version 3](CATEGORY%205%20-%20Iteration%20Methodology/v3.png)

**Result:** Authentic feel, good lighting. Composition slightly off-centre.
Background competing with subject.
**Decision:** Rejected — add shallow depth of field and mood.

---

#### ✅ Version 4 — Final Commercial-Grade Prompt
```json
{
  "prompt": {
    "subject": "young South Asian male professional, mid-20s",
    "action": "casually checking phone, slight smile of satisfaction",
    "setting": "modern apartment, morning light",
    "lighting": "soft natural morning light from left window",
    "style": "authentic lifestyle photography, not stock",
    "depth_of_field": "shallow, background pleasantly blurred",
    "mood": "relieved, satisfied, seamless experience",
    "color_grade": "warm, slightly bright, optimistic",
    "composition": "subject left-aligned, negative space right for text overlay",
    "negative": "no fake poses, no forced smile, no generic office, no clutter"
  },
  "aspect_ratio": "4:5",
  "use_case": "mobile app paid social ad, Meta format"
}
```
![Final Generation Version 4](CATEGORY%205%20-%20Iteration%20Methodology/v4_final.png)

**Result:** ✅ Usable ad creative. Subject authentic, composition ad-ready,
negative space available for copy overlay. Approved.

---

## 📂 Category Breakdown

---

### CATEGORY 1 — Product Hero Shots
**Tools:** Google Imagen / ImageFX  
**Purpose:** Commercial product photography simulation for app and SaaS landing pages  
**Key techniques:** Studio lighting simulation, floating perspective, infinite background, device mockups  

| Asset | Format | Use Case |
|-------|--------|----------|
| Smartphone dashboard mockup | 16:9 | SaaS landing page hero |
| Lifestyle app usage shot | 4:5 | Meta paid social |
| Flat lay product scene | 1:1 | E-commerce ad |

---

### CATEGORY 2 — Ad Creative Banners
**Tools:** Google Imagen / ImageFX  
**Purpose:** Background assets and full ad creatives for paid social campaigns  
**Key techniques:** Gradient control, negative space for CTA placement, format-specific composition  

| Asset | Format | Use Case |
|-------|--------|----------|
| Navy-purple gradient background | 9:16 | TikTok / Reels app install ad |
| E-commerce flat lay | 1:1 | Instagram product ad |
| Abstract tech background | 16:9 | YouTube pre-roll |

---

### CATEGORY 3 — Conceptual & Illustrative
**Tools:** Google Imagen / ImageFX  
**Purpose:** Brand illustration style assets for fintech, travel, and SaaS clients  
**Key techniques:** 3D illustration simulation, cinematic colour grading, brand style matching  

| Asset | Format | Use Case |
|-------|--------|----------|
| Fintech coin illustration | 1:1 | App store feature graphic |
| Aerial beach Sri Lanka | 16:9 | Travel app hero |
| Abstract data visualisation | 1:1 | SaaS brand asset |

---

### CATEGORY 4 — AI Video Prompts (Google Flow)
**Tools:** Google Flow  
**Purpose:** Motion assets for paid video ad campaigns  
**Key techniques:** Temporal consistency, seamless loop construction, scene pacing control  

| Asset | Duration | Use Case |
|-------|----------|----------|
| Product reveal — smartphone | 6 seconds | App install video ad |
| Lifestyle loop — cafe | 3 seconds (loop) | Paid social story ad |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Google Imagen / ImageFX | Text-to-image generation |
| Google Flow | Text-to-video generation |
| Structured JSON prompting | Precision output control |
| Iterative refinement methodology | Commercial-grade quality assurance |

---

## 💡 Prompt Engineering Principles I Follow

**1. Negative prompts are as important as positive prompts.**  
Telling the model what NOT to generate is often what separates professional output from generic output.

**2. Simulate real camera equipment.**  
Specifying lens focal length, aperture, and camera model trains the model's aesthetic intuition toward photorealistic output.

**3. Name the use case in the prompt.**  
Including the intended ad format (e.g., *"Meta 9:16 story ad"*) subtly shifts composition decisions toward commercial-ready framing.

**4. Separate style from composition from mood.**  
Bundling all attributes into one sentence loses precision. Structured prompts with distinct keys give you independent control over each dimension.

**5. Document every rejection.**  
The path to the final output is the actual skill. Anyone can get lucky on attempt one. Consistent results come from a repeatable process.

---

## 📬 Contact

**Ayomal Weerasinghe**  
AI Content Creator | IT Undergraduate  
📧 pasinduayomal2001@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ayomalwee)  
💻 [GitHub](https://github.com/ayovz)

---

*All assets in this repository were generated using AI tools. This portfolio demonstrates prompt engineering skill, creative direction, and iterative methodology — not traditional graphic design.*
