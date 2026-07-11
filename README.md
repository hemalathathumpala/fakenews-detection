
Fake News Detection using Machine Learning Overview 

The Fake News Detection project is a Machine Learning application that classifies news articles as Real or Fake based on their textual content. It uses Natural Language Processing (NLP) techniques to preprocess news text and a Passive Aggressive Classifier to perform accurate classification.

Features Detects whether a news article is Real or Fake. Uses TF-IDF Vectorizer for text feature extraction. Trained using the Passive Aggressive Classifier algorithm. Simple command-line interface for testing news articles. Beginner-friendly project suitable for learning Machine Learning and NLP concepts. Technologies Used Python Pandas NumPy Scikit-learn TF-IDF Vectorizer Passive Aggressive Classifier Project Structure Fake-News-Detection/
 │── app.py │── train.py │── news.csv │── model.pkl │── vectorizer.pkl │── requirements.txt │── README.md
 Installation Clone the repository:
 git clone https://github.com/your-username/Fake-News-Detection.git Navigate to the project folder: cd Fake-News-Detection Install the required libraries: pip install -r requirements.txt How to Run Train the model: python train.py Run the application: python app.py Enter a news article when prompted. The application will predict whether the news is REAL or FAKE. Dataset 

The dataset contains news articles with two columns:

text – News article content label – REAL or FAKE Future Enhancements Develop a web interface using Flask. Improve prediction accuracy using advanced NLP models. Deploy the project on a cloud platform. Add support for live news article analysis. Learning Outcomes Data preprocessing using NLP. Feature extraction with TF-IDF. Machine Learning model training and evaluation. Model serialization using Pickle. Building an end-to-end Machine Learning application.
 Author 

Thumpala Hema latha

B.Tech Student | Data Science Enthusiast | Interested in Machine Learning, Artificial Intelligence, and IoT.

