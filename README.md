# MeetingMinutesTranscriber
Open AI - Transcriber - Meeting Minutes Creator  

In this  project, I've focused on creating an automated meeting minutes generator using OpenAI's Whisper and GPT-4 models. This innovative application transcribes meeting audio, summarizes discussions, extracts key points and action items, and analyzes sentiment. This automated system aims to streamline the process of generating meeting minutes, saving time and ensuring that crucial information from meetings is accurately captured and easily accessible.

#Code Explanation
I start by transcribing the meeting's audio using Whisper, a model adept at converting spoken language into written text. For this, I use OpenAI's audio API to input the meeting's audio file and obtain a text transcription.

Once I have the transcription, I use GPT-4, OpenAI's advanced language model, to analyze and process the text. This involves creating separate functions for summarizing the transcript, extracting key discussion points, identifying action items, and analyzing the overall sentiment of the meeting. Each function is tailored to focus on a specific aspect, ensuring a comprehensive and detailed processing of the meeting's content.

The summary extraction function condenses the transcription into a concise abstract, retaining essential points and avoiding extraneous details. The key points extraction highlights the main ideas and topics discussed. The action item extraction identifies specific tasks or actions agreed upon during the meeting. Lastly, the sentiment analysis function evaluates the overall tone and emotion of the discussion.

Finally, I export these processed meeting minutes into a readable format, using the Python docx library to create a Microsoft Word document. This document includes headings for each section - summary, key points, action items, and sentiment analysis - providing a well-organized and accessible report of the meeting.
