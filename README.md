
# Extractive Text Summarization for Romanian News

This project focuses on implementing an extractive method for text summarization, specifically tailored for a Romanian news dataset. The summarization technique is based on a graph-based approach, similar to Google's PageRank algorithm, to identify and extract the most relevant sentences from the text.

## Project Structure

- **Principal Notebook**: [`summarization_romania.ipynb`](summarization_romania.ipynb)
  - Contains the main code and implementation details of the project.
  
- **Documentation**: [`NLP_Project___News_Summarization_1.pdf`](NLP_Project___News_Summarization_1.pdf)
  - Detailed documentation covering the methodology, experiments, and results.
  
- **Presentation**: [`TEXT_SUMMARIZATION_IN_NLP.pptx`](TEXT_SUMMARIZATION_IN_NLP.pptx)
  - PowerPoint slides used for presenting the project.

## Example Graphs

- **Use Graph**: [`use_graph.png`](use_graph.png)
- **Sentence Embedding Graph**: [`se_graph.png`](se_graph.png)
  - Visual representations of the matrix used in the graph-based method for summarization.

## Generated Summaries

- **Generated Summaries CSV**: [`generated_summaries.csv`](generated_summaries.csv)
  - Contains 100 generated summaries for analysis and comparison with original summaries.

## Input Data

- **Input Data CSV**: [`input_data_ro.csv`](input_data_ro.csv)
  - Paths to all news articles in the Romanian dataset.

## Results

- **Comparison Graph**: [`comparison_graph.png`](comparison_graph.png)
  - Comparison of the generated summaries with the original summaries.
  
- **Statistics Plot**: [`statistic_plot.png`](statistic_plot.png) and [`statistics_plot.html`](statistics_plot.html)
  - Statistical analysis and visual representation of the summarization performance.

- **Graph Based Method Visualization**: [`graphbased.png`](graphbased.png)
  - Visualization of the graph-based method's working.

- **Additional Plots**: 
  - [`categories.png`](categories.png)
  - [`graphbased.png`](graphbased.png)

## Getting Started

To run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/wood11nho/extractive-text-summarization.git
    cd extractive-text-summarization
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook summarization_romania.ipynb
    ```

## Contributing

We welcome contributions to improve this project. Please fork the repository and create a pull request with your changes.

## Acknowledgements

We would like to thank all contributors and the open-source community for their invaluable support.
