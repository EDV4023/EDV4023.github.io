---
title: "Expert Exports"
excerpt: "This website attempts to solve the uneven development of wealthy and poor states by using a website that recommends a developing country to another developing country based on export and import similarity.<br/><img src='/images/expert-exports.png'>"
collection: projects
---

The website utilizes export and import data about developing countries to recommended them other like-minded countries, that align with their commercial objectives. The website was built using python's Streamlit library, a powerful, streamlined UI development package. I extracted the data by using the web scraping libraries Requests and BeautifulSoup (bs4). Using the export and import data from the website, I converted a python dictionary with the data into a csv file using Pandas. Subsequently, I read and compared the export and import data of multiple countries, examining the degree of similarity they shared. Finally, I wrapped up all parts of the program into an integrated Streamlit GUI.

Check It Out
---
[Github Repository](https://github.com/EDV4023/Expert-Export)  
[Try it Out](https://expert-exports.streamlit.app/)