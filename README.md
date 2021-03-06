# Master Yoda ~ Google Assistant

## *Api.ai + Actions on Google | SDK + Markov Chains = Master Yoda*

### *Goal*

My goal was to create a conversational UI that would generate unique quotes/advice based on a corpus off scrapped quote's that also included a set of quote's from Yoda. I wanted the conversational UI to be able have coherent conversations or at least give coherent and lengthy advice/quotes

### *Game Plan*

My plan was to use a mathematical structure called Markov chain's to model the statistical likelihood of a word in a quote being followed by some other word in the given quote. Then, I could use that statistical information to generate new quotes by choosing the first word (at random) and then choosing subsequent words with a frequency proportional to how those words are arranged in regards to the original quote. This will then give me text that will not only be unique, but will also share stylistic properties when compared to the original text.


### *Why?*

I'm interested in learning more about conversational UI & NLP because I believe in it's potential on how it can change the way we/users/customers interact with technologies in a more natural/efficient way.



### *Result*

My results suggest that generateQuote was able to effectively model and observe the created state using Markov Chains, which then made it possible for the system to get the probability of each word and it's successor fairly easily. However I've realized that the longer the quote that is generated, the chance's of it being coherent drops. 

## *Ok Google, Speak to Master Yoda*

###### *Available on Google Home, Android 6.0+ devices, Chromebook, and iOS 9.0+ phones*

![Alt Text](https://i.imgur.com/1REEDbg.jpg)

### *Next Steps*

This Assistant can be developed further in a number of ways.

- I would like to use some other statistical model that is more accurate to generate more coherent and dependable response's that can help engage users.

- I would also want to train the Assistant to learn how to discern the users state in regards to how they are feeling in the moment based on how they're asking for advice. So it can generate advice that's more empathic towards users
