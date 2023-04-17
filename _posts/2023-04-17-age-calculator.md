# What's Your Age? 

Today, we started another FEM task - [age calculator](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q/hub). This was quite interesting and follwing was the approach followed:

1. Firstly, I made frontend design for the mobile version and then made it for the desktop part
2. Javascript Part begins..
3. firstly, took all the input fields and labels associated with them
4. condition applied to check whether the date field is empty, error class applied if true which turns all the fields red with an appropriate error msg
5. other conditions in date applied -> it should be greater than 1 and less than 31 and further day consitions according to month applied
6. even the leap year condition applied
7. format of DD for date also checked
8. now, empty month field checked, valid month number checked, format checked and errors displayed when invalid
9. lastly, year checked for empty field and format and year > 1000 applied
10. leap year codition associated with this field too
11. future dates handled
12. now that all the validations are covered, calculation part begins to show up age of the person in years, months and days till now
13. new date object and dob object from inputs created.. it has a month (0-11) so modifications done accordingly
14. years difference calculated and for months>currentMonth, added a year
15. months difference calculated 
16. days difference calculated
17. in leap year, -1 month and +7 days

That's it for the task.. It seems simple but through consistent hits and trials and the valuable feedbacks of my mentors, I could make it! Truly, I've gained more confidence with the completion of this task :D

The code can be found [here](https://github.com/jazzcodes/age-calculator-app).
The site is active [here](https://jazzcodes.github.io/age-calculator-app/).

Started JS30 Task-3, would continue it tomorrow.

Till then, Byeees! :D

