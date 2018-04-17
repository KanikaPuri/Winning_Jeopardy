# Winning_Jeopardy
Jeopardy is a popular TV show where participants answer questions to win money. Let's say you want to compete on Jeopardy, and you're looking for any edge you can get to win. This is a dataset of Jeopardy questions to figure out some patterns in the questions that could help win the game.


Analysis (basics.pynb) from Basics File

Answer terms in the question
The answer only appears in the question about 6% of the time. This isn't a huge number, and means that we probably can't just hope that hearing a question will enable us to figure out the answer. We'll probably have to study.

Question overlap
There is about 70% overlap between terms in new questions and terms in old questions. This only looks at a small set of questions, and it doesn't look at phrases, it looks at single terms. This makes it relatively insignificant, but it does mean that it's worth looking more into the recycling of questions.

Chi-squared results
None of the terms had a significant difference in usage between high value and low value rows. Additionally, the frequencies were all lower than 5, so the chi-squared test isn't as valid. It would be better to run this test with only terms that have higher frequencies.
