# Sunny
Web scraping and text analysis of Always Sunny in Philadelphia episodes

This project is relatviely straightforward; the code open up a webpage that contains links to the script for each episode of Always Sunny in Philadelphia. It then opens the link for each episode and extracts the text (the nodes containing the links and the episode text were determined by using Selector Gadget). From here, the scripts are saved into individual text files in the directory, and I compile all of the text into a Corpus. All of the text is made lowercase, and punctuation and stopwords are removed. I tried stemming the scripts, however this returned many incorrect words because of all of the strange text used in the show (clickety, clackety, popdepop, etc.). 

