# AI-assignment

## Project Overview
This Jupyter Notebook performs a Exploratory Data Analysis (EDA) on a dataset of card transactions (card_transdata.csv). The goal is to understand the underlying structure of the data, identify key features that are predictive of fraudulent transactions, and prepare the dataset for future machine learning modeling. The analysis covers several critical steps: data loading, data cleaning, univariate analysis, bivariate analysis.


## Reflection on AI Assistance

Using an AI tool for this EDA assignment was super helpful in a few ways. The biggest one was just saving time. Instead of spending forever looking up how to set up subplots or remembering the exact syntax for stuff like dropna(inplace=True), I could just tell the tool what I wanted, like "make five distribution graphs", and it would give me clean, ready-to-run code. This let me skip the boring parts and focus on the actual analysis, like deciding which variables were important to compare and why.

That said, I can totally see how using AI without really understanding the basics could get you into trouble. If you don't know what the code is actually doing, you might not catch mistakes. For example, at one point the AI generated code that tried to sample 100,000 rows from the dataset, but after cleaning, there were fewer rows left. It threw a ValueError because it was trying to take a bigger sample than the actual dataset size. If I didn’t have a clue how sampling works, I might’ve just been stuck or kept asking the AI to try again without learning why it broke.

When that error popped up, I had to step in and figure it out. The error message said it couldn’t take a sample larger than the population, which made sense once I thought about it. I checked what the AI did next, and it fixed the code by adding a check to only sample up to the number of rows available. So even though the AI sped things up, I still had to be the one to catch the mistake and make sure the fix made sense. It reminded me that the tool is helpful, but I’m the one who has to stay in control.
