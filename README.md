# **Sketching Cats with ARIMA: A Time Series Analysis into Cat Sketches**
*by Jayawardana Wickramasinghe Pathiranage Lakindu Ransika*

**[View the Final Report (PDF)](https://lakindu2003.github.io/QuickDrawCatTimeSeries/project_report.pdf)**
## 1. Introduction
## 1.1. Background
The advent of deep learning models such as diffusion transformers (Peebles & Xie, 2023) has shown the ability of machine learning models in generating images by developing a semantic understanding of the real world. This project explores the application of statistical models in image understanding and generation. More specifically, this project focuses on a simple cat drawing chosen from the Quick Draw dataset (Google, n.d.-a). Cats were selected due to their cuteness (England, 2025).
The Quick Draw dataset contains 50 million doodle drawings (Google, n.d.-a). These drawings were collected via the “Quick, Draw!” online game (Google, n.d.-b) from 15 million people (Google, n.d.-a) all over the world. In each game, the player is prompted with a subject, such as a cat, and is given 20 seconds to draw a doodle. 
Drawing a doodle involves a series of strokes. Each stroke is a sequence of inputs that sequentially mark the corresponding pixels on the screen. The causal and sequential nature of each stroke allows it and the entire doodle to be modelled as a time series. 

## 1.2. Objectives
This project has two main objectives:
* Model the distance from the center of a cat doodle drawing as a time series using ARIMA
* Analyze the generative capabilities of VARIMA in cat doodle sketching
