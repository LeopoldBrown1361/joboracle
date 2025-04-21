# answering short questions
short answer questions like, 'why do you want to work here', 'what is your greatest strength'.

## GPT prompt
im designing an AI to answer short form interview questions like, 'why do you want to work here', 'what is your greatest strength'. There will be plenty of scaffolding and prompt design and iteration on the question to get to the final product. I'm looking to get a list of all possible context that I could reasonably provide the model for it to write the best cover letter.  

For inputs, here's a list of all possibilities:
1. User's cover letter
2. Resume
3. Personal interests
4. Core values and motivations
5. Job description
6. Company description
7. Cover letter specific to job or industry
8. long list of work examples (tell me about a time where...)
9. list of past work with links 
10. LinkedIn profile
11. List of awards, achievements, etc.
12. Career goals
13. Example of a non-user good CL
14. Writing sample from the user

# desired traits/implementation
1. grading system for cover letters to give a score based on a rubric.
2. picks out which context is needed by the writer bot, ans summarizes it down to the useful parts. 

# meta/random thoughts
Have a grading system setup with examples (like the 300 question mcq test grader) and have it go through and grade each cover letter. This would allow me to test and directly compare different setups/architecture for creating a good cover letter, and would also allow me to then run a cover letter generation prompt multiple times and select the best rated one in the end.

# scaffolding structure
