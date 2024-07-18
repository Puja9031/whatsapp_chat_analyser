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
