# CS-AI-ML Dataset - 100 Samples

**Anonymous version for NeurIPS 2026 review**

This repository contains a random sample of **100 papers** from a large-scale dataset of AI/ML conference papers.

### Dataset Description

- **Total papers in full dataset**: 20,861
- **Sample size**: 100 papers (randomly sampled with seed 42)
- **Time period**: Submissions from 2018 to 2025
- **Venues**: NeurIPS, ICLR, ICML, CVPR, ACL, EMNLP, TMLR, and others

### Data Schema

Each paper contains the following fields:

- `paper_id`: Unique identifier
- `venue`: Conference or journal name
- `title`: Paper title
- `authors`: List of authors
- `abstract`: Paper abstract
- `keywords`: List of keywords (when available)
- `full_text`: Full paper text (when available)
- `pdf_local_path`: Local path to PDF (for reference)
- `openreview_url`: Link to OpenReview page
- `reviews`: List of reviewer comments with ratings and confidence
- `author_responses`: Author rebuttals (when available)
- `editor_decision`: Final decision (Accept / Reject / etc.)
- `collected_at`: Timestamp of data collection

**Duplicates** were removed using SHA-256 content hashing of `title + abstract`.

### Usage

This sample is provided for anonymous review purposes. The full dataset will be released publicly upon acceptance.

### Citation

If you use this dataset, please cite the associated paper: (coming soon). 
