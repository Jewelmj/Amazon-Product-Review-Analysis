about: this project is about automaticly analysing the product review on amazon.

ideation: the last time i bought a amazon product, i had to go through the pains taking prcedure of reading the reviews one by one, 
            i wanted to solve this gap in the market by using the skills i have at the time of devolopment.

time of devolopment: during my first year of B-tech, 2022.

how it works: it uses selenium to "extract data" from amazon. then it preproces the data and plots a "word cloud" 
                for analysing whether the product is good or bad. along side the regular word cloud it plots a 
                "ai powered" wordcloud which analyses the text in a sentence and colors them based on whether they are good or bad.

technologys: it uses selenium to scrap the web. thinker for the ui. tensorflow to train a custom model. wordcloud to plot the wordcloud. pandas and nlp for preprocessing.

pros: Its a unique tool.

cons: it trains the model while the app is running which increases the time the app takes to start running.

here is a word could plot without ai: https://github.com/user-attachments/assets/4618138c-6918-4284-b2b1-457a0625bd14

here is a word could plot with ai: https:https://github.com/user-attachments/assets/50f2961c-97a8-4af8-b35d-57b54066c7b7
