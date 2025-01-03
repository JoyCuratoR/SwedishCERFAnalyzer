# Analyze your Swedish Language Learning Materials for their CERF Level

This app allows you to input any text that you're using to learn to read Swedish (so long as you have the text/transcript or you transcribe it) to help you determine what level the material you are reading is at. 

# How is This Measured?

Here's a detailed explanation of how the analyzer works.

<b>Word Lists Organization</b>
```
A1: ~50 most basic words (pronouns, basic verbs, numbers, essential nouns)

A2: ~40 intermediate words (common verbs, time expressions, descriptive adjectives)

B1: ~30 advanced words (abstract concepts, academic terms, complex conjunctions)

B2: ~30 sophisticated words (technical terms, formal expressions, complex verbs)
```


<b>Analysis Process</b>
The analyzer uses multiple metrics to determine the CERF level

<b>a. Word Level Distribution</b>

- Counts how many words appear in each CERF level list

- Calculates percentages of words at each level

<b>b. Sentence Complexity</b>

- Average sentence length

- Lexical diversity (unique words divided by total words)

<b>Additional Metrics Displayed:</b>

- Word count

- Unique words

- Average word length

- Sentence count

- Average sentence length

- Lexical diversity

- Word distribution percentages

- Average sentence length

- Lexical diversity (unique words divided by total words)


<b>Level Determination Algorithm</b>

The text is classified based on these thresholds:

```
C1: B2 words > 5% OR (avg sentence length > 20 AND lexical diversity > 0.7)

B2: B1 words > 10% OR (avg sentence length > 15 AND lexical diversity > 0.6)

B1: A2 words > 15% OR (avg sentence length > 12 AND lexical diversity > 0.5)

A2: A1 words > 20% OR (avg sentence length > 8 AND lexical diversity > 0.4)

A1: Default level if no other criteria are met

```

