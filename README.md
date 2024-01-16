# Whatsapp-Chat-Analyzer
Social Media Chat Analyzer: 
This project is a social media chat analyzer built with Python and Streamlit. The application provides various analyses on a chat log, including top statistics, activity timelines, activity maps, word cloud, most common words, emoji analysis, and sentiment analysis. The analysis can be done for a specific user or for the overall chat.

Features
Top Statistics: Displays the total number of messages, total words, media shared, and links shared.
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/863a46ca-3273-4df5-9e70-bebef7d09269)

Activity Timelines: Shows the monthly and daily activity timelines.
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/8c49e979-d941-4235-91e2-c435fbb89fef)
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/6d7f4c3a-cb83-4c2c-8e7c-0fc3cb17dbb0)


Activity Maps: Visualizes the most busy day and month. 
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/c3b8d7d9-7eef-47eb-8b1a-6917cc2976ea)
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/b2c326a0-538d-4dca-80e6-d84fae474160)
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/01d19632-8a37-49ed-a51b-ec6652fc9e19)


Word Cloud: Generates a word cloud for frequent words. 
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/829d19dc-7d9a-477f-a118-4c4f8c1ae4c5)

Most Common Words: Lists the most common words used in the chat. 
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/ae3ec4d3-7fd7-49e4-9334-d25fc6855e0b)

Emoji Analysis: Analyzes the usage of emojis in the chat.
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/b840b137-86d9-44b0-9889-1d9ae6511497)

Sentiment Analysis: Performs sentiment analysis based on the text and emojis used in the messages. image
![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/1e119dac-6df6-4d8c-ad15-8d6cd7743988)

Installation
Clone the repository:
gh repo clone amitkedia007/Whatsapp-chat-analyzer
Navigate to the project directory:
cd Whatsapp-chat-analyzer
Install the required Python packages:
pip install -r requirements.txt
Usage
Run the Streamlit application:
streamlit run app.py
Open your web browser and go to http://localhost:8501.

Upload a chat log file using the file uploader in the sidebar.

![image](https://github.com/anuragsrivastav-dtu/Whatsapp-Chat-Analyzer-/assets/140643875/475ef7ce-90ae-4bc1-b5d5-ca00a0986a25)


Select a user from the dropdown menu in the sidebar.

Click the "Show Analysis" button in the sidebar to display the analysis.

Project Structure
app.py: The main Streamlit application.

preprocessor.py: Contains the preprocess function for preprocessing the chat log.

helper.py: Contains various helper functions for the analyses.

stopwords.txt: A text file containing common stopwords to be excluded from the word cloud and most common words analysis.
