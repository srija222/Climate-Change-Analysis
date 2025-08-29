# Climate-Change-Analysis
Climate Change Modeling — NASA Facebook Comments (2020–2023)
PROJECT OVERVIEW

This project analyzes public opinion on climate change using comments collected from NASA’s official Facebook page (2020–2023).
The dataset contains over 500 comments, including metadata such as posting date, likes, and replies.

Using Natural Language Processing (NLP) techniques, the project explores:

Sentiment Analysis → whether comments are positive, neutral, or negative.
Topic Modeling (LDA) → major discussion themes in climate change conversations.
Engagement Analysis → how sentiment influences likes and replies.
Trend Analysis → how opinions and topics shift over time.

This project demonstrates the role of data science in social discourse analysis, helping us understand how people react to climate change communication.

⚙️ Technologies Used

Python 3
Pandas, NumPy → data manipulation
Matplotlib, Seaborn → data visualization
Scikit-learn → feature extraction, topic modeling (LDA)
Custom Lexicon → rule-based sentiment analysis (offline-friendly)

📊 Dataset

Source: NASA Climate Change Facebook Page

Columns:

Date → when the comment was posted
LikesCount → number of likes
CommentsCount → number of replies
ProfileName → anonymized user ID
Text → actual comment content
Size: ~500 comments (2020–2023)

🔎 Key Insights

Comment activity peaked during major climate events and announcements.
Most comments were neutral, but negative comments often triggered debates.
Positive comments tended to receive more likes, while negative ones attracted more replies.
Common themes included: NASA missions, climate science, skepticism, extreme weather, and policy discussions.

🚀 How to Run

1.Clone this repository:

git clone https://github.com/yourusername/climate-change-modeling.git
cd climate-change-modeling


2.Install required libraries (if not already installed):

pip install pandas numpy matplotlib seaborn scikit-learn


3.Open the Jupyter Notebook:

jupyter notebook Climate_Change_NASA_Facebook_Comments_Project.ipynb


4.Run all cells to reproduce the analysis.

📌 Future Improvements

Replace rule-based sentiment with VADER or transformer models for higher accuracy.
Expand dataset with more comments or posts from other climate-related pages.
Deploy an interactive dashboard using Streamlit or Flask.

📖 Acknowledgements

NASA Climate Change Facebook Page for open public engagement.
Scikit-learn & Pandas communities for powerful open-source tools.
