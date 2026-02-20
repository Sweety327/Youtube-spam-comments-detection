# Youtube-spam-comments-detection
This project is a machine learning web application that detects whether a YouTube comment is Spam or Not Spam using Natural Language Processing (NLP) techniques. <br>
It analyzes user input text and predicts results instantly using a trained classification model.<br>
The purpose of this project is to demonstrate how machine learning can automate comment moderation and help filter unwanted spam content.<br>

🚀 Features<br>
Real-time spam detection<br>
Text preprocessing pipeline<br>
Machine learning prediction model<br>
Simple web interface<br>
Lightweight and fast performance<br>

🧠 How It Works<br>
User enters a comment<br>
Text is cleaned and processed<br>
Model converts text into numerical vectors<br>
Classifier predicts spam or not spam<br>
Result displayed instantly<br>

🛠️ Tech Stack<br>
Python<br>
Flask<br>
Scikit-learn<br>
Pandas<br>
NumPy<br>
HTML<br>
<br>
📂 Project Structure<br>
Youtube-spam-comments-detection<br>
│<br>
├── app.py<br>
├── templates<br>
&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|── youtubechk.html<br>
├── Youtube01-Psy.csv<br>
├── requirements.txt<br>
├── app (2).yaml<br>
└── README.md<br>
<br>
▶️ How to Run<br>
Install dependencies:<br>
pip install -r requirements.txt<br>
<br>
Run app:<br>
python app.py<br>
<br>
Open browser:<br> 
paste- http://127.0.0.1:8081<br>
<br>
⚠️ Important Setup Note<br>
If you get this error:<br>
TemplateNotFound: youtubechk.html<br>
Move HTML file into a folder named templates<br>
<br>
sample output:<br>
<img width="1501" height="772" alt="Screenshot 2026-02-20 153925" src="https://github.com/user-attachments/assets/46fb4e6b-8807-420f-8245-fdc3cc835975" /><br>
<img width="1450" height="768" alt="image" src="https://github.com/user-attachments/assets/725dffac-9754-4408-97a1-77af73d4af2e" /><br>
<br>
->This project can be used as a prototype for:<br>
Social media moderation systems<br>
Comment filtering tools<br>
Spam detection engines<br>
Content safety systems<br>

->Future Improvements:<br>
Deep learning model integration<br>
Live YouTube API connection<br>
Multilingual detection<br>
Accuracy dashboard<br>
