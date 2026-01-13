I want you to rewrite this email in a friendly and professional tone

Let me know if you also want:

I definitely, want 
A version that splits this task into steps or batches for long uploads.


Now I want separately A version optimized for LaTeX output only.

also separately An extended prompt that includes a reference management system or citation extraction.

Finally, I want separately An extended prompt that splits this task into steps or batches for long uploads, by converting all ris files into bib ones. Then I will upload all the bib files, and will make one bib file with all the references. 



You are a reference management assistant. Your task is to merge multiple `.bib` files into a **single, clean, and deduplicated BibTeX file** for use in a scientific manuscript submission.

**Instructions:**

1. I will upload more than 10 `.bib` files in separate batches due to size limits.
2. For each uploaded file:
   - Parse all BibTeX entries.
   - Validate the format of each entry (`@article`, `@book`, etc.).
   - Normalize citation keys (e.g., use `AuthorYear` format if missing or inconsistent).
   - Detect and remove duplicate entries based on DOI, title, or exact metadata match.

3. After all files are uploaded:
   - Output the **merged BibTeX file**, including only **unique, well-formatted entries**.
   - Sort the entries alphabetically by citation key.

4. The final `.bib` file should be ready to use with LaTeX or Markdown + Pandoc workflows.

Wait for my signal when all `.bib` files are uploaded. Do not output the final file until I say: **"Merge and finalize the BibTeX file."**

```text
ASSET REGISTRY
├── Figures
│   ├── System block diagrams
│   ├── Antenna geometries
│   ├── Radiation patterns
│   ├── SNR / BER / Throughput plots
│   └── Comparative performance charts
├── Tables
│   ├── Simulation parameters
│   ├── Comparative benchmarks
│   └── Performance summaries
└── Equations
    ├── System models
    ├── Antenna equations
    ├── Channel models
    └── Performance metrics

```




I want you to write a prompt to read a draft of a structure of a research article. Then it will expand it with integrations of design equations, techniques and diagrams, design algorithms, and what adaptations are adopted in the basic papers. Also whatever will put inside the structure, it must answer the questions inside.



Perfect — here's the refined version of the prompt, tailored for **electrical engineering** research article development:

---                                                                   

### ✅ Electrical Engineering Research Article Expansion Prompt:

**"You are a technical research assistant specialized in electrical engineering. Your task is to expand a provided draft structure of a research article into a complete, technically rigorous paper. Follow these instructions:**

1. **Analyze the draft structure** (headings, subheadings, notes) and expand each section using accurate and relevant content from the field of electrical engineering.
2. **Integrate appropriate design equations, theoretical models, system or block diagrams, circuit schematics, and relevant algorithms** where applicable.
3. **Incorporate techniques and methodologies** that are standard or innovative within the domain (e.g., power systems, embedded systems, RF design, control systems, signal processing — depending on context).
4. **Reference foundational research papers or standards** and explain what adaptations or improvements are applied in the current work. Clearly indicate how this research builds upon or deviates from existing approaches.
5. Ensure that all inserted technical content is **directly tied to the core research questions or objectives**, effectively contributing toward answering them.
6. Use precise academic and engineering terminology, and maintain a logical, publication-ready structure."

**You will receive:**

* A rough outline or structure of the article.
* The main research questions or design objectives.
* (Optional) Reference papers or standards to base the work on.

**Your output should be:**

* A fully developed research article draft (or a significantly expanded structure), complete with equations, figures, technical explanations, and clear responses to the posed research questions."

---

### 💡 Tips When Using This Prompt:

You should pair this prompt with:

* A draft structure like:

  * Abstract
  * Introduction
  * Problem Statement
  * Proposed Methodology
  * Design and Implementation
  * Results and Analysis
  * Conclusion
* A list of research questions (e.g., “How can power efficiency be improved in low-voltage inverters?”)
* A list of reference papers (if available)

---

Would you like me to show how this prompt would be applied to an actual draft structure?








Excellent clarification — you're asking for a **prompt that expands a research paper strictly within its given structure**, while integrating technical content (equations, diagrams, methods, etc.) **without altering or deviating from the original section layout**.

Here is your optimized prompt:

---

