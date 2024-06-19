Retirement Planning Assistant App

Overview

The Retirement Planning Assistant is a Python application designed to help users plan for their retirement by calculating the monthly savings needed based on their financial inputs.
Features

    User Registration: Allows users to register and store their financial information securely.
    Monthly Savings Calculation: Computes the required monthly savings based on current age, retirement age, current savings, retirement goal, and annual interest rate.
    Visualization: Provides visual representation of savings growth over time using Matplotlib.

Project Structure

The project consists of the following main files:

    main.py: Entry point of the application that orchestrates user interaction and integrates functionalities.
    database.py: Sets up the SQLite database using SQLAlchemy for storing user data.
    models.py: Defines the SQLAlchemy model for the User table.
    retirement_calculator.py: Contains functions to calculate financial aspects related to retirement planning.
    visualizer.py: Provides functions to visualize savings growth over time using Matplotlib.
    user_interface.py: Handles user registration and interaction.
    
1)Setup

Installation
Clone the repository:
git clone https://github.com/sha-shankk/Retirement-Planning-Assistant.git

cd Retirement-Planning-Assistant

2)Install dependencies:
    pip install -r requirements.txt

3) Usage
 Run the application:
 python main.py


The project requires the following dependencies, which can be installed via pip:

    SQLAlchemy
    Matplotlib



Contributions are welcome! Please fork the repository and create a pull request with your changes.
    
