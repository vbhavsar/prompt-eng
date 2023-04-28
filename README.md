
Notes from the course <a href="https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/">ChatGPT Prompt Engineering for Developers</a>.

# Lesson: Guidelines
## Principle 1: Write clear and specific instructions.

### Tactic 1: Use delimeters
- Triple quotes: """
- Triple backticks: ```
- Triple dashes: ---
- Angle brackets: <>
- XML tags: `<tag> </tag>`

### Tactic 2: Ask for structured output
HTML, JSON

### Tactic 3: Check whether conditions are satisfied. 
Check assumptions required to do the task.

### Tactic 4: Few-shot prompting
Given successful eaxmples of completing tasks
Then ask model to perform the task. 

## Principle 2: Give the model time to think. 

### Tactic 1: Specify the steps to complete a task.
Step 1: ...
Step 2: ...
...
Step N: ...

### Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion.

Simply asking if the answer is correct may lead to the incorrect answer. The model skims the answer.

E.g.: Determine if the student's solution is correct or not.

Instead, prompt: "Your task is to determine if the solution is correct or not. 
First, do the solution yourself.
Does the student's solution match the actual solution?
Student grade: <student grade>
"

## Model Limitations
Hallucination
Makes statements that sound plausible but are not true
Gives fictitious answers.

Use previously discussed tactics to reduce hallucinations.

# Lesson: Iterative prompt development process. 


