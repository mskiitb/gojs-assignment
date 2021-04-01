# gojs-assignment
Implement a decision tree by using GoJS. Implement a PDF-generator and insert the user-input values from Gojs to print/download the PDF with some static text.


    Implement a decision tree by using GoJS.
    Mission: Ask one question to a user with multi-option
    answer. Depending on which option the user chooses -
    show a sub-question. 

    Example:
    Are you married? QuestionID = 1003
    User input: Yes AnswerID = 1003
    How long have you been married? QuestionID = 1004
    User input: 5 years AnswerID = 1004

    Are you married? QuestionID = 1003
    User input: No AnswerID = 1003
    Will you ever get married? QuestionID = 1005
    User input: No AnswerID = 1005

    Implement a PDF-generator and insert the 
    user-input values from Gojs to print/download
    the PDF with some static text. 

    Example:
    Static text
    We asked the user if he or she is married. The user replied {{AnswerID:1003}}. 
    I have been married for {{AnswerID = 1004}} years
