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




