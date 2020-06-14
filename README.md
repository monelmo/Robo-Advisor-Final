# Robo-Advisor-Final

# ROBO-ADVISOR-6.12.20

WELCOME TO E-Z STOCK ADVISORY. THIS PROGRAM WILL GIVE YOU STOCK INFORMATION AND INVESTMENT ADVICE BASED ON CURRENT MARKET  TRENDS. 
IMPORT FOLLOWING MODULES:

Prerequisites:
Anaconda 3.7
Python 3.7
Pip


SET UP:

First step is to obtain your API KEY:

    Please go to (https://www.alphavantage.co/support/#api-key) to receive your unique API Key. Once you have your API Keytake a moment to create a new file wihtin the repository called ".env" to securely keep your real API key.

    e.g.ALPHAVANTAGE_API_KEY="rando345"

PACKAGES:

    
    import re
    import json
    from dotenv import load_dotenv
    import os
    import csv
    import requests
    import datetime
    import matplotlib
    import matplotlib.pyplot as plt
    import matplotlib.ticker as ticker
    import datetime

TO START: 
    Oncce you are Done with this step please navigate from your command line to the repository and run the script: python app/robo_advisor.py