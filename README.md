# ResumeIQ: AI-Powered Resume Understanding & Q&A

## Project Overview

**ResumeIQ** is an AI-driven tool that extracts structured, recruiter-ready information from multi-page resumes using state-of-the-art Large Language Models (LLMs). It enables automated question answering over resumes, providing concise answers to queries such as **skills**, **education**, **experience**, **programming languages**, and **location**.

By combining text preprocessing, intelligent chunking, and LLM reasoning, ResumeIQ demonstrates practical AI applications in **document understanding, natural language reasoning, and HR automation**.

## Key Features

* **PDF and text resume support:** Seamlessly load resumes from PDFs or plain text.
* **Text cleaning & preprocessing:** Removes formatting artifacts, bullet points, and special characters for optimal model performance.
* **Chunking for large documents:** Splits resumes into manageable segments for LLM processing.
* **Targeted Q&A:** Ask any question about the candidate and receive concise, context-aware answers.
* **Recruiter-ready output:** Structured and easily interpretable summaries for faster decision-making.


## Why LLMs Are Used

* **Context-aware reasoning:** Can understand multi-sentence and multi-page context beyond keyword matching.
* **Flexible querying:** Supports structured and unstructured questions about a candidate’s profile.
* **Concise summarization:** Extracts essential information without requiring manual parsing or templates.


## Notes

* **Chunking is critical:** Helps LLMs process long resumes without truncation.
* **LLM selection matters:** Larger models like `flan-t5-large` or `flan-ul2` improve accuracy and context understanding.
* **Structured extraction:** Ideal for recruiters or HR systems, and can be extended to output JSON or Excel-ready formats.


## Future Improvements

* Implement **document layout understanding** (tables, bullets, sections) for even cleaner extraction.
* Fine-tune models specifically on resumes for higher precision.
* Integrate with HR systems to automate candidate shortlisting.
