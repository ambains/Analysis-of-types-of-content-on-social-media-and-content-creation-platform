## Analysis-of-types-of-content-on-social-media-and-content-creation-platform

User engagement is a key metric for success on a social media and content creation platform. By analyzing datasets with content type and user engagement information, the top 5 most popular categories can be identified to help a social media platform to understand which types of content are resonating with their audience.

This analysis is of three datasets provided by Accenture on theforage.com from Social Buzz. Forage is a platform offering virtual work free experiences to showcase skills on your resume.

The three datasets include information on user engagement such as types of content categories, reactions on the content created by users, and the reaction types (sad, excited, heart).

The tool used to analyze the three datasets is Jupyter Notebook with pandas.

Steps of Data Analysis in Jupyter Notebook:
Data Understanding-The data model, which generated the three datasets with information on content categories, reactions and reaction types was reviewed and the unique identifiers were recognized for each dataset.
Data Assessment- The three datasets were imported into Jupyter Notebook, a tool that allows for programmatic assessment using Python, for data analysis. Jupyter Notebook contains both code and text cells that facilitate an easy step-by-step process of analyzing the data. The libraries used are pandas for programmatic assessment and matplotlib.pyplot and seaborn for visualizations.
Data Cleaning- A programmatic assessment was conducted on the three datasets (content, reactions, and reaction types) to ensure their quality. Using pandas, any identified issues with the data's quality or organization were programmatically cleaned and a cleaned, master dataset was created.
Uncovering Insights - The master dataset included scores for each reaction type within each category type. These scores were grouped and sorted in descending order, resulting in the top 5 content categories.
