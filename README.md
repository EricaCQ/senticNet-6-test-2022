#senticnet-6-test-2022

#This repository contains all the tests for SenticNet 6 polarity performance for four Brazilian Portuguese Datasets:
#MQD;
#SADIE;
#TOPIE; 
#TWEET_SENT_BR

#Request the API key at: https://docs.google.com/forms/d/e/1FAIpQLScY_pszqe8fKoqNjrG5oKwwTgkNpXuTZb7MU6JbbLopSKpSng/viewform
#Source: https://sentic.net/api/

#The main commands to tun the test are shown below:

LANG = 'CHOOSE LANGUAGE. EX: 'PT''
APIKEY = 'YOUR API KEY'
APIURL = 'https://sentic.net/api/' + LANG + '/' + APIKEY + '.py?text='
FILENAME = 'YOUR FILE'
