# DebateArchive

**DebateArchive** is a web app for organizing complex debates. Using a 4-tier hierarchy—Topics, Claims, Arguments, and Sources—it separates core evidence from rhetorical noise. With dynamic themes and a portable JSON backup system, it provides a clean, surgical interface for tracking the world's most critical discussions.

---

## 📋 Information Architecture
The platform enforces a rigid downstream data tree to maintain analytical clarity and prevent chaotic formatting:
1. **Topic:** High-level thematic categorization (e.g., Geopolitics, Civil Rights).
2. **Primary Claims:** High-level thesis statements isolating core points of contention.
3. **Supporting Arguments:** Rational logic structures explicitly supporting or refuting a claim.
4. **Verifiable Sources:** Unpacked raw evidence tracking back to primary publisher links or secure local documentation backups.

---

## ✨ Key Features

* **Universal Template Engine:** Runs entirely as a serverless front-end application. The browser intercepts dynamic URL parameters to seamlessly repaint a single universal template page with matching metadata and color presets.
* **Progressive Disclosure UI:** Leverages intuitive accordion micro-interactions to hide deep technical evidence layouts until requested, keeping global page density remarkably clean.
* **13 Dynamic Theme Palettes:** Dynamically translates color states across borders, badges, and background accents matching specific domains on the fly (e.g., Slate, Indigo, Purple, Teal, Emerald).
* **Sandbox Portability:** Features an auto-healing client-side JSON parsing framework. Users can securely download complete multi-topic database backups and instantly restore their workspace data in alternative browser contexts.

---

## 🛠️ Tech Stack

* **Markup:** HTML5
* **Utility Styling:** Tailwind CSS
* **Interactivity Engine:** Alpine.js
* **Deployment System:** GitHub Pages Architecture
