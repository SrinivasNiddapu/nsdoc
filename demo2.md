Can you be visual web designer to Build my personal one-page website? 

Objective - Can you gather all relevinet information on "Srinivas Niddapu" who is the Cloud Architect in AxiomIO, Who is Sr. CloudOps Lead in Ascentt., 
(Active Search)
Audiance - Recruiter and human source. 

I need you Sleek, Modern, White space heavy, Swis design,

Get inspiration from 21st.dev component Library to get you building blocks for all the sections. 

==>

Now I am using lovable.dev. I need a single prompt covering all the sections you have outlines with the microcopy, UI components, integrations, interactions, special validation In a single markdown code block format. 

o/p ==>

# Context
You are a UI/UX + frontend engineer using Lovable.dev.  
Target audience: recruiters and HR.

# Task
Build a **one-page portfolio website** for **Srinivas Niddapu**, Sr CloudOps Lead @ Ascentt & ex–Cloud Architect @ Axiom IO.

The design must be **sleek, whitespace-rich, Swiss‑clean**, using Swiss typography and a neutral palette (white, light gray backgrounds, charcoal text, blue accents). Include layout elements inspired by 21st.dev.

# Structure & Sections

1. **Header / Hero**
   - **Full-width section** with subtle cloud-tech background (light abstract graphic).
   - Overlaid content (centered vertically & horizontally):
     - H1: `Srinivas Niddapu`
     - H2: `Sr. CloudOps Lead @ Ascentt · ex‑Cloud‑Architect @ Axiom IO`
     - CTA button: `Download Résumé` → scrolls to Contact.

2. **About**
   - Two columns:
     - Left: placeholder for profile photo (circle), alt text "Srinivas portrait".
     - Right: a bio paragraph (~50 words):
       > “I’m a seasoned cloud architect and operations leader specializing in AWS/Azure/GCP, CI/CD, automation, and resilient systems. I lead cloud transformations, optimize pipelines, and drive best practices to deliver scalable and secure infrastructures.”

3. **Experience Timeline**
   - Horizontal timeline with two cards:
     - **Ascentt (Oct 2023–Present)**: bullet points:
       - Lead CloudOps transformation, optimized CI/CD pipelines, improved system resilience.
     - **Axiom IO (Oct 2011–Sep 2023)**: bullet points:
       - Architected multi‑cloud solutions, led migration, implemented DevOps standards.
   - Timeline visually connected by a central line and round nodes.

4. **Core Skills**
   - Grid of skill tags (clean pills or icons + labels): AWS, Azure, GCP, Docker/K8s, Terraform, CI/CD, Monitoring, Security.
   - Uniform style, hover effect (background → accent blue, text white).

5. **Featured Projects**
   - Horizontal scrollable cards (or grid on desktop) with placeholders:
     - Title, 1‑line description, “View details” link (non‑functional placeholder).
   - Example placeholder:
     - *Multi‑Region Resiliency – Designed a cross‑region AWS architecture with failover mechanisms.*

6. **Education & Certifications**
   - List style:
     - **Sikkim Manipal University** – [Degree], distance education.
     - Include bullet list of cloud certification placeholders (e.g. AWS Certified Solutions Architect, Azure Fundamentals).

7. **Contact**
   - CTA section with text:
     > “Interested in cloud architecture leadership or operations excellence? Let’s connect.”
   - Form: Email Input (validated for proper email), Name Input (required), Message textarea (optional).
   - Submit button: “Send message”. Use form validation:
     - Email must be valid.
     - Name required.
     - On submit, show success banner: “Thanks! I’ll be in touch shortly.”
   - Also include direct link/button: “Download Résumé” and LinkedIn icon/button linking to profile.

# Styling Guidelines
- Use neutral color variables: `--bg: #fff`, `--bg-light: #f7f7f7`, `--text: #333`, `--accent: #006DF0`.
- Typography: Helvetica Neue or similar, with clear hierarchy and spacing.
- Components: use 21st.dev-style blocks—cards with subtle shadows, consistent gutters, modular design patterns.

# Interactions & Responsive
- Smooth scrolling for all internal links.
- Hero CTA and Contact download button anchor scroll.
- Timeline and Projects scroll horizontally on mobile.
- Button hovers: slight elevation, accent background on hover.

# Integrations
- Resume download should link to a hosted PDF (use placeholder URL).
- Form submission: stubbed endpoint (`/api/contact`)—validation in frontend, console.log submit.

# Constraints
- Single page; no multi-page navigation.
- No paid APIs.
- Keep the visual tone minimal, whitespace focused.
- Responsive from mobile (min 320px) through desktop.

Please generate Lovable.dev UI + layout scaffold code (React + Tailwind if convenient), with component definitions, placeholder assets/URLs, form validation logic, and smooth scroll behavior.

