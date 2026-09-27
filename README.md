# Framing AI in the Hollywood Strike

A social media analysis exploring how different Reddit communities framed the role of Artificial Intelligence during the 2023 Hollywood Strike.

## Overview

The 2023 Hollywood Strike brought generative AI into the center of debates around creative work, authorship, labor rights and technological innovation.

This project investigates how different online communities interpreted AI during the dispute, asking whether these perspectives varied across communities and throughout different phases of the strike.

The analysis combines **Natural Language Processing and network analysis** to examine both the content of the discussions and the structure of interactions between users.

## Research Question

> How did online communities frame the role of AI during the Hollywood Strike, and did framing vary systematically across communities and across the temporal phases of the dispute?

## Dataset

Reddit discussions were collected through the **PullPush historical archive** from March to December 2023.

The final dataset includes:

- 399 submissions
- 11,048 comments
- 5 subreddits
- 3 temporal phases: pre-strike, strike and post-strike

The communities analyzed include `r/Screenwriting`, `r/movies`, `r/artificial`, `r/television` and `r/labor`.

## Methodology

The project follows a multi-method analysis combining:

- **Data preprocessing** and text normalization
- **Exploratory lexical analysis**
- **Frame detection** using dictionary-based classification
- **Sentiment analysis** using a RoBERTa-based transformer
- **Named Entity Recognition (NER)** with spaCy
- **Network analysis** of Reddit reply interactions
- **Community detection** using the Louvain algorithm
- **Centrality and broker analysis**
- **Temporal analysis** across different phases of the strike
- **Integrated community analysis** connecting network structure with discussion content

Five main interpretative frames were identified:

1. Replacement Anxiety
2. Workers' Rights
3. Authenticity & Creativity
4. Corporate Power
5. Innovation Opportunity

## Key Findings

The analysis shows that AI was interpreted differently across Reddit communities.

- `r/Screenwriting` emphasized authorship, creative identity and labor-related concerns.
- `r/artificial` focused more strongly on technological innovation and opportunity.
- Entertainment-oriented communities showed more mixed perspectives.
- User interactions formed a highly segmented network, with discussion occurring mainly within individual communities.
- Cross-subreddit interaction decreased over the course of the strike.
- Concerns around AI remained visible even after the formal resolution of the dispute.

Overall, the results suggest that **community structure and interpretation evolved together**: groups that interacted less frequently also tended to develop different ways of framing AI.

## Technologies

`Python` · `pandas` · `NLTK` · `spaCy` · `Transformers` · `NetworkX` · `python-louvain` · `PyVis` · `Matplotlib` · `Seaborn`

## Repository Contents

- `WSA_Camera_Miele_notebook.ipynb` — complete data collection and analysis pipeline
- `WSA_Camera_Miele_report.pdf` — final project report
- `WSA_Camera_Miele_Presentation.pdf` — project presentation

## Authors

**Beatrice Camera**  
**Daria Miele**

Bachelor in Artificial Intelligence  
Web and Social Media Search and Analysis — Academic Year 2025/2026
