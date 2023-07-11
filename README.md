# Chatbot-for-Data-Science
In this project, I want to explore what people are dicussing about at popular data-science related posts on Reditts. 

I used Reditt API to extract comments from Top 100 posts within subreddits "MachineLearning", "artificial", "data". 

I then used Langchain to create a vector index to store these comments in order for ChatGPT AI to retreieve later.

Finally, I loaded the vector index into OpenAI to finish the chatbot. 

How this Chatbot would work is that when it is given a question, it will search relevant input (comments) within the vector index, and then provide answers based on input it deemed as relevant and retrieved. 
