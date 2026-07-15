# Hi, I'm Michael 👋

I’m a software engineer who enjoys making things that bridge the gap between passions and clean digital systems. Whether translating real-world mechanics into code, or cleaning up messy data pipelines, I enjoy spending my free time with backend architecture, UI design and smart state management.

Right now, I'm working on several side projects that align with my personal interests as well as improving my knowledge of distributed systems, delving into schema-enforced LLM pipelines and mastering Blender to build an immersive 3D personal website.

---

## 🧰 Technical Skills

| Layer | Technologies & Libraries |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white) |
| **Frontend Ecosystem** | ![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Zustand](https://img.shields.io/badge/Zustand-%23443E38.svg?style=for-the-badge&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![AngularJS](https://img.shields.io/badge/AngularJS-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white) |
| **Specialized UI & Media** | ![Tiptap](https://img.shields.io/badge/Tiptap-%2324292E.svg?style=for-the-badge&logo=prosemirror&logoColor=white) ![OSMD](https://img.shields.io/badge/OSMD-%23008080.svg?style=for-the-badge&logo=musicbrainz&logoColor=white) ![Tone.js](https://img.shields.io/badge/Tone.js-%23000000.svg?style=for-the-badge&logo=web-audio-api&logoColor=white) |
| **Backend & Frameworks** | ![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-%23000000.svg?style=for-the-badge&logo=express&logoColor=white) ![.NET Core](https://img.shields.io/badge/.NET%20Core-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white) ![MVC](https://img.shields.io/badge/MVC-%234D4D4D.svg?style=for-the-badge&logo=architecture&logoColor=white) ![WinForms](https://img.shields.io/badge/WinForms-%23512BD4.svg?style=for-the-badge&logo=windows&logoColor=white) ![Java Swing/AWT](https://img.shields.io/badge/Swing%20%2F%20AWT-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) |
| **Databases & ORMs** | ![Supabase](https://img.shields.io/badge/Supabase-%233ECF8E.svg?style=for-the-badge&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-%232D3748.svg?style=for-the-badge&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-%23CC292B.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white) |
| **Design & Markup** | ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) |
| **Auth & Infra** | ![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black) ![Clerk](https://img.shields.io/badge/Clerk%20Auth-%236C47FF.svg?style=for-the-badge&logo=clerk&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android%20Studio-%233DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white) |
| **Cloud & Certs** | ![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS%20Cloud%20Practitioner-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) |

---

## 🛠️ What I’ve Been Building Recently

### 🎹 PlayRight 
> *A browser-based piano practice accelerator that orchestrates real-time computer keyboard and MIDI performance tracking over a dynamically rendered sheet music display.*
> 
> **Problem:** Converting raw sheet music file formats into a reactive learning platform requires extreme timing and state synchronization. I built a custom `MusicXML/MXL` ingestion pipeline using `fast-xml-parser` and `Zod` to compile musical scores into a strict step-by-step chord execution script. To automate guidance, I designed an ergonomic hand-span predictor using a cost-based Dynamic Programming solver as well as training the integrated ML model on a dataset of piano fingerings.
> 
> **Core Mechanics & Performance:** Engineered a decoupled `InputManager` to map keyboard shortcuts and sliding 17-to-21-note core scopes directly into a global `Zustand` engine state. Features include an interactive **Program Mode** for step-by-step cross-hand fingering overrides, a high-performance rolling-window **Play Mode** utilizing `Tone.js` transport scheduling with incremental canvas diffing (`OpenSheetMusicDisplay`), and a secure `Clerk` and `Supabase` personal library backend.

### 📚 Booky 
> *An intelligent web reader that structuralizes unstructured PDFs into comfortable, highly custom digital layouts featuring dynamic chapter detection, live parsing progress tracking, and secure cloud storage.*
> 
> **Problem:** Raw PDF data is a generally chaotic stream of unmapped text fragments and vector shapes. I engineered a multi-stage server-side parsing engine (`Express 5` + `pdfjs-dist`) that maps pages into logical content blocks (headings, prose, images). The pipeline runs concurrent worker routines to extract artwork and triggers `Tesseract.js` OCR to read context-dependent chapter banners and images.
> 
> **Architecture & Testing:** Designed a strict state-versioning system (`PARSER_VERSION`) that triggers automated cache invalidation and document re-parsing across a `Supabase` storage layer. To prevent layout or structural regressions during updates, I built a custom test harness to validate code outputs against snapshots of massive text-heavy and illustration-heavy books.

### ✍️ Michael's Babbles 
> *A secure, interactive digital journaling space built on a layered parchment framework featuring deep rich-text formatting, search indexing, writing prompts, and real-time statistics tracking.*
> 
> **Problem:** Storing rich media content directly in a document editor can create bloated payloads that strain network requests. I extended the TipTap schema to intercept image insertions, dynamically validating file sizes directly on the client side to prevent database performance degradation.
> 
> **Details:** Implemented a non-blocking 10-second auto-save heartbeat loop coupled with a Prisma and PostgreSQL backend. Secured the entry lifecycle via Clerk authentication tokens to enforce read-only visibility for visitors while preserving write privileges for the owner.

---

## 🎲 Beyond the Commits

When I'm not staring at a terminal or working through LeetCode problems, you can usually find me doing a few other things:

* **Music:** I love playing instruments. I spend a lot of time on the piano (which is what inspired PlayRight as I don't have access to a physical keyboard this co-op term) and I also play the trombone in several ensembles. 
* **Reading:** Massive fantasy worldbuilding is my not-so-guilty pleasure. I'm a huge fan of the works of George R. R. Martin (Winds 2027??), and have recently been getting into the works of Brandon Sanderson and Pierce Brown. 
* **Sports & Travel:** I love exploring new places, and I'm a big fan of watching hockey and basketball despite having an on-and-off relationship with the Toronto Maple Leafs.
* **Board Games:** Always down for a game night, especially if it involves port play and gambling on development cards in *Catan*.

---

## 🚀 Current Focus

I'm currently scaling up my knowledge to handle enterprise-level systems and expanding my creative engineering toolkit:
* **Infrastructure:** Diving deep into Docker and multi-container networking to break heavy monolithic workflows into separate, asynchronous background workers.
* **Data & AI Rigor:** Building smarter systems with schema-enforced LLM parsing (getting clean JSON back from models every time) and learning the mechanics behind semantic vector search.
* **Future Projects & 3D Assets:** Expanding game engineering mechanics by building out more complex interactions in projects like Meltdown. Also learning Blender to design and render custom 3D assets to build an immersive, highly visual personal portfolio website.

---

## 📬 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/michael-liu-uw/)
[![Email](https://img.shields.io/badge/Email-michaelliu2016%40gmail.com-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:michaelliu2016@gmail.com)
