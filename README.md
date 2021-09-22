# YouTube-Transcript-Summarizer-
Please Note: This project is in process of creating a chrome extension.
Basic Idea: A Chrome extension that will make a request to a backend REST API where it will perform NLP and respond with a summarized version of a YouTube transcript.

Main Project: HuggingFace's transformers library is used in Python to perform **abstractive text summarization** on the transcript of the YouTube API.

Hugging Face Transformer Library(https://github.com/huggingface/transformers)
YouTube API(https://github.com/jdepoix/youtube-transcript-api)

**Abstractive Summarization:** The model produces a completely different text that is shorter than the original, it generates new sentences in a new form, just like humans
do. 

The project could have been approached in many ways, for eg, converting video into audio and then transforming it to text, but this would require a lot of memory and processing. The second one is by generating subtitles, in this, we have to first make the text meaningful and then try different algorithms.