==>

Fine tunning step

Do you think you would like to add anything? you can ask me questions?

==>

I really like all your ideas. Prepare the final prompt that I can copy-paste. 

o/p ==>

# 📘 Custom Knowledge (add this to your Lovable project’s Knowledge File)
Vision & Goals: Build a sleek, Swiss‑clean one‑page portfolio for recruiters and HR.  
Audience: Technical recruiters and hiring managers.  
Tech Stack: React + Tailwind CSS (+ Lovable). No paid APIs; form stub via /api/contact; resume hosted PDF.  
Design System:
- Colors: --bg: #fff, --bg-light: #f7f7f7, --text: #333, --accent: #006DF0
- Typography: Helvetica Neue or similar, modular grid layout
- Components inspired by 21st.dev; use Magic MCP via `/ui`
Rules:
- Mobile‑first responsive (tailwind breakpoints sm, md, lg, xl)
- Whitespace‑rich, Swiss‑typography, minimal disclosures
- Always ask before major refactors :contentReference[oaicite:6]{index=6}

---

# 🚀 Prompt: Build Section‑By‑Section

## 1. Hero & Navigation
/ui create a responsive full‑width Hero section:
- Background: light abstract cloud‑tech graphic, subtle overlay
- Centered content: 
  • H1 “Srinivas Niddapu”  
  • H2 “Sr CloudOps Lead @ Ascentt · ex‑Cloud Architect @ Axiom IO”  
  • Buttons: [Download Résumé] and smooth-scroll down icon
- Navigation: fixed top, smooth‑scroll links to each section
- Typography: Swiss‑clean, ample whitespace, accent button hover styles

## 2. About Section
/ui create two‑column About block:
- Left: circular placeholder avatar
- Right: Bio text:
  “I’m a seasoned cloud architect and operations leader specializing in AWS/Azure/GCP, CI/CD, automation, and resilient systems. I lead cloud transformations, optimize pipelines, and drive best practices to deliver scalable and secure infrastructures.”
- Grid adjusts to single column on mobile

## 3. Experience Timeline
/ui create horizontal timeline component:
- Two cards on a central line with round nodes:
  1. Ascentt (Oct 2023–Present): “Lead CloudOps transformation, optimized CI/CD pipelines, improved system resilience.”
  2. Axiom IO (Oct 2011–Sep 2023): “Architected multi‑cloud solutions, led migration, implemented DevOps standards.”
- Responsive: horizontal scroll on mobile

## 4. Core Skills
/ui create pill‑style grid with hover states:
- Tags: AWS, Azure, GCP, Docker/Kubernetes, Terraform, CI/CD, Monitoring, Security
- On hover: bg accent blue, text white, smooth transition

## 5. Featured Projects
/ui create horizontal scrollable cards:
- Example placeholder card: Title “Multi‑Region Resiliency”, Description “Designed a cross‑region AWS architecture with failover mechanisms.”, link text “View details →”
- Desktop layout: grid; mobile: scroll
- Use consistent card shadows and spacing

## 6. Education & Certifications
/ui create list component:
- List items:
  - **Sikkim Manipal University** – [Degree, Distance Education]
  - Placeholder: “AWS Certified Solutions Architect”  
  - Placeholder: “Azure Fundamentals”
  - Placeholder: “GCP Professional Cloud Architect”

## 7. Contact & Footer
/ui create a Contact form section:
- Hero microcopy: “Interested in cloud architecture leadership or operations excellence? Let’s connect.”
- Form: Name (required), Email (validated), Message (optional)
- Submit button “Send message”; on success show banner “Thanks! I’ll be in touch shortly.”
- Also display: [Download Résumé] button and LinkedIn icon linking to profile
- Validate email format, name non‑empty

---

# 💡 Final Touch & Responsiveness
- Add smooth‑scroll behavior for all internal links
- Use Tailwind breakpoints (mobile‑first): sections stack/scroll gracefully
- Buttons: accent bg hover, slight elevation
- Forms: client‑side validation; stub submit to /api/contact
- Resume button uses your hosted PDF URL placeholder
- Ask before large refactors; keep files <300 lines :contentReference[oaicite:7]{index=7}

---

## ✅ Instruction to Lovable.dev
Start with React + Tailwind initialization. Then phased:
1. Build Hero & Nav
2. Add About
3. Timeline
4. Skills
5. Projects
6. Education & Contact

Generate code incrementally. Confirm each section before proceeding. Don’t refactor unrelated parts. Ensure code consistency and responsive behavior. Once all sections built, finalize with accessibility checks (aria-labels, keyboard focus) and mobile‑first polish.

Please acknowledge before starting with Hero & Nav.

==>



