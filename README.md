# design-reddit-frontend-challenge
Growth Whiteboarding Challenge: Design Reddit

The scope of this challenge is to design the architectural scaffolding of the Reddit homepage. This is meant to be a whiteboarding question.

https://www.reddit.com/

Assume that we have an API that allows for retreiving a list of 100 Reddit posts with the following metadata...

```
  {
  "upvotes": [integer], 
  "original_poster": [string], 
  "title": [string], 
  "comment_count":[integer], 
  "link": [string],     
  "time_posted": [timestamp], 
  "country": [string], 
  "content_type": [string],
  "subreddit": [string]
  }
```

Though we use React at Shipt, can talk about this page in the context of any framework that you are most comfortable with. Be prepared to discuss:

1) How to construct and layout components in a clean and reusable fashion
2) How to maintain app state
3) How to interact with the API layer
4) How you would allow for front page sorting by "hot", "new", "upvotes" and "country"
5) How you would allow for an automatically-updating homepage based on real-time data (i.e. the most upvotes make a post rise to the top)

Remember: this is a discussion and there is no one right answer. 

Best of luck!

