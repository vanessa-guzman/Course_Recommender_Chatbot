# Course Recommender Chatbot

**Tools**: Python, Supabase, n8n <br>
**Python Packages**: Pandas, BeautifulSoup, Selenium <br>
**Skills**: Web Scraping, Data Cleaning, AI Agent Prompting <br>
**Objective**: Create a chatbot that will help students find courses that fit their interests and that are open to them based on completed prerequisites. <br>

**About the data**: The data was obtained via web scraping. Information such as course code, course title, description, and requisite was obtained from the Borough of Manhattan Community College [course catalog](https://bmcc.catalog.cuny.edu/courses).

**What was done**:
* Web scraped course information using a combination of BeautifulSoup and Selenium.
* Cleaned the data using Pandas.
* Imported the data into Supabase.
* Prompted AI agent to create a chatbot in n8n.
* Connected Chat Trigger node, which starts the chatbot interaction, and Supabase node, which contains all the course information.
* Connected Chat Model and Memory for generating accurate responses.

**Link to [web scraping](https://github.com/vanessa-guzman/Course_Recommender_Chatbot/blob/main/bmcc_courses_webscrape.ipynb) code.** <br>
**Link to code that [combines course information](https://github.com/vanessa-guzman/Course_Recommender_Chatbot/blob/main/bmcc_unioning_all_courses.ipynb).** <br>
**Link to [JSON file](https://github.com/vanessa-guzman/Course_Recommender_Chatbot/blob/main/Course_Recommender.json) containing n8n workflow for creating chatbot.**
