# Interview Process Overview

1. Initial Interview
   - An interview to discuss fundamental LLM / RAG related concepts.
2. Technical Assessment (Current Stage)
   - Complete a take-home technical assignment.
3. Technical Assessment Interview
   - An interview to discuss your implementation and a few more LLM / RAG related concepts.
4. Culture Interview (TBD)
   - Discuss company details, work experience expectations for both you and the company.

# Technical Assessment

**Deadline:** 2 days from when you receive the assignment

**Estimated Time:** 3-4 hours of focused work

**Tech Stack Requirements:** python

## Note

**You cannot use any high level LLM frameworks like langchain, crewai, etc for this task. You can only
use standard python libraries for your implementation.**

- You can use other python libraries like pydantic as part of your code.

- You can only use external APIs for `standard LLM calls` (directly use the APIs from the labs),
  `embedding generation`, `vector stores`, `evals` and `logging / experiment tracking`.

- You will be evaluated on both the quality of the technical implementation as well as your ability to
  perform well thought out experiments and cleanly track your evals across the different experiments.

- Let me know if you need API keys for any LLM vendors and I would be happy to provide them for you.

## Task Overview

### Part 1: Set up GitHub

1. Setup a private github repo with the following naming convention - `connectiq_ds_technical_assessment_<YOUR_NAME>`.
2. Add me as a collaborator to this repo - my github username is `skrishnan99`.

### Part 2: Build a RAG chatbot

You will be building a RAG chatbot that can discuss the book - `The Hard Thing About Hard Things` by
Ben Horowitz.

You can find a pdf version of this book in this repo - `the_hard_thing_about_hard_things.pdf`.

- The end output should be a python script where a user can ask a question about the things discussed in
  the book and the chatbot responds with accurate answers.

- Each response should include references from the book. It should provide specific excerpts along
  with their page numbers that the chatbot used as reference.

- It should support multi-turn conversations.

- Try different approaches and track your results across each experiment. In the next interview stage,
  we will discuss your experimental process. This includes:

  - Which experiments you tried
  - How you evaluated each experiment
  - The results you observed
  - How these insights informed your next approach

- Try to implement at least 3 different experiments as part of your implementation.

## Support During the Assignment

- If you have any questions regarding the overall task itself, please create an issue in this
  repository and tag me. I will try to check and respond every few hours.

- For questions regarding your particular implementation and any guidance there, please create an
  issue in the private repository you have set up between the two of us and tag me.

- If you have not gotten a response within 24hrs, please feel free to email me about it.

## Submission Requirements

- Add all source code pertaining to this task on the private GitHub repository you have set up between
  the two of us.

- Create a file named `README.md` in your repository with instructions on how to run the script and
  ask questions about the book.
- Add a file called `NEXT_STEPS.md` that discusses additional experiments/approaches you would like
  to try if you had more time.

**Once you have completed the assignment, please send me an email saying you have completed the assignment.**
