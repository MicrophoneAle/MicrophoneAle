# Hi, I'm Michael 👋

I’m a software engineer who loves making fun apps that bridge the gap between interests and clean digital systems. Whether I'm trying to translate real-world mechanics into code, or cleaning up messy data pipelines, I thoroughly enjoy spending my free time with backend architecture, UI design and smart state management.

Right now, I'm sharpening my skills in distributed systems and prepping for Winter 2027 SWE and AI Engineering internships.

---

## 🛠️ What I’ve Been Building Recently

### 📚 Booky 
*An intelligent digital reading platform that reconstructs unstructured PDFs into typographically precise, multi-device two-page book spreads featuring full chapter navigation and custom layout controls.*
* Problem: PDF layouts are notoriously chaotic data streams. I built a multi-phase extraction pipeline using pdfjs-dist and Tesseract OCR to structuralize raw text blocks. This handles complex layout anomalies—including stripping tracking artifacts, collapsing letter-spaced running headers, and executing localized OCR on image-based chapter banner plaques.
* Testing: To ensure parser updates don't cause layout regression, I developed a node-driven automated testing harness that compares parsed node outputs against an established baseline of complex text and image-heavy documents.

### 🎹 PlayRight 
*A browser-based piano practice accelerator that parses raw MusicXML scores into interactive sheet music sheets paired with automated fingering prediction and dynamic keyboard tracking.*
* Problem: Standard sheet music lacks intuitive finger assignments. I engineered a cost-based dynamic programming solver that analyzes phrase boundaries and hand-span constraints to calculate optimal digit placements over complex chords.
* Architecture: Designed a decoupled event processing architecture using a custom InputManager. This isolates high-frequency ASCII/MIDI hardware keystrokes from the core Zustand state machine, allowing the OpenSheetMusicDisplay canvas to highlight and scroll smoothly in sync with active performance thresholds.

### ✍️ Michael's Babbles 
*A secure, interactive digital journaling space built on a layered parchment framework featuring deep rich-text formatting, search indexing, writing prompts, and real-time statistics tracking.*
* Problem: Storing rich media content directly in a document editor can create bloated payloads that strain network requests. I extended the TipTap schema to intercept image insertions, dynamically validating file sizes directly on the client side to prevent database performance degradation.
* Details: Implemented a non-blocking 10-second auto-save heartbeat loop coupled with a Prisma and PostgreSQL backend. Secured the entry lifecycle via Clerk authentication tokens to enforce read-only visibility for visitors while preserving write privileges for the owner.

---

## 🎲 Beyond the Commits

When I'm not staring at a code editor or working through LeetCode problems, you can usually find me doing a few other things:

* **Music:** I love playing instruments. I spend a lot of time on the piano (which is what inspired PlayRight as I don't have access to a physical keyboard this co-op term) and I also play the trombone. 
* **Reading:** Massive fantasy worldbuilding is my not-so-guilty pleasure. I'm a huge fan of the works of George R. R. Martin (Winds 2027??) and have recently been getting into the works of Brandon Sanderson and Pierce Brown. 
* **Sports & Travel:** I love exploring new places, and I'm a big fan of watching hockey and basketball despite having an on-and-off relationship with the Toronto Maple Leafs.
* **Board Games:** Always down for a game night, especially if it involves port play and gambling on development cards in *Catan*.

---

## 🚀 Current Technical Focus

I'm currently scaling up my knowledge to handle enterprise-level systems and expanding my creative engineering toolkit:
* Infrastructure: Diving deep into Docker and multi-container networking (docker-compose) to break heavy monolithic workflows into separate, asynchronous background workers.
* Data & AI Rigor: Building smarter systems with schema-enforced LLM parsing (getting clean JSON back from models every time) and learning the mechanics behind semantic vector search.
* Advanced Projects & 3D Assets: Expanding game engineering mechanics by building out more complex interactions in projects like Meltdown. Also learning Blender to design and render custom 3D assets to build an immersive, highly visual personal portfolio website.

---

## 🧰 My Toolkit

| Layer | Technologies & Libraries |
| :--- | :--- |
| Languages | Python, C/C++, Java, C#, SQL, TypeScript, JavaScript, HTML/CSS |
| Frontend Ecosystem | React.js (18/19), Zustand, Vite, Tailwind CSS, AngularJS |
| Specialized UI & Media | Tiptap Core (Rich-Text Engines), OpenSheetMusicDisplay (Vector Sheet Music), Tone.js (Web Audio API Engine) |
| Backend & Frameworks | Node.js, Express, .NET Core, .NET WinForm, MVC, Java Swing/AWT |
| Databases & ORMs | Supabase, PostgreSQL, Prisma ORM, MySQL, SQL Server, MongoDB |
| Auth & Infra | Clerk Auth, Git, Linux, Android Studio, VS Code |
| Cloud & Certs | AWS Certified Cloud Practitioner ☁️ |

---

## 📬 Let's Connect!

* **LinkedIn:** [linkedin.com/in/michael-liu-uw](https://www.linkedin.com/in/michael-liu-uw/)
* **Email:** [michaelliu2016@gmail.com](mailto:michaelliu2016@gmail.com)
