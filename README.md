# Hi, I'm Michael 👋

I’m a software engineer who enjoys making apps that bridge the gap between interests and clean digital systems. Whether translating real-world mechanics into code, or cleaning up messy data pipelines, I enjoy spending my free time with backend architecture, UI design and smart state management.

---

## 🛠️ What I’ve Been Building Recently

### 📚 Booky 
> *A digital reading platform that reconstructs unstructured PDFs into typographically accurate, multi-device, two-page book spreads featuring full chapter navigation and custom layout controls.*
> 
> **Problem:** PDF layouts are extremely chaotic data streams. I built a multi-phase extraction pipeline using pdfjs-dist and Tesseract OCR to structuralize raw text blocks. This handles complex layout anomalies—including stripping tracking artifacts, collapsing letter-spaced running headers, and executing localized OCR on image-based chapter banner plaques.
> 
> **Testing:** To ensure parser updates don't cause layout regression, I developed a node-driven automated testing harness that compares parsed node outputs against an established baseline of complex text and image-heavy documents.

### 🎹 PlayRight 
> *A browser-based piano practice accelerator that parses raw MusicXML scores into interactive sheet music sheets paired with automated fingering prediction and dynamic keyboard tracking.*
> 
> **Problem:** Standard sheet music lacks intuitive finger assignments. I engineered a cost-based dynamic programming solver that analyzes phrase boundaries and hand-span constraints to calculate optimal digit placements over complex chords.
> 
> **Architecture:** Designed a decoupled event processing architecture using a custom InputManager. This isolates high-frequency ASCII/MIDI hardware keystrokes from the core Zustand state machine, allowing the OpenSheetMusicDisplay canvas to highlight and scroll smoothly in sync with active performance thresholds.

### ✍️ Michael's Babbles 
> *A secure, interactive digital journaling space built on a layered parchment framework featuring deep rich-text formatting, search indexing, writing prompts, and real-time statistics tracking.*
> 
> **Problem:** Storing rich media content directly in a document editor can create bloated payloads that strain network requests. I extended the TipTap schema to intercept image insertions, dynamically validating file sizes directly on the client side to prevent database performance degradation.
> 
> **Details:** Implemented a non-blocking 10-second auto-save heartbeat loop coupled with a Prisma and PostgreSQL backend. Secured the entry lifecycle via Clerk authentication tokens to enforce read-only visibility for visitors while preserving write privileges for the owner.

---

## 🎲 Beyond the Commits

When I'm not staring at a code editor or working through LeetCode problems, you can usually find me doing a few other things:

* **Music:** I love playing instruments. I spend a lot of time on the piano (which is what inspired PlayRight as I don't have access to a physical keyboard this co-op term) and I also play the trombone. 
* **Reading:** Massive fantasy worldbuilding is my not-so-guilty pleasure. I'm a huge fan of the works of George R. R. Martin (Winds 2027??), and have recently been getting into the works of Brandon Sanderson and Pierce Brown. 
* **Sports & Travel:** I love exploring new places, and I'm a big fan of watching hockey and basketball despite having an on-and-off relationship with the Toronto Maple Leafs.
* **Board Games:** Always down for a game night, especially if it involves port play and gambling on development cards in *Catan*.

---

## 🚀 Current Focus

I'm currently scaling up my knowledge to handle enterprise-level systems and expanding my creative engineering toolkit:
* **Infrastructure:** Diving deep into Docker and multi-container networking (docker-compose) to break heavy monolithic workflows into separate, asynchronous background workers.
* **Data & AI Rigor:** Building smarter systems with schema-enforced LLM parsing (getting clean JSON back from models every time) and learning the mechanics behind semantic vector search.
* **Advanced Projects & 3D Assets:** Expanding game engineering mechanics by building out more complex interactions in projects like Meltdown. Also learning Blender to design and render custom 3D assets to build an immersive, highly visual personal portfolio website.

---

## 🧰 Technical Skills

| Layer | Technologies & Libraries |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) |
| **Frontend Ecosystem** | ![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Zustand](https://img.shields.io/badge/Zustand-%23443E38.svg?style=for-the-badge&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![AngularJS](https://img.shields.io/badge/AngularJS-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white) |
| **Specialized UI & Media** | ![Tiptap](https://img.shields.io/badge/Tiptap-%2324292E.svg?style=for-the-badge&logo=prosemirror&logoColor=white) ![OSMD](https://img.shields.io/badge/OSMD-%23008080.svg?style=for-the-badge&logo=musicbrainz&logoColor=white) ![Tone.js](https://img.shields.io/badge/Tone.js-%23000000.svg?style=for-the-badge&logo=web-audio-api&logoColor=white) |
| **Backend & Frameworks** | ![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-%23000000.svg?style=for-the-badge&logo=express&logoColor=white) ![.NET Core](https://img.shields.io/badge/.NET%20Core-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white) ![WinForms](https://img.shields.io/badge/WinForms-%23512BD4.svg?style=for-the-badge&logo=windows&logoColor=white) ![MVC](https://img.shields.io/badge/MVC-%234D4D4D.svg?style=for-the-badge&logo=architecture&logoColor=white) ![Java Swing/AWT](https://img.shields.io/badge/Swing%20%2F%20AWT-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) |
| **Databases & ORMs** | ![Supabase](https://img.shields.io/badge/Supabase-%233ECF8E.svg?style=for-the-badge&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-%232D3748.svg?style=for-the-badge&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-%23CC292B.svg?style=for-the-badge&logo=microsoft-sql-server&clockColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white) |
| **Design & Markup** | ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) |
| **Auth & Infra** | ![Clerk](https://img.shields.io/badge/Clerk%20Auth-%236C47FF.svg?style=for-the-badge&logo=clerk&logoColor=white) ![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black) ![Android Studio](https://img.shields.io/badge/Android%20Studio-%233DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) |
| **Cloud & Certs** | ![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS%20Cloud%20Practitioner-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) |

---

## 📬 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/michael-liu-uw/)
[![Email](https://img.shields.io/badge/Email-michaelliu2016%40gmail.com-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:michaelliu2016@gmail.com)
