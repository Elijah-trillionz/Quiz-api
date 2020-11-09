# Quiz-api
This is a section of the dev project currently in progress. With this repository we intend to put questions and answers on programming so as to use it as an api for the quiz in the parent project.
# Note:
Questions will be attributed to each contributers in the finished project, as well as a link to your profile or website; that is if you choose to leave your name on it.
# This is the guide on submitting questions.
In the code, there is a questions array of objects, each objects contain a key and a value of string / number except the "__options__" key which contains an array of possible options. The array of objects is further explained below
1. The __id__: The id of the question is dependent on the previous question, the code is clear enough to know the last question's id. So simply increment the last question's id by 1 to get your question's id.
2. The __quest__: The quest is short for question. Obviously, this is where you put your questions.
