# Datahacks 2021: Religious Text Analysis
Team: Lauren Sidarto, Kent Utama

In this report, we analyzed the word counts of different keywords from different religious texts. The dataset includes 8265 features, all of which are words from the text, and 100 rows, where each row represents a chapter from one of eight religious books. Each entry in the dataset is an integer that indicates the number of times a word appears in that chapter; a "0" indicates that the word was not used in the chapter.

Given the data, we aimed to look at any the similarities and discrepancies between the word counts of the given texts, analyze how these patterns may reflect parts of a corresponding ideology, and similarly, compare the words used in the religious texts of religions that have a strong historical affiliation.

Additionally, from a technical standpoint, we aimed to utilize the python programming language to build a machine learning model that predicts the book any given chapter is from, given the chapter's word counts. The dataset was also used to make use of other data analysis and visualization toolkits and packages, such as Pandas, Scikit-learn, and Tableau, to best perform exploratory data analysis (EDA) techniques.

---

Prompt (as given):
1. Look and explore through the data. Organize your findings and observations in a way that will help you visualize certain patterns.
2. Extract trends and patterns from the data using:
a. Data visualization: Create an infographic with no less than three charts (that can
help you better understand the data).
b. Hypothesis/experimental testing: Explore the data and come up with a
hypothesis.
3. Use data visualization tools (Python libraries, Tableau, etc.) to present the trends you
found. Create an infographic with no less than three charts.
4. Using your findings, determine:
a. the top 20 words that appear in each book
b. the top 20 words that appear through all books
5. Three of the books (Proverbs, Ecclesiastes, Wisdom) are part of the Old Testament, but
are spread out in time of founding. Define a model to determine how the wording has changed from the Book Of Proverbs to the Book of Wisdom. This is an open-ended question, so you may choose to answer it in any manner appropriate, as long as you use a machine learning method.
6. Both Buddhism and Taoism have influenced each other. Propose a hypothesis to find out similarities that can be drawn between both texts in terms of word usage? Can we extend the word usages in the texts to their practices? Justify.
7. Prepare a report containing your results from the analysis. It should contain the following: Intro, data cleaning/pre-processing, visualizations (at least 3), analysis, proposal, conclusion.

---

This was my first data science hackathon--my primary role involved using the scikit-learn library to create a machine learning algorithm that determines how the wording between the books of Proverbs, Ecclesiastes (both in the Old Testament), and Wisdom (in the Deuterocanon) have changed. All three books are spread out in time of founding, but are supposedly written by the same author, and are about the same topic: wisdom.

This task was a challenging one, as I had to teach myself foundational machine learning principles, and how to use sklearn, while managing the time zone difference between me and my partner (this hackathon took place virtually, as per currennt events). That said, this was an overall fun and valueable experience; it tested my flexibility, resillience, communications skills, while allowing me to pick up lots of useful skills on the fly, like being able to read documentation efficiently.

Now with the steep learning curve of fundamentals out of the way, I can forsee next year's datathon being a much smoother--possibly even more professional--experience.
