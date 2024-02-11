# Academic Research Paper Fetcher

This Colab tool is designed to facilitate the retrieval of academic research papers from various sources, including Google Scholar, ACL, ACM, PMLR, and others. It leverages a range of APIs to fetch citations, related papers, and connected works based on specified keywords or titles.

## Features

- Fetch all citations of a single paper from Google Scholar.
- Retrieve related papers of a single paper from Google Scholar.
- Acquire all connected papers from connectedpapers.com based on similarity graphs.
- Gather relevant papers based on keywords from different sources such as ACL, ACM, PMLR, and more.

## Supported Conferences and Sources

Fetching Papers from:

| Conference Name  | Supported |
|------------------|:---------:|
| Google Scholar   | ✅        |
| ACL              | ✅        |
| PMLR             | ✅        |
| Arxiv            | ✅        |
| Semantic Scholar | ✅        |
| NeurIPS          | ✅        |
| IJCAI            | ✅        |
| openreview       | ✅        |
| thecvf           | ✅        |

## How to Use

1. Clone the repository and install the required dependencies.
2. Set the desired search term for fetching papers.
3. Execute the provided code to fetch results from Arxiv, ACM, and Semantic Scholar.
4. Review the top 10 results displayed in a formatted table within the notebook.
5. Access the full results saved as CSV files for further analysis.

### Define a search term
` search_term = 'Marketing mix models (MMMs)' `

## Executing the Tool

Ensure you're in the correct directory and then run the code cells in the provided Colab notebook. The tool will output the top 10 results from each source and save all fetched results into CSV files.

## Outputs

- Bar charts visualizing the number of results from each source.
- Pretty-formatted tables displaying the top 10 results.
- CSV files containing all fetched results for each source.

## Results

Upon running the tool, you'll get a display of the top 10 results for your search term from Arxiv, ACM, and Semantic Scholar. All results will be saved in CSV format in the `/content` directory of the Colab environment.

## Downloading Results

The CSV files with all the results can be downloaded directly from the Colab environment after the execution of the notebook.

## Project Credits

This tool is based on the project:

```plaintext
@misc{Resp2021,
  title = {RESP : Research Papers Search},
  author = {Pal, Ankit},
  year = {2021},
  howpublished = {\url{https://github.com/monk1337/resp}},
  note = {Fetch Academic Research Papers from different sources including Google Scholar, ACL, ACM, PMLR etc based on keywords or title}
}
```