### ✅ Final Prompt: Electrical Engineering Paper Expansion (Structure-Preserved)

**"You are a research article assistant specializing in electrical engineering. Your task is to expand a provided research paper draft into a complete technical paper.**
**You must strictly follow the given structure and headings — do not change or add new sections.**

For each section:

1. **Expand the content using accurate, relevant electrical engineering knowledge**, based on the context of the section.
2. **Integrate technical elements** such as:

   * Design equations and mathematical models
   * Circuit schematics or system diagrams
   * Design techniques, simulations, or test setups
   * Algorithms or pseudocode if applicable
3. **Incorporate adaptations or improvements from foundational or cited papers**, showing how the current work builds upon or differentiates from them.
4. **Ensure all inserted content contributes to answering the research questions or achieving the design objectives**.
5. **Use clear academic writing**, suitable for a peer-reviewed journal in electrical engineering.

You will receive:

* A draft paper structure with section headings and notes (can be partial sentences, bullet points, or placeholders).
* A list of research questions or goals.
* (Optional) References to base papers.

Your output should:

* Keep the exact structure and headings provided.
* Fill in each section with logically coherent, technically valid, and publication-quality content."**

---

### ✅ Why This Works:

* Explicitly enforces *structure preservation*.
* Prioritizes *technical expansion* over rewriting.
* Aligns inserted content with *research objectives*.
* Encourages *integration from base literature*.

---

If you're ready to apply it, feel free to paste your **draft structure + research questions**, and I’ll show you a real output using this prompt.









Thanks — I’ve reviewed your research article draft:
**“Advances in Antenna Design for 5G/6G Vehicular Communications: A Critical Overview and Systematic Review.”**
Based on your request to build a **prompt that reads and expands this structure while preserving it**, here is the final tailored prompt you can use with ChatGPT or any LLM:

---

### ✅ Final Prompt — Structure-Preserved Research Article Expansion (Electrical Engineering | Antenna Design)

**"You are a technical writing assistant with expertise in electrical engineering, specifically in advanced antenna design for 5G/6G vehicular communications. Your task is to expand the provided structured draft of a research article into a complete, publication-ready paper.**

**Follow these strict instructions:**

1. **Preserve and follow the exact section structure and headings as provided.** Do not alter or rearrange them.
2. For each section:

   * Expand the content using domain-specific knowledge in electrical engineering.
   * Integrate relevant technical elements such as:

     * Design equations (e.g., ECC, S-parameters, beamforming models)
     * Antenna performance metrics (gain, isolation, bandwidth, efficiency, etc.)
     * System diagrams, schematics, or figures if described
     * Design techniques (e.g., metamaterials, decoupling structures, FSS, DGS)
     * Algorithms or methods when relevant (e.g., for beam steering, MIMO optimization)
3. Use insights from foundational and referenced papers to:

   * Support each antenna type discussion
   * Show what design adaptations were made for vehicular scenarios
   * Highlight what prior reviews missed or treated superficially
4. **Ensure that each expanded section helps directly answer the research questions** in the paper (e.g., which antennas are suitable for vehicular 5G/6G? How are designs adapted to mobility, Doppler shift, or integration constraints?).
5. Maintain professional academic tone, logical flow, and technical accuracy suitable for peer-reviewed publication in an MDPI journal.

**Input to be provided:**

* A structured draft paper with headings and bullet points, notes, or partial sections (already provided).
* Any core research questions or design goals (already embedded in the introduction and framework).

**Your output:**

* A fully expanded research article draft.
* Each section must be technically detailed and aligned with both the structure and the research objectives."**

---

### 🧪 Example Use Case:

Paste your structured document (like the one you uploaded), and run it with this prompt. The model will:

* Respect the original headings like “MIMO Antennas”, “Phased Arrays”, etc.
* Expand only within each section
* Insert equations like `C = B log₂(1 + SNR/m)` and other domain-relevant formulas
* Address vehicular-specific needs (e.g., Doppler shift, integration challenges)
* Discuss and contrast with prior reviews and standards

---

Would you like a demonstration of how this prompt expands a specific section of your uploaded draft? For example: I could expand the "Patch Antennas" section into full detail. Just say the word.
