# LLMTemporalComparator: A Tool for Analysing Differences in Large Language Models’ Knowledge over Time

**LLMTemporalComparator** is a cutting-edge tool designed to help researchers, policymakers, and businesses analyze and compare machine learning models trained on data from different time periods. It automates the exploration of temporal differences in model outputs, providing valuable insights into how perceptions, narratives, and societal attitudes evolve over time.

## Key Features

- **Automated Hierarchical Topic Generation**: The system dynamically creates a hierarchical topic structure based on user queries.
- **LLM-based Text Comparison**: Uses LLMs like SBERT and LLM Comparator to automatically compare outputs from two models, identifying differences in vocabulary, facts, and themes.
- **Customization Options**: Users can specify query depth, threshold for detecting differences, and comparison methods.
- **Temporal Analysis**: Designed to reveal shifts in public opinion, media framing, and societal values across time periods.
- **Visualization**: Outputs can be visualized in a tree structure or a treemap, highlighting categories with significant differences.

## Use Cases

This tool can be used in several areas, including:

1. **Public Opinion Analysis**: Track how societal attitudes change over time by comparing model outputs trained on historical and contemporary data.
2. **Media Framing Studies**: Investigate how media framing of topics evolves across different periods.
3. **Historical Text Comparison**: Compare thematic differences in text generated from various historical periods.
4. **Research in Continual Model Adaptation**: Study how machine learning models adapt to new data over time.

## How to Use It

1. **Setting Up Models**: Provide two machine learning models trained on different time periods.
2. **Defining the Query**: Specify a root keyword for the topic of interest (e.g., "social media").
3. **Configuring Parameters**:
   - Choose the depth of the hierarchy.
   - Define thresholds for detecting differences.
   - Select comparison methods (e.g., SBERT, LLM Comparator).
4. **Running the Algorithm**:
   - The system will generate hierarchical categories and compare text outputs from the two models.
5. **Reviewing Results**:
   - Explore the differences through the provided visualization tools (tree structure or treemap).
6. **Interpreting Differences**: Understand shifts in trends, language, and framing based on the comparison output.


## Citation
### Bibtex
```bibtex
@article{fritsch2024LLMTemporalComparator,
  title={LLMTemporalComparator: A Tool for Analysing Differences in Large Language Models’ Knowledge over Time},
  author={Fritsch, Reinhard and Jatowt, Adam},
  journal={},
  year={2024}
}
```

## Acknowledgments
Thanks to our contributors and the University of Innsbruck for supporting this project.