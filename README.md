# Amazon-Sales-Project


## Overview

The Amazon Sales Analytics is a robust and feature-rich web application developed using R and Shiny. This platform enables businesses to gain deep insights into their sales, profit, and regional performance, empowering them with predictive analytics and advanced machine learning capabilities.

This project focuses on transforming sales data into actionable insights, with features such as interactive visualizations, real-time predictions, and geographical mapping. Designed with user experience in mind, it offers a clean, modern interface and enterprise-grade security.

## Features

Authentication:

Secure Google OAuth2.0-based authentication.

Enhanced login UI with modern animations.

Dashboard:

Interactive visualizations (bar charts, scatter plots, 3D plots, etc.) powered by ggplot2 and plotly.

Quick analytics, sales trends, and geographical performance.

Machine Learning:

Predictive analytics using Random Forest and XGBoost models.

Profit prediction with confidence intervals.

Feature importance visualization for model interpretability.

Geographical Insights:

Interactive map for regional sales performance using leaflet.

Regional summaries and drill-down capabilities.

Data Management:

Upload and process Excel files dynamically.

Custom filtering and data export capabilities.

Customization:

Various plot types, customizable visualizations, and real-time updates.

Developer Tools:

Easily extensible with modular design.

Comprehensive logs and debugging features.

## Technologies Used

Languages and Frameworks:

R (Shiny, ggplot2, dplyr, randomForest, xgboost, caret, etc.)

Frontend and Styling:

shinythemes, shinyjs, CSS animations, and fontawesome icons.

Backend:

OAuth2.0 Authentication (Google APIs)

Data Visualization:

plotly, ggplot2, leaflet

Geospatial Analysis:

leaflet for interactive maps

## Setup Instructions

Prerequisites:

R and RStudio installed on your system.

Required libraries: Install them using the command:

install.packages(c("shiny", "ggplot2", "dplyr", "randomForest", "xgboost", "caret", "readxl", "plotly", "shinythemes", "DT", "shinyjs", "httr", "fontawesome", "tidyverse", "lubridate", "forecast", "leaflet", "scales"))

Set Up OAuth Credentials:

Replace the placeholders in google_client_id and google_client_secret within the grandfinal.R file with your credentials from the Google Cloud Console.

Run the Application:

Open the grandfinal.R file in RStudio.

Click Run App.

Access the App:

Open the URL displayed in your RStudio console in a web browser.


## Usage

Data Upload:

Upload Excel files containing your sales data.

Ensure the file includes required columns: Sales, Profit, Discount, Region, Category, Sub-Category.

Dashboard Navigation:

View sales trends, profit forecasts, and regional performance.

Use filters and dynamic inputs for customized analysis.

Export and Share:

Download analysis results and visualizations as CSV or PNG files.

## Contributors

Apurva Kacholiya Role: Data Scientist
Ayush Sukhwal Role: Lead Developer
