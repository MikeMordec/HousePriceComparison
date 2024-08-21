HousePriceComparison
Overview

HousePriceComparison is a C++ program designed to compare the price per square foot of three different house models. Users input the price and finished area of each model, and the program calculates and compares their price per square foot to determine which model is the most cost-effective.
Features

    Input prices and finished areas for three different house models.
    Calculate the price per square foot for each model.
    Compare and determine the model with the lowest price per square foot.
    Handles ties and outputs the results clearly.

Getting Started
Prerequisites

    C++ compiler (e.g., g++, clang++)

Compilation

To compile the program, use the following command:

bash

g++ -o HousePriceComparison HousePriceComparison.cpp

Usage

Run the compiled program:

bash

./HousePriceComparison

Follow the prompts to enter the price and finished area for each house model. The program will display the price per square foot for each model and indicate which model has the lowest price per square foot.
Example

yaml

Enter the price of the colonial model: 250000
Enter the finished area in square feet of the colonial model: 2000

Enter the price of the split-entry model: 300000
Enter the finished area in square feet of the split-entry model: 2200

Enter the price of the single-story model: 280000
Enter the finished area in square feet of the single-story model: 1800

Price per square foot for colonial model: $125.00
Price per square foot for split-entry model: $136.36
Price per square foot for single-story model: $155.56

The price per square foot of the colonial model is the least.

