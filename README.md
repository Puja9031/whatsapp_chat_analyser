###  WhatsApp Chat Analyzer

This project involves creating a comprehensive tool for analyzing WhatsApp chat data using Python. The tool leverages several libraries, including pandas, matplotlib, seaborn, and Streamlit, to process and visualize chat data, providing insights into user activity, message patterns, and more. The project consists of three main components:

1. **Streamlit App for Chat Analysis**:
   - A user-friendly interface built with Streamlit allows users to upload their WhatsApp chat data and perform various analyses.
   - Key statistics such as total messages, words, media shared, and links shared are displayed.
   - Interactive visualizations including monthly and daily timelines, activity maps, word clouds, and emoji analysis provide a detailed understanding of chat patterns.
   - Users can filter analyses by specific participants or view overall group data.

2. **Helper Functions for Data Analysis**:
   - A collection of helper functions is used to process the chat data and extract meaningful insights.
   - Functions include `fetch_stats` for basic statistics, `most_busy_users` for identifying the most active participants, `create_wordcloud` for generating word clouds, `most_common_words` for listing frequently used words, and `emoji_helper` for emoji usage analysis.
   - Additional functions like `monthly_timeline`, `daily_timeline`, `week_activity_map`, `month_activity_map`, and `activity_heatmap` generate various visualizations depicting chat activity over time.

3. **Data Preprocessing**:
   - The preprocessing function converts raw WhatsApp chat data into a structured pandas DataFrame.
   - It uses regex to parse date and time from the chat text, splits messages and user information, and extracts various datetime components (year, month, day, hour, etc.).
   - The function also includes the creation of a `period` column to categorize messages by time periods, facilitating time-based analysis.

Together, these components provide a powerful tool for analyzing WhatsApp chats, offering users valuable insights into communication patterns within their groups or individual conversations.
### output

![1](https://github.com/user-attachments/assets/12428050-f1ca-484c-9723-9fcca421d075)
![2](https://github.com/user-attachments/assets/70a3ce86-4307-4c1b-84eb-768192963308)
![3](https://github.com/user-attachments/assets/ef3636b7-8ac6-41b2-a9ac-7b94bf5cffb0)
![4](https://github.com/user-attachments/assets/f4c3a56f-cf32-4171-bcd6-e4ca9119191c)
![5](https://github.com/user-attachments/assets/f88e59f2-f906-486f-b977-e085ea4aee99)
![6](https://github.com/user-attachments/assets/824334e7-aab1-4868-8adc-8c49560b4fe5)
![![8](https://github.com/user-attachments/assets/93aa83e0-15df-47c1-975c-2ca748fd9832)
7](https://github.com/user-attachments/assets/69d39654-149b-4226-b1f0-c5a232a167e8)
![9]![10](https://github.com/user-attachments/assets/17ad41d9-59e2-4389-8a00-90ac117f42b4)
![11](https://github.com/user-attachments/assets/01d8b08b-ca71-456f-b787-5ed2e65bb331)
![13![12](https://github.com/user-attachments/assets/7ca30b7d-41a7-4007-ae4f-b60cef7a63d9)
](https://github.com/user-attachments/assets/7afbefe2-7b24-4a37-83b0-41371e6b359f)
