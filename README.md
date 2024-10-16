# Extractive Summarization of News Articles Using Top 3 and Top 5 Sentence Scoring with Rouge Score Evaluation

This project applies extractive summarization techniques to a set of three news articles. The summarization process uses a sentence scoring approach, where the top 3 and top 5 highest-scoring sentences from each article are extracted to form the summary. The summaries are then evaluated using the Rouge Score to measure their quality by comparing them to reference summaries.

**The project includes:**

- Text Preprocessing: Tokenization and sentence splitting to prepare the news articles for summarization.
- Summarization Model: Extraction of the top 3 and 5 sentences based on scoring algorithms from each news article.
- Evaluation: The Rouge Score is used to evaluate the generated summaries in terms of recall, precision, and F1-score.
- Analysis: Detailed analysis of the performance of the summarization models using both top 3 and top 5 sentence extraction methods.

**Key Features:**

- Implementation of an extractive summarization method specifically for news articles.
- Evaluation of generated summaries using Rouge Score metrics.
- Comparison of results between top 3 and top 5 sentence extraction.
- In-depth analysis of the quality and effectiveness of the summaries.

**Technologies Used:**
- Python: For data processing and model development.
- NLTK / SpaCy: For text preprocessing and tokenization.
- Rouge Score: For summarization evaluation.
