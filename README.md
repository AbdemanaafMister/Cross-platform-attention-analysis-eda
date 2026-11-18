# Attention, Virality, and Digital Culture

## Project Overview

How does attention move across major social media platforms, and what patterns seem to support virality?

This project explores social media engagement, digital attention, sentiment, and virality across six major platforms: **Twitter (X), Reddit, Instagram, YouTube, TikTok, and Facebook**.

Using Exploratory Data Analysis (EDA), the project investigates how platform characteristics, content topics, posting times, sentiment, and account influence relate to online engagement and viral behaviour.

## Objectives

- Compare engagement patterns across different social media platforms.
- Identify topics that attract the most attention and discussion.
- Explore the relationship between posting time and engagement.
- Analyse sentiment patterns across platforms and content topics.
- Investigate the relationship between follower count and engagement.
- Identify characteristics associated with viral posts.
- Explore how cross-platform spread relates to engagement.

## Dataset

**Dataset:** Multi-Platform Social Sentiment Evolution  
**Source:** [Kaggle – Social Sentiment Evolution](https://www.kaggle.com/datasets/benjaminneil/social-sentiment-evolution)

The dataset contains social media post information, including:

- Platform and topic
- Likes, shares, comments, and views
- Sentiment categories
- Posting time and day
- Follower count and verification status
- Viral coefficient
- Cross-platform spread

The dataset is included in this repository as `trendsanalysis.zip`.

## Tools and Technologies

- **Python** – Main programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualisation
- **Seaborn** – Statistical visualisation
- **Jupyter Notebook** – Interactive analysis environment

## Project Structure

```text
Cross-platform-attention-analysis-eda/
│
├── project2.ipynb
├── trendsanalysis.zip
└── README.md
```

## Analysis Performed

The notebook covers the following areas:

1. Dataset loading and initial exploration
2. Data quality checks and statistical summaries
3. Platform-wise engagement analysis
4. Topic and attention analysis
5. Topic-wise discussion patterns
6. Posting time and day-of-week analysis
7. Sentiment analysis
8. Account influence and follower analysis
9. Viral versus non-viral content analysis
10. Key findings and statistical summary

## Key Findings

The analysis highlights several interesting patterns:

- **Platform differences:** YouTube leads in views, TikTok generates high like volumes, Twitter (X) supports sharing behaviour, and Reddit encourages discussion through comments.
- **Topic influence:** Entertainment, technology, and gaming perform strongly across several platforms.
- **Timing matters:** Certain posting hours and weekends are associated with higher engagement.
- **Account influence:** Follower count is positively associated with engagement, but smaller accounts can still achieve high viral coefficients.
- **Virality:** Viral posts show substantially higher engagement than non-viral posts.
- **Cross-platform spread:** Wider content spread is associated with stronger engagement.

## Limitations

- The dataset may be synthetic or simplified and may not fully represent real-world platform behaviour.
- Engagement metrics are measured differently across platforms.
- The analysis identifies relationships, not proof of causation.
- Limited user and content context may restrict deeper interpretation.

## Conclusion

This project demonstrates that social media attention is influenced by multiple factors, including platform design, content topics, posting time, sentiment, and account authority.

There is no single factor that guarantees virality. Different platforms reward different types of engagement, and understanding these differences is important when analysing digital attention.

The project strengthened my practical understanding of **Exploratory Data Analysis, data visualisation, statistical summaries, and interpreting real-world-style social media data using Python**.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Social Media Analytics | Digital Culture | Data Analytics
