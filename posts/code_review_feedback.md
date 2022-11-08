# Giving and Receiving Feedback for Code Reviewing
As a rule of thumbs, I like to do my share of code reviewing as the first thing in the morning
when I start working. Since code reviewing is the fine art of adding value to the code writing by my dear colleges,
I try to keep in the back of my mind the following points when reviewing and receiving feedback:

* Be mindful. That code is going to end up in production in some point,
  so the more complex the code the more you should look into it
* The code has been writing by a human being and human beings tend to commit mistake
* Reviews are an opportunity to learn
* As a reviewer, before attacking someone's code, make sure to phrase your comments
  in such a way that you question the intent of the code and not the person coding skills
* As a person receiving feedback, remember that reviewing code takes a lot of effort.
  So, appreciate the feedback before being annoyed about the other person's comments

## Pedantic vs Correct
In my opinion, one of the worst dynamics during code reviewing, is having a pedantic colleague 
that continuosly point to inconsequential details, causing the attention to drift from
the actual issue or feature that is the subject of a pull requests. So how to avoid being 
pedantic without neglecting the code quality?
Firstly, you need to put in place a protocol within your team about using a formatting tool,
together with a testing framework and the best practices to follow for the target language.
Now, after checking that the code is correct by running the tests
(or whatever metric you team uses to establish correctness),
if you are still in doubt about certain functionality that may seem incorrect,
 ask yourself the following question:

**Can I explain why that piece of code is wrong?**

If the answer is affirmative and you have a solid argument, then go ahead and communicate it
to the person proposing the changes, otherwise let it go and avoid entering in a lenghty discussion
for unimportant details!


## Where can I find more about code Review?
Listen to [this great episode of Software Engineering Radio with Michaela Greiler](https://www.se-radio.net/2020/02/episode-400-michaela-greiler-on-code-reviews/)
