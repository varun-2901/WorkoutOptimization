# Optimizing Workout Sequences: A Genetic Algorithm Approach

## Overview

This project utilizes a genetic algorithm to optimize workout sequences, aiming to balance training across multiple muscle groups. By leveraging a dataset of gym exercises, the project seeks to create effective workout plans that enhance overall fitness and prevent injuries.

## Data Source

The dataset used in this project is sourced from Kaggle. It contains information on various gym exercises and the muscle groups they target.

#Methodology

- Data Loading: The dataset is loaded and cleaned to remove NA values and white spaces.
- Basic Data Analysis: A preliminary analysis of exercise counts per muscle group is performed.
- Genetic Algorithm Optimization: A genetic algorithm is used to select exercises that maximize muscle group coverage.
- Population Size: 50
- Max Iterations: 100
- Mutation Probability: 0.01

# Results

The optimized workout plan targets a range of muscle groups, with a notable emphasis on lower body exercises, particularly Hamstrings, Adductors, and Gluteus Maximus. While lower body strength is well-represented, the upper body muscles, such as Biceps Brachii and Deltoids, are underrepresented.

# Key Insights
- Balanced Lower Body: Strong focus on lower body muscle groups.
- Moderate Upper Body Coverage: Some upper body muscle groups are less emphasized.
- Actionable Recommendations: Adjustments can be made to achieve a more balanced workout.

# Future Improvements
- Balanced Upper and Lower Body Training: Incorporate weighting in the fitness function for better muscle group representation.
- Personalization: Refine optimization to include user-specific preferences and goals.
- Incorporating Recovery: Future models may include rest periods to prevent overtraining.




