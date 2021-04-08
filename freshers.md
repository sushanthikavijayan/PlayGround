# Coding Challenge For Freshers
Finahub is hiring freshers as interns. To apply for internship you need to take the coding challenge given below.

## Trivia Quiz HTML Page
Create a HTML page that will display multiple choice quize using the data from the Open Trivia DB API given below.
 <pre>
 https://opentdb.com/api.php?amount=10&category=9&difficulty=easy&type=multiple
 </pre>

The format of the data return by the API is as given below:

<pre>

{
    "response_code": 0,
    "results": [
        {
            "category": "General Knowledge",
            "type": "multiple",
            "difficulty": "easy",
            "question": "What does the &#039;S&#039; stand for in the abbreviation SIM, as in SIM card? ",
            "correct_answer": "Subscriber",
            "incorrect_answers": [
                "Single",
                "Secure",
                "Solid"
            ]
        },
        {
            "category": "General Knowledge",
            "type": "multiple",
            "difficulty": "easy",
            "question": "The drug cartel run by Pablo Escobar originated in which South American city?",
            "correct_answer": "Medell&iacute;n",
            "incorrect_answers": [
                "Bogot&aacute;",
                "Quito",
                "Cali"
            ]
        },
        .
        .
	.
	.
    ]
}

</pre>`

### Required behaviour of the page
1. Each time the page is called new data will be loaded by making a call to the above API
2. Users of the page should be able to select their answers from 4 choices displayed below the question.
3. A "Check My Answers" button should be provided at the end of all the question to verify the answers selected by the user. 
4. When user clicks on the "Check My Answers" button, the page should display the correct answers, wrong answers and the score of the user.

## Technology Stack
Plain HTML and Javascript is sufficent to implement this challenge. That said you are free to use any javascript/web library like JQuery, ReactJS, Bootstrap etc.

## Submiting the code
**Step 1:** Fork [PlayGround Repository](https://github.com/Finahub/PlayGround)

**Step 2:** Add you code in a new folder

**Step 4:** Submit a pull request 



