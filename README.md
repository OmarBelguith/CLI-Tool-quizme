## Quizme

A CLI too that will help to test knowledge.

```sh
quizme
```

- Ask a question
- Evaluate answer or have me self-evaluate
- Log the results

```sh
quizme --add
```

- Start a dialogue
- Ask me for a question
- Ask me for the answer
- Store for future uses


## What do I need?

- Parse Arguments
- Interactive command line
- Persist my data - using JSON
  - Reading/Writing from the file system
- Global script
- self-evaluating or auto-evaluating

## Data Structure

* id: Integer
* question: String
* answer: String
* created: String (date)
* lastAsked: String (date)
* lastAnsweredCorrect: Boolean


## What's Next?
- [ ] Load Questions from a free API: maybe quizme --fetch
- [ ] Try to continue for next question if user wants to
- [ ] Store a score for the user
- [ ] make it as MCQ