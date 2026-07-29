# Figures

This directory contains the visual evidence supporting the three case studies.

## Figure List

| Figure | File | Description | Source Case Study |
|--------|------|-------------|-------------------|
| **Figure 1** | `figure-01-relevance-scores.png` | Overall relevance scores by evaluated advertisement (bar chart) | Case Study 01 |
| **Figure 2** | `figure-02-quality-diagnostic.png` | Quality Score component diagnostic for AG-01 (horizontal bar chart) | Case Study 02 |
| **Figure 3** | `figure-03-search-volume-share.png` | Share of search volume by intent stage (bar chart) | Case Study 03 |

## How to Generate These Figures

The original figures were created in the author's academic paper (see `../paper.pdf`). To extract them for this repository:

1. Open `paper.pdf` in any PDF viewer
2. Navigate to the figure pages (pages 8, 10, 12)
3. Use your PDF viewer's "Export Image" or screenshot function
4. Save as PNG with the filenames listed above

Alternatively, the data underlying each figure is fully documented in the corresponding case study markdown file and can be recreated in any charting tool (Excel, Google Sheets, Python matplotlib, R ggplot2, etc.).

## Figure 1 Data

| Advertiser | Query | Score | Category |
|-----------|-------|-------|----------|
| HubSpot CRM | affordable CRM... | 9.4 | High |
| Salesforce | affordable CRM... | 5.8 | Medium |
| bestbusinesstools.net | affordable CRM... | 3.0 | Low |
| Babbel | online Spanish... | 9.3 | High |
| spanishschool.edu | online Spanish... | 6.1 | Medium |

## Figure 2 Data

| Component | Rating |
|-----------|--------|
| Ad Relevance | Above Average |
| Expected CTR | Above Average |
| Landing Page Experience | Average |

## Figure 3 Data

| Intent Stage | Share of Search Volume |
|-------------|----------------------|
| Informational | 100% |
| Commercial | 72% |
| Transactional | 44% |
| Navigational | 18% |

---

*[← Back to main README](../README.md)*
