# FinBert Yiyanghkust
there are several pre-trained models that classifies financial text data. the most famous ones were developped by a Hong kong professor called Yi Yang.

Yi yang developped 4 models:

| Model        | Model type |
|--------------|---------------------|
| FinBert-Tone | text classification |
| FinBert-Esg  | text classification |
| FinBert-fls  | text classification |

#### Finbert-tone
This specified model is pre-trained by 10000 financial statements annotated by analyst reports with the following labels:
1. Positive
2. Negative
3. Neutral

#### FinBert-esg
ESG analysis can help investors determine a business' **long-term sustainability** and identify associated risks. FinBERT-ESG is a FinBERT model fine-tuned on 2,000 manually annotated sentences from firms' ESG reports and annual reports.
the labels: 
1. Enviromental
2. Social
3. Governance

#### Finbert-fls
Forward-looking statements (FLS) inform investors of managers’ beliefs and opinions about firm's future events or results. Identifying forward-looking statements from corporate reports can assist investors in financial analysis.
###### what is forward looking statements?
It is any statement about future plans and perspectives.

The labels : 
1. Specific-FLS 
2. Non-specific FLS
3. Not-FLS.
