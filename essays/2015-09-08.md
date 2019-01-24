---
layout: essay
type: essay
title: How do I ask a question?
# All dates must be YYYY-MM-DD format!
date: 2019-01-23
labels:
  - Questions
  - Answers
  - StackOverflow
---

## What makes a question... good?

  There has been a saying that you probably heard more than once that goes, "there is no such thing as dumb questions". Although this essay is specifically about asking smart questions, I would like to say that I agree with this statement (despite the ridiculous title). However, there are magnitudes about how to ask a question that helps your viewers be able to solve the problem that you are experiencing. Here, we will be exploring ways on how to ask questions on StackOverflow so you can recieve the maximum amount of help from fellow programmers.

## Pinpoint the problem!

  One way to get people to invest time into your problem is to ask questions that are precise and specific. Do you know those types of people in your math class that would ask the smartest person to show them the full process of a math problem? Please do NOT be that type of person. Rather, tell them where you are having trouble. You want the people you are asking to help solve a problem, not give you a lesson. Telling them solutions you have already tried also helps your viewers. This helps eliminate options and answers the viewer could tell you and can help you reach a solution much faster. This also saves the listener the trouble of going on a wild goose chase about how the problem needs to be solved.
  
## Choose a topic that is not too trivial

  StackOverflow is going to be where we will be posting these questions, so it is in your best interest not to post anything that you could find within minutes. It is recommended that you select a topic that is sophisticated enough to where it is out of the bounds of common or standard knowledge. Asking questions such as, "Is there a way to check the size of an array", are not going to cut it since this is very common knowledge within the field. Do not ask questions that can be answered within a couple seconds or minutes. Asking these types of questions can sometimes even lead to you getting ignored or even some snarky comments. 
  
```
Q: I have an array of integers, and I'm using the .push() method to add elements to it. 

Is there a simple way to remove a specific element from an array? The equivalent of something like array.remove(int);.
```

This here is an example of one those trivial questions. Although the answer to this question has helped many, you could have found the same answer on the developer's website for the programming language that you are using. You could have even saved the answerer some times from sending the link to the list of methods. 

## Be Detailed

  Describing the situation as much as possible helps viewers visualize your whole process and makes it easier to identify where your problem is. Giving snippets of your code and describing its function and purpose helps viewers reach levels of understanding much faster and will help you reach an answer quicker. That extra effort to make your problem digestible might even bring more attention to your cause.

```
Q: I already have a 404 handler in the SPA which works. The problem here is that Google for example links to old pages that no longer exist. While the user will see a custom 404 component, google will get, I assume, a 200 OK and continue to think the page is valid.

{
  path: '*',
  name: 'not-found',
  component: NotFound // 404
}

I have the server re-route to / and let vue handle the routing using History:

<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteCond %{HTTPS} off
  RewriteRule (.*) https://%{HTTP_HOST}%{REQUEST_URI} [R=301,L]
  RewriteBase /
  RewriteRule ^index\.html$ - [L]
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteRule . /index.html [L]
</IfModule>
 
It's a standard Vue CLI install with a php backend. PHP is currently only used for API calls.

Is there a way to have the server return a 404 status code in this scenario?
```

I have no idea what he is talking about, considering that I am only a beginner programmer at the time of writing this essay, but this is a more refined example of how to ask a question. The questioner gives the run down of what his code does, gives snippets, and then ends it off with wondering if there is a possible solution to this scenario.

## Conclusion

  When relying on others to answer a question that you have, it best to give them as much useful information as possible in order to give them an easier time to help you. Help them help you, as some would say. Eventually, you will be put in a scenario where you have to answer someone else's question, and you might be tearing your hair out because they asked you in one of the most unclear fashions possible. So now, take your curiosity to StackOVerflow and learn as much as you can! Just make sure when making a post, it is within the proper forum.
