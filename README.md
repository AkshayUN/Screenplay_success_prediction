# Screenplay_success_prediction
This project predicts movie success by forecasting IMDb ratings and the number of ratings using features like plot, genre, director, cast, producer, taglines, and release year. It helps directors and producers make data-driven decisions to streamline content review and assess a movie's potential.

Key Contributions:
Data Preparation:
Processed text features (e.g., plot, keywords) using word2vec to convert text into semantic vector representations.
Converted multi-genre data into binary vectors using MultiLabelBinarizer and standardized numerical features (e.g., release year) using StandardScaler.
Removed missing values to ensure data quality.

Model Design and Development:
Designed a Feedforward Neural Network (FNN) with a progressively shrinking layer architecture (512 → 256 → 128 → 64).
Applied ReLU activation, dropout layers for regularization, and sigmoid activation to constrain IMDb ratings between 1 and 10.
Utilized MSE Loss for performance evaluation and the Adam optimizer for model training.

Key Data Analytics Skills Acquired:
Natural Language Processing (NLP): Applied advanced text vectorization techniques (word2vec) to capture semantic relationships in text data.

Feature Engineering: Converted complex data into machine-readable formats, ensuring compatibility with neural network models.

Model Evaluation: Monitored loss metrics on training and testing sets to identify performance gaps and prevent overfitting.

Optimization Techniques: Fine-tuned hyperparameters and optimized preprocessing pipelines to improve prediction accuracy.

Business Impact:
Accelerated Decision-Making: Provided a framework to forecast movie success, enabling directors and producers to make informed choices about scripts and casting.

Data-Driven Insights: Helped identify key predictors of a movie's success, such as genre and tagline relevance.

Improved Efficiency: Replaced traditional, subjective content reviews with predictive analytics, saving time and resources.

Challenges and Solutions:
Resolved data size mismatches by switching from TF-IDF to word2vec for more flexible vectorization.

Addressed prediction accuracy issues by fine-tuning hyperparameters and planning experiments with BERT for advanced text analysis.

This project exemplifies the integration of NLP, machine learning, and business strategy to drive actionable insights and improve decision-making processes in the entertainment industry. It showcases a blend of technical expertise and practical application to solve real-world problems.
