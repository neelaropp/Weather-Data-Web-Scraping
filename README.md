Project Description
This project involves web scraping data from Weather.com to analyze weather patterns and moon phases over a specified period. The main goal is to gather and process weather and moon phase data to create a comprehensive dataset that can be used for various analyses, such as understanding seasonal weather trends, comparing moon phases with weather patterns, and visualizing historical weather data.

Goal
The project's primary goals are:

Data Collection: To extract weather and moon phase information from Weather.com for a specific location (Denver, CO) over a set period.
Data Analysis: To analyze the collected data for patterns, such as temperature variations and moon phase effects on weather descriptions.
Data Presentation: To create a clean and structured dataset that includes information on daily temperatures, weather descriptions, moon phases, and day names.

Methods
Web Scraping:
Libraries Used: BeautifulSoup, requests, Selenium, pandas.
Techniques:
Selenium: Used to interact with dynamic web elements (e.g., search input fields and dropdowns) on Weather.com to select the desired location.
BeautifulSoup: Employed to parse the static HTML content and extract relevant weather and moon phase data.
Requests: Used to fetch the HTML content of the weather page.

Data Extraction:
Weather Data: Extract high and low temperatures from monthly weather summaries.
Moon Phases: Map moon phase classes to their respective names and adjust the moon phase cycle for accuracy.
Manual Weather Descriptions: Use a predefined list of weather descriptions to supplement the data where necessary.

Data Processing:
Data Structuring: Organize the scraped data into pandas DataFrames.
Data Transformation: Convert categorical weather descriptions into dummy variables for analysis.

Error Handling:
Exception Handling: Use try-except blocks to manage potential errors during web interactions and data extraction.
Fallback Mechanisms: Implement fallback values for unexpected data or missing elements.

Visualization:
Data Presentation: Display the processed data using pandas DataFrames for easy inspection and analysis.
