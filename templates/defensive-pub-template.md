# Understanding the Defensive Publication Template

This guide provides a step-by-step breakdown of every section within the `defensive-pub-template.md` file—explaining why it exists, what it does, and how to fill it out correctly.

### Overall Purpose of the File

This is a ready-to-fill Markdown template designed to be copied, customized, and published publicly (e.g., GitHub Gist, arXiv, or a personal blog). Its primary goal is to create **prior art** that prevents "patent trolls" or competitors from patenting your idea later.

> **Note:** The goal is **not** to protect your "secret sauce." Instead, it is to "burn" non-core, public-facing ideas so no one can claim exclusive ownership over them.

---

### Breakdown – Section by Section

**# Defensive Publication Template**

* **Purpose:** The document title. It ensures clarity for anyone (including patent examiners) who opens the file.

**TrollProof Playbook – Infringement Shield**

* **Purpose:** Identifies the document as part of a specific strategy and repository. This helps with branding and context when the file is forked or shared.

**Instructions for Use**

* **Purpose:** A practical "how-to" block at the top to prevent errors.
* **Key Reminders:**
* Make it **enabling** (detailed enough for a skilled person to build it).
* Only publish what you are comfortable with the world using.
* Timestamp the document immediately after publishing.



**Title: [Descriptive, specific title]**

* **Purpose:** Uses keywords to ensure search engines and patent examiners find it.
* *Bad:* "AI thing for kids"
* *Good:* "Rule-Based Adaptive Prompt Generation for Personalized Neurodivergent Education Tools"



**Publication Date: [YYYY-MM-DD]**

* **Purpose:** Records the exact date of disclosure. This is critical for establishing the timeline of prior art.

**Author(s): [Name / Pseudonym / Company]**

* **Purpose:** Optional attribution. You can use a pseudonym for privacy or a company name for professional credibility.

**Abstract / Summary (1–3 sentences)**

* **Purpose:** A high-level overview. It helps readers quickly grasp the technical disclosure without wading through the full text.

**Background / Problem Addressed**

* **Purpose:** 2–4 neutral sentences explaining **why** this method exists. This provides context without revealing trade secrets or sounding like a marketing pitch.

**Detailed Description**
This is the **heart** of the document—the technical "enabling" part that validates it as prior art.

1. **Input Data Sources:** List exactly what goes in (e.g., specific data fields or event triggers) and any light preprocessing required.
2. **Core Processing Method:** A numbered "recipe" of how it works. Be precise, but don't give away production-level secrets.
3. **Output Generation:** Describe the format and nature of the result.
4. **Pseudocode / Flow Example (Optional):** Highly recommended. Simple Python-like logic makes the disclosure 100x more "enabling" in the eyes of a patent office.
> **Pro Tip:** Use pseudocode or simplified real code—never paste production secrets or proprietary keys.


5. **Variations / Alternatives (Optional):** Listing easy tweaks broadens the disclosure, blocking others from patenting slight variations of your idea.
6. **Intended Use & Limitations:** Clarifies the scope (e.g., "for education, not medical use") to prevent misuse and narrow the legal target.

**Declaration**

* **Purpose:** An explicit statement that this is a defensive publication intended to create prior art.
> **Note:** This sentence is the most important part—keep it verbatim or very close to avoid ambiguity in intent.



**Keywords for search/discovery**

* **Purpose:** A comma-separated list of terms a troll might use when filing a similar patent. This helps the document get indexed in patent databases.

**Version / Publication Platform / URL**

* **Purpose:** Administrative tracking. Record the version number, where you posted it (e.g., GitHub Gist), and the final live link for your records.

**Tips Before Publishing**

* **Purpose:** Final reminders regarding searchability and the use of timestamping tools like [OpenTimestamps](https://opentimestamps.org).

> **Warning:** After publishing, never delete or edit the live version—changes could weaken its prior-art status or invalidate the timestamp.



---

# Defensive Publication: [Your Specific Title Here]

**Project:** TrollProof Playbook – Infringement Shield

**Document Type:** Technical Disclosure for Prior Art

---

### Instructions for Use (Delete this section before publishing)

* **Be Enabling:** Provide enough detail that a "person having ordinary skill in the art" could recreate the basic logic.
* **Publicity:** Once published, this is available for everyone. Do not include core trade secrets.
* **Integrity:** Never delete or edit the live version after publishing; changes can weaken its status.

---

**Title:** [e.g., Rule-Based Adaptive Prompt Generation for Personalized Education Tools]

**Publication Date:** [YYYY-MM-DD]

**Author(s):** [Your Name, Pseudonym, or Company Name]

**Abstract / Summary:**
[Write a 1–3 sentence summary of what this does. Focus on the technical "how" rather than the "why."]

**Background / Problem Addressed:**
[Explain the specific technical problem this solves in 2–4 sentences. Keep it factual.]

---

### Detailed Description

**1. Input Data Sources**
[List the specific data points, API triggers, or user inputs required.]

**2. Core Processing Method**
[Provide a step-by-step breakdown of the logic.]

1. [Step one...]
2. [Step two...]

**3. Output Generation**
[Describe the result of the process—data format, UI change, or triggered action.]

**4. Pseudocode / Flow Example**

> **Note:** Use pseudocode or simplified real code—never paste production secrets or proprietary keys. If you include real variable names or logic, anonymize them slightly so trolls can't later claim the prior art is invalid because you copied your own secret implementation.

```python
# Simplified logic flow
def example_logic(input_data):
    # 1. Pre-process
    # 2. Execute rule
    # 3. Return output
    pass

```

**5. Variations & Alternatives**

* [Variation A: Describe a different way to handle Step 1]
* [Variation B: Describe a different data source]

**6. Intended Use & Limitations**
[Clarify the scope, e.g., "This is for web-based orchestration, not medical hardware."]

---

### Legal Declaration

> **Important:** Publishing this does **not** create any patent rights for you — it only blocks others from patenting the disclosed idea.

**This document is a defensive publication intended to establish prior art under the laws of the United States and international patent jurisdictions. The author(s) hereby disclose this information to the public domain or under a non-exclusive license to prevent the subsequent patenting of this specific method by third parties.**

> **Note:** You may shorten this sentence slightly if needed, but **keep key phrases** like "defensive publication", "prior art", and "public domain" to avoid ambiguity in intent.

---

**Keywords:** [keyword1], [keyword2], [keyword3]

**Version:** 1.0

**Publication Platform:** [e.g., GitHub Gist / arXiv]

**URL:** [Paste link here after publishing]

---

### ⚠️ Common Mistake to Avoid

**Publishing something too vague:** If the description is not "enabling" (meaning a dev couldn't actually build it from your notes), it may not count as valid prior art in a legal challenge.

---
