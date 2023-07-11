
# Automation Time

- In the CS253 (Introduction to Software Development) Course, I learned to write bash scripts for basic tasks, such as searching for strings through files using the grep command, which would have otherwise taken too much time if done manually. 

- After that, I wanted to know if we could control the keyboard and mouse using scripts to automate some basic tasks...

- Then I came to know about Selenium and tried to experiment with what can be done using it
## ChatGPT

- Isn't it cool how using the ChatGPT API Key can get responses to the queries just by using a few lines of code?

- But this free key is valid only for the first 60 days of our account, which might have expired long ago. ( I came to know about this key long after my expired :( )

- To simulate the above, I wrote a few lines of code in Selenium, which would post my queries to ChatGPT in Chrome via my regular account and read the responses into the code.

- To skip the process of login etc., I used to open the Chrome Browser with my profile already loaded in Chrome

- Although the API also has several other benefits, this also wasn't a bad option
## Train Ticket Booking

- For those who use websites for ticket booking, I am sure you would know how uncertain we are about getting a confirmed ticket when booking a Tatkal ticket. 

- While trying to automate this, I got stuck at one point where  Captcha was required to log in. Then Pytesseract, an OCR Library in Python, came to the rescue. Since the Captcha used on the website was simply an image of letters, so using this, I was successfully able to decode it.

- Till now, I have written the code to log in, enter the journey details and search for trains.

Work in Progress...
