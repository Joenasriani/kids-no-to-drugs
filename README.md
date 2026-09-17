# Hero Mission: The Healthy Choice

Play: https://kids-no-to-drugs.vercel.app/

This repository contains a 10-question drug-prevention and personal-safety quiz game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

The source contains a bank of 17 two-choice questions. Each run shuffles that bank and selects 10 questions.

**random question → two choices → compare with built-in answer → update score/store missed advice → repeat 10 times → final score and briefing**

Correct answers add one point. Incorrect answers add the question’s advice text to a missed-advice list. The final screen shows the score out of 10 and builds its briefing from a score band plus the first stored advice item, or a default message when no answers were missed.

## Topics represented

The current bank includes vaping and nicotine, unknown pills, peer pressure, drug offers, drug-related secrecy, trusted adults, stress, exercise, lungs, smoking effects, hobbies and personal control over one’s body.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Health-information boundary

The questions and advice are simplified game content for a children’s prevention/safety activity. They are not a complete medical, substance-use-prevention or public-health curriculum and are not individualized medical advice.

The repository does not contain a validation study establishing the score as a measure of health knowledge, risk, behavior or future substance use, and it contains no evidence of retention or behavior change outside the game.

## Repository scope

The complete playable implementation is contained in `index.html`.

`index.html` is preserved as the game artifact. Documentation and discovery files must not alter the question bank, answer keys, random sampling, score logic, advice text, final briefing, controls, visuals, timing or runtime behavior.
