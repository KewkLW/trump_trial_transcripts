# Court Case Transcripts Repository

This repository contains transcripts and evidence from court cases pulled from the [NY Courts Press](https://ww2.nycourts.gov/press/index.shtml). The repository is organized into three folders to facilitate different use cases and formats.

## Contents

### 1. PDF

This folder contains the raw transcripts directly from the court in PDF format. These documents are unmodified and can be viewed using any standard PDF reader.

### 2. Mark_down

This folder contains text files parsed from the PDFs for a more readable format. The text files are organized for ease of reading and can be used for quick reference or manual review.

### 3. JSON

This folder contains the transcripts in JSON format. This format is suitable for ease of parsing, generating analytics, or creating graphs. If you are familiar with JSON, you will find this format useful for programmatically accessing and manipulating the transcript data.

## Files

- **PDF**: Use any PDF reader to view the documents.
- **Mark_down**: Open the text files in any text editor or markdown viewer for a more readable format of the transcripts.
- **JSON**: Utilize the JSON files for programmatic access, data analysis, or visualization.
- **Gemini 1.5 Flash Summary**: https://github.com/KewkLW/trump_trial_transcripts/blob/main/trump_case_summary.md

## Tools

- **Gemini**: Over 2 million tokens were used with this system. The system prompt was:

```
You are an AI trained to read and analyze court documents. Your task is to carefully read through the provided legal text and extract the most important information. Focus on the following key points:

Case Information: Identify the case number, title, and date.
Parties Involved: List the names and roles of the parties involved (plaintiff, defendant, attorneys, judge, etc.).
Core Issues: Summarize the main issues or disputes presented in the document.
Facts of the Case: Extract and summarize the relevant facts and background information.
Legal Arguments: Identify the main legal arguments and positions of each party.
Rulings and Decisions: Highlight the court's rulings, decisions, and any orders given.
Reasoning: Summarize the reasoning and rationale behind the court's decisions.
Significant Quotes: Extract any significant quotes from the judge or legal arguments.
Outcomes and Implications: Detail the outcomes of the case and any broader implications or precedents set.
When extracting information, ensure that you preserve the original meaning and context. Provide clear, concise summaries for each key point.
```
