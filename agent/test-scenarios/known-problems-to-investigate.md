# Problems to investigate

## Matching Question Response

In match question responses, even if the user provides the correct answer, the assistant will consider the answer incorrect if it is not in the expected format.

**Example:**

- **Expected answer:** A-1, B-2, D-3, C-4
- **User answer:** A1, B2, D3, C4

The assistant will consider the user's answer incorrect due to the formatting difference.


## Repeating the "Choose the question type" Section

In some scenarios where the user selects a question type option, the "Choose the question type" section is repeated.

## In some cases, for multiple-response questions, the assistant marks the user's response as incorrect, but the explanation indicates that the answer is actually correct.

## In some cases, for multiple-choice questions, the assistant marks the user's response as incorrect, but the explanation indicates that the answer is actually correct.

## If I ask questions coming from "preparation mode" the assistent is losing the variables values and changing the domain

## If I ask questions coming from "preparation mode" the assistent is losing the question type variable value

## In PRACTICE MODE when I try to change the question type, it is loosing de domain selected before

## In Practice Mode if I use lowercase to answer, it is considering worg even it is correct