# Titanic Data Visualization with Seaborn

An exploratory data visualization using the classic Titanic dataset, built to practice core `seaborn` plot types and uncover patterns in passenger demographics, fares, and survival-related attributes.

## Dataset

The built-in [`seaborn` Titanic dataset](https://github.com/mwaskom/seaborn-data) — passenger-level data including age, sex, fare, ticket class, and more, loaded directly via `sns.load_dataset('titanic')` (no download needed).

## What's covered

A range of seaborn plot types, each chosen to answer a different question about the data:

| Plot | Question it answers |
|---|---|
| `jointplot` (fare vs. age) | Is there a relationship between how much a passenger paid and their age? |
| `distplot` (fare) | What does the distribution of ticket fares look like? |
| `boxplot` (age by class) | How does passenger age vary across 1st/2nd/3rd class? |
| `swarmplot` (age by class) | Same question, showing every individual data point |
| `countplot` (sex) | What's the gender breakdown of passengers? |
| `heatmap` (correlation matrix) | Which numerical features correlate with each other? |
| `FacetGrid` (age histograms by sex) | How does the age distribution differ between male and female passengers? |

All plots render directly in the notebook with their outputs saved, so you can view the charts on GitHub without running anything.

## Tech stack

- Python
- seaborn
- Matplotlib


