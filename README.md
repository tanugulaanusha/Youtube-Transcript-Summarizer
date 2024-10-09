This project is a Chrome extension that automatically summarizes YouTube video transcripts and translates the summaries into different languages. It provides users with a quick overview of a video’s content without needing to watch the entire video.

Key Features
Automatic Transcript Summarization: Uses Natural Language Processing (NLP) techniques to extract key points from the YouTube video transcript.
Multi-Language Translation: Integrates with the Google Translation API to translate the generated summaries into different languages based on user preference.
Dynamic Summarization: Automatically generates concise summaries when the user clicks on the extension while watching a YouTube video.
User-Friendly Interface: The extension provides an easy-to-use interface, allowing users to quickly view or copy the summary and choose the translation language.

Project Workflow

Transcript Retrieval:
The extension utilizes the YouTube Transcript API to extract the transcript from the video.
If a video contains multiple language subtitles, the user can select the language from which to generate the summary.

NLP-Based Summarization:
The transcript text is processed using Natural Language Processing algorithms to identify the key points, filtering out non-essential details.
Summarization techniques focus on reducing the transcript size while maintaining the core content of the video.

Translation:
After summarizing the transcript, the user can choose a language for translation.
The Google Translation API is integrated to convert the summary into the selected language.

User Interface:
The Chrome extension provides a clean and minimalistic UI.
Users can generate the summary with a single click and view it within the extension.
The UI also allows users to select a translation language from a dropdown menu and instantly view the translated summary.
Technologies Used
HTML, CSS, JavaScript: For creating the Chrome extension and frontend user interface.
Flask: Used as the backend framework to handle API requests and data processing.
YouTube Transcript API: For fetching video transcripts.
Google Translation API: For translating the generated summaries into different languages.
Natural Language Processing (NLP): To process and summarize the transcripts.
How to Use
Clone the Repository: Download the source code from GitHub.
Install the Extension:
Load the unpacked extension in Chrome by navigating to chrome://extensions/ and enabling developer mode.
Click on "Load unpacked" and select the project folder.
Run the Backend:
Install the necessary Python dependencies using pip install -r requirements.txt.
Run the Flask backend using python app.py.
Activate the Extension: Open any YouTube video, click on the extension, and view the summarized transcript in your preferred language.
Use Cases
Content Summarization: Quickly understand the content of long YouTube videos.
Multi-Language Support: Summarized content can be translated into various languages, making it accessible to a wider audience.
This project aims to enhance the video consumption experience by providing quick, easy-to-read summaries and language translation for YouTube content, saving time and breaking language barriers.
