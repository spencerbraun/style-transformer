# Model Date: 3/6/30

## Notes:
- Learning rate 0.001 (for both models)
- Ran for 500 iterations
- Model logs saved in model_logs

## Output Notes:
- "What the Dickens?" -- the model is latching onto the word "defarge", and probably using this to try to fool the discriminator
- The model appears to be learning advanced synonyms for vocabulary even if the general sentences are gibberish
- Stopping early and increasing the learning rate may have contributed to poorer results (likely more the former)
