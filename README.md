I created a model(bitcoin_model) using RNN which predicts the price of bitcoin(price at upcoming 5 days).
As deep learning algorithms are always data hungry, my "DataAdderInBTCfile" file is scraping www.coindesk.com/coindesk20 website and adding data in csv file using Beautifulsoup 
library.I have put a schedular,who runs this(DataAdderInBTCfile) file at 00.00 every night.
"Bitcoin_model ka code 15 din me chale" file is basically another schedular who runs "bitcoin_model" file in every 15 days.So my model again gets trained in every 15 days on 
the entire data(including new 15 days data).
