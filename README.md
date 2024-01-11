# Analyzing Oil and Chemical Spill Incidents and Clustering

Oil and chemical spill incidents present substantial threats to the environment, human health, and economic stability. This project, "Analyzing Oil and Chemical Spill Incidents and Clustering," delves into the comprehensive examination of the extensive "incidents.csv" dataset. This dataset serves as a historical repository, documenting oil and chemical spills over a significant timeframe, ranging from minor localized occurrences to major environmental crises.

## Project Objective

The primary goal of this project is to extract meaningful insights from the dataset, unveiling trends and patterns inherent in these incidents. Leveraging advanced data analysis techniques and machine learning methodologies, our aim is to contribute to the development of effective prevention and response strategies. Additionally, we seek to categorize these incidents into clusters based on the severity of the damage they have caused, providing a nuanced understanding of the diverse impacts of oil and chemical spills.

## Project Phases

### 1. Data Preprocessing and Geospatial Extraction

Initiating with data preprocessing and geospatial extraction, we enhance the dataset's quality and enrich it with location-based insights. Textual preprocessing using the Natural Language Toolkit (NLTK) refines incident descriptions for subsequent analysis. Geospatial Extraction and GPT-based Text Augmentation further contribute to a comprehensive understanding of the incidents.

### 2. Feature Extraction

Feature extraction becomes a pivotal step in structuring unstructured textual data related to chemical spills. We employ OpenAI's GPT-3 model for systematic information extraction, providing structured insights into incidents, including date/time, reporting agency, incident nature, location, substances involved, safety measures, casualties, environmental impact, current status, lead agency, additional inquiries/support, and spill volume.

### 3. Text Classification

Utilizing text classification, we analyze incident descriptions categorized as 'Oil' and 'Chemical' threats. Through TF-IDF vectorization and a Multinomial Naive Bayes (NB) classification model, we achieve a refined dataset that serves as the foundation for subsequent phases.

### 4. Addressing Class Imbalance

Addressing class imbalance is crucial, and the project integrates the Synthetic Minority Over-sampling Technique (SMOTE) for data augmentation. Furthermore, GPT-3 is harnessed for text augmentation specifically focused on chemical spills, enhancing the diversity and realism of incident descriptions.

### 5. Visualizations

The project concludes with extensive visualizations, including geographical representations, temporal trends, and cluster analyses. These visualizations provide stakeholders with actionable insights into the dynamics of oil and chemical spill incidents, paving the way for informed decision-making and proactive environmental management.

## How to Contribute

If you wish to contribute to this project, please review our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We extend our gratitude to the contributors and stakeholders who have supported the development of this project.

---

Feel free to customize the sections, add relevant links, and adjust the formatting according to your preferences. Remember to include the actual details for the contribution guidelines, license, and acknowledgments.
