# CAT-Citation-Assistive-Tool-

# Goals of Project 
The goal of this tool is to present information to users more efficiently than a Google Search and more reliably then with ChatGPT. 
Google Search can often be overwhelming and time consuming when trying to find a quick bite of info. 
ChatGPT is a new solution that is very time-efficient, but also error-prone and limited in its knowledge. 
I aim to solve these issues with CAT, a tool that offers accessible and easy to read material on any subject and presents content derived from reliable sources.

# Approach 
CAT is a user-friendly system that integrates ChatGPT to summarize topical information from Google by utilizing up-to-date web information as its source. 
The tool leverages the Google Search API and Google Suggest API to retrieve the information available on a subject and provide information on related topics. 
Instead of simply presenting the entire web page, like Google, CAT utilizes the GPT 3.5 Turbo API to quickly and efficiently summarize the text from these websites for the user.
In addition, it tailors the desired information to the user’s preferences using domain type and publishing time frame of the sources. 
All of this together allows the user to have more confidence that the information provided by ChatGPT is accurate and dependable while also presenting in-depth info in a quick and neat manner.

# Final Output of Product 
A user of our product can easily access all of the product's features via the simple and easy to understand UI. 
The user simply enters the topic they want more information on, and has the option to specify the domain and dates of the sources. 
When they click enter, the tool retrieves the top three sources from the google search API using their query parameters.
It then retrieves the essential information from these sites and then make a call to the OpenAI API to summarize the content. 
For the user, the three websites and their summaries are displayed along with a link to each of the sources.
Furthermore, the user will see three suggested topics if the user wanted to do further research on related ideas. 

# Running the Code 
After cloning this repo, simply run 'python main.py' to launch the website.
