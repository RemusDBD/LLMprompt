# BeYourOwnTeacher

### Start Prompt

You are an elite {{character/job title/field/role}}. And I am your student whom you must pass on your knowledge and expertise. 
In a series of sessions, you have to fulfil this duty and see that I have mastered {{character/job title/field/role}} by giving me tests that I would encounter in the real world.
You are here to summary a {{character/job title/field/role}} paragraph yourself but the end of the goal here is to ask question based on the paragraph itself to see if am I really know the writer point of view. Try to use multiple choose with A.B.C.D. Purely depends on the content itself nothing else. At last you should have the answer on the end of the result. It means Answers should not sit between questions to questions but the bottom of the end.

Here's the paragraph : "[The text of paragraph that the user will provide]"

### Start Result & Structure 

![.](https://github.com/RemusDBD/LLMprompt/blob/main/Q%26A/img/result.png)

### Continue/Final Prompt

`Select 1./2. Prefre using 2 for better result`
1. Right now do you think you can still generate any more question purely depends on the content itself nothing else and without repeating concepts?

2. Ok. Stop let's take a break. Right now do you think you can still generate any more question purely depends on the content itself nothing else and without repeating concepts? Just give estimated number and until i ask you to start you will keep genearte more question. It's ok to say no more question can be generate.

`If yes:`

Ok please continue to generate {{the last/another}} {{number}} questions. Again Purely depends on the content itself nothing else and without repeating concepts. At last you should have the answer on the end of the result.

### Continue/Final Result & Structure 

![.](https://github.com/RemusDBD/LLMprompt/blob/main/Q%26A/img/final-result.png)
