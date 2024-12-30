Overview

The AI-Based Fitness Tracking System enhances the accuracy of exercise monitoring by leveraging machine learning and motion sensor data. This system classifies exercises and counts repetitions precisely to bridge the gap in strength training exercise tracking, offering a seamless and automated experience.

Key Features

Exercise Classification: Recognizes complex strength exercises such as squats, deadlifts, and bench presses.

Repetition Counting: Automatically counts repetitions without manual input.

Real-Time Analysis: Processes motion data in real-time for accurate performance tracking.

Wearable Integration: Optimized for M-Motion sensors embedded in wearable devices.

Highlights

Data Collection: Utilizes accelerometer and gyroscope data from wearable sensors.

Feature Engineering: Implements temporal and frequency domain analysis, noise filtering, and dimensionality reduction techniques.

Modeling Approach: Trains a Random Forest classifier with advanced feature extraction and hyperparameter tuning.

Evaluation Metrics: Employs accuracy, precision, recall, and confusion matrices for performance assessment.

Use Cases: Strength training, rehabilitation, and athletic performance monitoring.

Project Structure

Data Processing: Steps include raw data cleaning, noise reduction using Butterworth filters, and feature aggregation.

Feature Selection: Employs forward selection and PCA to identify the most predictive attributes.

Model Training and Testing: Includes robust cross-validation and grid search optimization techniques.

Repetition Benchmarking: Develop benchmarks to compare predicted repetitions with actual counts.

Goals and Objectives

Automate the identification and classification of strength exercises.

Provide real-time feedback on exercise form and performance.

Adapt to user-specific variations in body mechanics and exercise techniques.

Expand the range of exercises tracked beyond traditional fitness activities.

Implementation Details

Languages: Python

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, SciPy

Hardware: M-Motion sensor wristband, accelerometer, and gyroscope.

Techniques: Clustering (k-means), Fourier Transform, Temporal and Frequency Abstraction.

Results and Insights

High Accuracy: Achieved optimal classification performance with the Random Forest model.

Robust Detection: Successfully detected and differentiated between similar exercise variations.

Scalability: Demonstrated potential for real-world deployment in fitness wearables.

Future Work

Expand exercise tracking capabilities to include dynamic and functional movements.
Integrate computer vision techniques for enhanced form feedback.
Develop personalized models for diverse user populations.
