Web Scraping and Query Model
The following code allows user to scrap data out of any web page through the URL provided. In our case we have chosen the ICC World Cup 2023 Wikipedia Page. For this project, only single web pages have been considered.

Once data has been scraped, Langchain models have been used to create chunks and embedding for each document. OpenAI provides API key to their turbo models which can be obtained free or through a paid subscription. This key has been used to initialize the chat model and consequently the Langchain - Conversation Retrieval Chain. 

NOTE - The secrete API key has been omitted in the code. If you would want to run the code, you will have to generate your API key from "https://openai.com/".
