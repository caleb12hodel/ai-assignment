This assignment took me less than an hour to complete, and went smoothly. I utilized the Copilot-instructions.md file to create general instructions for the entire project. In this file, I prompted Copilot to act as an expert in both credit card fraud detection and Python development. I think this technique really helps to streamline the purpose of the project to Copilot, and effectively communicate how I wanted my notebook to look.

There were a lot of concrete benefits I noticed from using Copilot to assist with the AI assignment. I was able to create graphs very quickly that displayed exactly what I was asking for. Once I gave Copilot the context of the data and the column names, it only took one iteration per graph. I would prompt Copilot to create the desired graph style with the desired columns and then verify visually that the graph mirrored what was in the example notebook on Brightspace.

With the ease of using copilot also comes dangers. I see how it is very easy to get working code that you do not understand. Even for this assignment, some of the ways that copilot chose to make graphs was new to me. Copilot used shapes and colors in ways that I previously have not. It is very tempting to treat the code Copilot generates as a black box. With any abstraction the danger is that you do not understand the reasoning behind the tools and code you are using. Understanding why you do what you do remains a critical part of any work flow— data science or not. We must be credible in what we do, which means having the ability to explain and justify design decisions. 

I did not have to verify any output for this project beyond a simple visual comparison of output. Copilot did a really good job generating code that worked the first time. I also think this is because I was able to effectively give copilot adequate context of the data we were working with. 

here is my `copilot-instructions.md` file:
# Credit Card Copilot Generated EDA Instructions
For this assignment, I am going to prompt you to do and exploratory data analysis on credit card fraud using the data in [./card_transdata.csv]. You are to become well acquainted with the format of this data in order to help me generate the exact data analysis I desire. You are an expert programer in python, and know all of the best practices that come with using pandas for data science. Additionally, you have domain knowledge on credit card fraud, and are an expert in identifying fraud and helping others use data to identify fraud. 

# Response Formats
If you, copilot, have an indepth response that consist of many parts of complicated code, do not give it all at once. I would like you to give chunks of code that incrementally help me achieve my EDA goal. The key word in our interactions to move onto the next step will always be 'mango'.

# Code and Markdown Format
For cell of code that you generate for me, also produce a markdown cell above it outlining key elements of my prompt that resulted in the code you generate. 

# Goal
Combine your expertise in python coding and credit card fraud to deliver an exploratory data analysis that is satisfactory to me. 

