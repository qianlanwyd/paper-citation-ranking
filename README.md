# Conference Citation Ranking

This repository provides a tool for ranking the citations of individual papers presented at various AI top-tier conferences such as NeurIPS (NIPS), ICML, and others. The aim of this project is to provide insights into the citation performance of papers within a specific conference, helping researchers and institutions assess the impact of individual works.

## Features
- **Citation Ranking**: Displays citation counts for papers and their ranks within the conference.
- **Percentile Analysis**: Highlights the percentile a paper belongs to within the citation distribution of the conference.
- **Data for Top Conferences**: Covers major AI conferences, including NeurIPS and ICML.
- **Date of Analysis**: Provides the date of the citation data, ensuring up-to-date ranking information.

## Data Format
The data is presented in JSON format, with each entry representing a paper's citation statistics. Below is an example and the explanation of each field:

```json
{
    "title": "Characteristics of Harmful Text: Towards Rigorous Benchmarking of Language Models",
    "citations": 48,
    "rank": "39 out of 127",
    "percentile": "top 30%",
    "date": "2024-12-19"
}
```

### Field Descriptions
- **`title`**: The title of the paper.
  - Example: "Characteristics of Harmful Text: Towards Rigorous Benchmarking of Language Models"
- **`citations`**: The number of citations the paper has received as of the specified date.
  - Example: 48
- **`rank`**: The paper's rank among all papers from the same conference in terms of citation count.
  - Example: "39 out of 127" indicates this paper is the 39th most cited out of 127 papers.
- **`percentile`**: The citation percentile, showing the relative citation performance within the conference.
  - Example: "top 30%" means the paper is in the top 30% most cited papers.
- **`date`**: The date when the citation data was last updated.
  - Example: "2024-12-19"

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/conference-citation-ranking.git
   ```
2. Load the JSON data file containing citation rankings for a specific conference.

## Contributing
Contributions are welcome! If you have suggestions for improving the tool, additional features, or data sources, feel free to open an issue or submit a pull request.

## Updates
We are committed to keeping this repository up-to-date. Citation data will be regularly refreshed to ensure the rankings remain accurate and relevant.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

