# IPL Win Predictor

[Live Demo](https://bhargav-ipl-win-prediction.streamlit.app/) | [GitHub Repository](https://github.com/rbsinh/ipl-win-predictor) 

---

## Overview

Welcome to the "IPL Win Predictor" project! This machine learning model, built using logistic regression, predicts the probability of a team winning an IPL match based on the current match situation. Get ready to make data-driven predictions!

## About This Project

The "IPL Win Predictor" leverages logistic regression to provide insights into the probability of a team winning an IPL match. This model analyzes various match features, team performance, and player statistics to offer real-time predictions.

## Project Preview

![Capture](https://github.com/rbsinh/IPL-WIN-PREDICTION/blob/main/bhargav_ipl_sample.png) <!-- Update with an actual image path -->

## Explore the Project

### Live Demo
- Experience the IPL Win Predictor in action! [Live Demo](https://bhargav-ipl-win-prediction.streamlit.app/)

## Features

- **Real-Time Predictions**: Get live predictions for IPL match outcomes based on the current match situation.
- **Interactive Interface**: The predictor is deployed on Streamlit, offering a user-friendly interface for exploring match scenarios.
- **Customizable Inputs**: Adjust the match parameters and teams to simulate different match scenarios.
- **Deployment**: Hosted on Streamlit Cloud for easy access and sharing.

## Usage

To make predictions, provide the following parameters when prompted:

- **Batting Team**: The team currently at bat.
- **Bowling Team**: The team currently bowling.
- **City**: The location of the match.
- **Current Runs**: The current score of the batting team.
- **Overs Completed**: The number of overs completed.
- **Wickets**: The number of wickets lost.
- **Target Runs**: The total runs scored by the bowling team.

The predictor will calculate the probability of the batting team winning based on these parameters and the current match situation.

## Technologies Used

This project leverages the following technologies:

- Python
- Logistic Regression
- NumPy
- Pandas
- Streamlit

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine using this command:

   ```shell
   git clone https://github.com/rbsinh/ipl-win-predictor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ipl-win-predictor
   ```

3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app locally:

   ```bash
   streamlit run app.py
   ```

5. Open the provided local URL in your web browser to access the IPL Win Predictor.
