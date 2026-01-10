# Cinema Audience Forecasting

## Overview
Time-series forecasting project to predict daily cinema audience counts across multiple locations.
Completed as part of an academic course project using a private Kaggle competition.

## Problem Statement
Given historical booking, visit, and point-of-sale data, the goal was to forecast future audience
counts for different movie-theater combinations over a defined prediction horizon.

## Dataset
The dataset was provided via a private Kaggle competition hosted for coursework.

- Multiple transactional and relational tables
- Time-indexed data spanning several months
- Target format provided via a sample submission file

(Competition link included for reference.)
https://www.kaggle.com/competitions/Cinema_Audience_Forecasting_challenge/overview

## Data Understanding
Initial data inspection was performed to understand table sizes, relationships, and scale.
The dataset consisted of multiple high-volume transactional tables and supporting metadata,
requiring careful joins and preprocessing before modeling.

## Approach
- Data loading and schema validation across multiple tables
- Data cleaning and preprocessing
- Feature engineering to capture temporal patterns
- Model training and evaluation using scikit-learn
- Time-aware validation to avoid data leakage

## Tools & Technologies
Python, Pandas, NumPy, scikit-learn, Matplotlib, Kaggle
