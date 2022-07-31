# job_application_autofill
 
It's a personal project just for the personal interest. I used Selenium to create a script to for autofilling job application webpages.

The program will first identify all the input and select tags in HTML and find their labels (and options for select). If the label (question) matches existing ones in the info.csv file, then it will fill in the field automatically. Otherwise, it prompts the user to enter the answer and then it will store it to the info.csv file for the future.