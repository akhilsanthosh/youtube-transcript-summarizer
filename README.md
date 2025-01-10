# YouTube Transcript Summarization and Translation

## **Project Overview**

This project automates the process of extracting, summarizing, and translating YouTube video transcripts. It leverages advanced Natural Language Processing (NLP) techniques to enhance the accessibility and comprehension of video content.

---

## **Key Features**

- **Transcript Extraction**: Extract video transcripts directly using the YouTube Transcript API.
- **Text Summarization**: Generate concise and meaningful summaries using the BART model.
- **Multilingual Translation**: Translate summaries into multiple languages using the Google Translate API.
- **Efficient Workflow**: Designed to simplify the process of digesting YouTube video content.

---

## **Technologies Used**

- **Programming Language**: Python
- **APIs**:
  - [YouTube Transcript API](https://github.com/jdepoix/youtube-transcript-api) for transcript extraction.
  - [Google Translate API](https://pypi.org/project/googletrans/) for translation.
- **Libraries**:
  - [Transformers (Hugging Face)](https://huggingface.co/docs/transformers) for text summarization.
  - Other libraries: `googletrans`, `youtube_transcript_api`.

---

## **System Architecture**

1. **Input**: User provides a YouTube video link.
2. **Transcript Extraction**: The YouTube Transcript API extracts the transcript of the video.
3. **Summarization**: The BART summarization model processes the transcript to generate a concise summary.
4. **Translation**: The Google Translate API translates the summary into the desired language.
5. **Output**: The summarized and translated text is presented to the user.

---

## **Installation Instructions**

### Prerequisites

- Python 3.7+
- Install the required libraries:
  ```bash
  pip install youtube-transcript-api googletrans==3.1.0a0 transformers
  ```

### Running the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Run the script:
   ```bash
   python <script_name>.py
   ```
3. Follow the prompts to input the YouTube video link.

---

## **How It Works**

1. Extracts the transcript of a YouTube video using its video ID.
2. Processes the transcript to generate a summary, splitting large transcripts into smaller segments for better summarization.
3. Translates the summary into the specified language (e.g., Telugu).

---

## **Project Output**

- **Sample Summary Output**:
  *"This video discusses the importance of time management and productivity tips for students and professionals alike."*

- **Sample Translation Output** (Telugu):
  *"ఈ వీడియో విద్యార్థులు మరియు నిపుణుల కోసం సమయం నిర్వహణ మరియు ఉత్పాదకత చిట్కాల ప్రాధాన్యత గురించి చర్చిస్తుంది."*

---

## **Future Enhancements**

1. Support for additional languages.
2. Customizable summary lengths.
3. Enhanced NLP models for greater context-awareness and accuracy.
4. Integration into a web-based or mobile application for broader accessibility.

---

## **Contributors**

- **Andhavarapu Vamsi Teja** (320106411003)
- **Boddu Sai Akhil** (320106411004)

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
