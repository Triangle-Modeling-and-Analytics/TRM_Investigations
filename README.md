# TRM_Investigations

Data visualizations and other products associated with Triangle Regional Model (TRM) investigations.

## About

The Triangle Regional Model (TRM) is the travel demand model for the Triangle region of North Carolina. It is used to forecast travel patterns and support transportation planning decisions across the region.

This repository collects the visualizations, analyses, and supporting materials produced while conducting TRM investigations. Investigations can take the form of model enhancements, systematic reviews, anomaly resolution, and more.

## Purpose

The goal of this repository is to provide a central, version-controlled home for:

- Charts, maps, and other visualizations derived from TRM data
- Scripts and notebooks used to generate those products
- Documentation describing the methods and findings behind each investigation

By keeping these products together, the work remains transparent, reproducible, and easy to share.

## Repository Structure

The repository is organized by investigation. A typical layout looks like:

```
TRM_Investigations/
├── <investigation_name>/
│   ├── data/          # Input data or references to source data
│   ├── scripts/       # Code used to process data and build outputs
│   ├── outputs/       # Generated visualizations and products
│   └── README.md      # Notes specific to this investigation
└── README.md          # This file
```

Individual investigation folders may vary depending on their scope and needs.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<owner>/TRM_Investigations.git
   cd TRM_Investigations
   ```
2. Navigate to the investigation of interest and review its README for specific instructions.
3. Install any dependencies noted in that investigation before running its scripts or notebooks.

## Data Notes

Some TRM data may be large or subject to distribution restrictions. Where data cannot be committed directly, the relevant investigation folder should document where and how to obtain the source data.

## Contributing

Contributions and additional investigations are welcome. When adding new work:

- Create a dedicated folder for each investigation.
- Include a short README describing the question, method, and key findings.
- Keep generated outputs separate from the code that produces them.

## Contact

For questions about the Triangle Regional Model or the contents of this repository, please open an issue or reach out to the repository maintainers. 

