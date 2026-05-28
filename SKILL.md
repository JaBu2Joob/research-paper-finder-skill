---
name: research-paper-search
description: A professional skill for searching and summarizing published research papers from reputable academic databases (e.g., Google Scholar, PubMed, arXiv, Semantic Scholar, IEEE, Scopus). Use this skill to find relevant literature, extract key information, and generate study-ready outputs including Markdown summaries, BibTeX citations, and direct PDF links.
---

# Research Paper Search Skill

This skill provides a structured workflow for efficiently searching, analyzing, and extracting information from academic research papers. It focuses on retrieving published works from credible sources to support professional research and study.

## Workflow

To effectively use this skill, follow these sequential steps:

1.  **Define Search Query**: Clearly articulate the research topic, keywords, and any specific criteria (e.g., publication year, authors, journals).

2.  **Execute Search**: The skill will perform searches across multiple academic databases. Prioritize precise and concise queries for optimal results.

3.  **Review and Select Papers**: Evaluate the search results based on relevance, impact, and source credibility. Identify papers most pertinent to the research objective.

4.  **Extract Information**: For selected papers, the skill will extract key details, including abstracts, main findings, and conclusions.

5.  **Generate Output**: Produce a comprehensive output package containing:
    *   A Markdown summary of the selected papers.
    *   BibTeX citations for easy referencing.
    *   Direct links to PDF versions of the papers, where available.

## Usage Instructions

To initiate a research paper search, provide a clear and focused query. The skill will then guide you through the process of refining results and generating the desired output.

### Example Usage:

```
Search for "impact of climate change on marine biodiversity in Southeast Asia" published in the last 5 years.
```

## Bundled Resources

### `scripts/`

-   `search_papers.py`: This script will encapsulate the logic for querying various academic search engines and parsing their results. It will prioritize reliable sources and published papers.
-   `generate_summary.py`: This script will process the extracted information from selected papers to create a concise Markdown summary.
-   `generate_bibtex.py`: This script will format the citation details into BibTeX entries.

### `references/`

-   `academic_sources.md`: A reference file listing the primary academic databases and their specific search parameters or access methods.

### `templates/`

-   `summary_template.md`: A Markdown template for structuring the research paper summaries.
-   `bibtex_template.bib`: A template for generating BibTeX citations.

---

**Note**: This skill is designed to assist in academic research by streamlining the paper discovery and information extraction process. Always critically evaluate the retrieved information and cross-reference findings when necessary.
