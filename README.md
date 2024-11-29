Dog Classification System

This project was completed as part of the AI Programming with Python and TensorFlow course through the Palestine Launchpad Initiative by Google and Udacity.

Project Overview

The city is hosting a large dog show, and I volunteered to assist with the registration process. As part of the system, participants upload an image of their dog along with biographical information.
To ensure only dogs are registered, a Python-based image classification system was implemented to verify submitted images.

This project involves applying Python skills and evaluating different pre-existing image classification algorithms to identify dogs and their breeds.

Features

	•	Dog Classification: Verifies whether an uploaded image is of a dog or not.
	•	Breed Identification: Evaluates how accurately the classifier can identify the breed of the dog.
	•	Algorithm Performance Testing: Compares multiple image classification algorithms for accuracy and runtime efficiency.

Tasks

	1.	Algorithm Evaluation:
	•	Evaluate different image classification algorithms to determine the best performer for distinguishing between “dogs” and “not dogs.”
	2.	Breed Identification:
	•	Assess the accuracy of the best algorithm in identifying specific dog breeds.
	3.	Performance Analysis:
	•	Measure the runtime of each algorithm to understand the trade-off between accuracy and computational cost.

Technologies Used

	•	Python: Primary programming language used for implementation.
	•	Pre-Trained Image Classifier: An existing classifier provided as part of the course.
	•	Tools: TensorFlow, Numpy, and additional Python libraries.

Key Insights

	•	Accuracy vs. Runtime Trade-Off: Higher accuracy algorithms tend to have longer runtimes and require more computational resources.
	•	Practical Applications: The project highlights how image classifiers can be used as tools in real-world applications, such as verifying the validity of registrations.

How It Works

	1.	Input: An image is submitted to the classifier.
	2.	Processing: The classifier predicts whether the image depicts a dog.
	3.	Output: The result indicates “dog” or “not dog.”
	4.	Additional Evaluation: If the image is classified as a dog, the system attempts to identify its breed.

Future Improvements

	•	Incorporate more classifiers to test additional algorithms.
	•	Enhance breed identification accuracy using fine-tuned models.
	•	Optimize runtime performance for faster classification.
