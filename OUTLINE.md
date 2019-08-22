# Creating outline of your article

You decided to write about something awesome and share it with the world. Cool! The best start is to actually shape what you want to write about and who is going to be your audience. You can take a look below and try to answer a few questions about your future contribution, or just skip to the actual outline.

## Topic & Motivation

### Theme / Topic

Title: **Building a static site with Gatsby.js + How to use GraphQL with Kentico Cloud**

* What is Static site generator and its benefits, what is Gatsby and how to use it with Kentico Cloud to reach that benefits.
* It is possible to use GraphQL with Kentico Cloud

### Target role

* Developers, CTOs

### Transformation

* Consider using static site for client projects
* Understand static sites benefits
* Static site does not mean a set of HTML files

## Outline

* What is static site generator
* What is GraphQL
* What is Gatsby (React)
* GraphQL vs REST API
* Generating static site
* Publishing static site
* Updating content on static site
* CI/CD of static site
* What does the static mean (no plain HTML from 90's)
* Kentico Cloud content structure ing Gatsby GraphQL content model
  * Start from content structure -> Reusable components
* Showcase on one complex model -> Company intranet with personal space
  * Possibly use Material descign framework for react (https://demos.creative-tim.com/material-dashboard-react/#/admin/dashboard)
  * https://app.kenticocloud.com/09fc0115-dd4d-00c7-5bd9-5f73836aee81/content-models/types
  * User name + surname -> connect in Gatsby 
  * rich text used to create a personal BIO, landing page
  * Multilingual links
  * Type -> Itemsl links
  * Element types resolition
    * Standard types (text, datetime, radio, taxonomy)
    * Linked element resolution
    * Rich text item reolution
      * embedded resolution in JS SDK
      * resolve rich text to a structured React components
* Interested in static site generator - meet us and the stand
* Deploy showcase and add the link + QR code to the presentation

### Expectations

Right after the teaser it's the right place to set expectations. Readers should understand what will the take away from reading your article. They can learn from your experience, learn about new technologies or tools, or they can get a boilerplate to speed up their development using specific technology stack. This way you show your readers you value their time and they will get something in return for their investment.

If you're not sure about wording in this part of your article, just use bullet points.

### Content

Now it's time for the actual content. Write down all the things you want to write about. Do not think about the structure yet, just put down all the things you want your readers to know about.

Take a look at this example of ideas related to Apollo and GraphQL article:

- explain what is GraphQL
- explain what is Apollo
- why is the tightly coupling of components and their backend code a problem
- why is the transfer of knowledge to a new developer going to be a problem
- why should they care about maintaining their code
- how can they generate data model schema
- how can they define queries and mutations
- how do they put it all together
- which tools should they use
- which JS frameworks can they use

Once you get all these ideas written down, you can organize them into a few sections of your future article:

1. Introduce the problem
    - why is the tightly coupling of components and their backend code a problem
    - why is the transfer of knowledge to a new developer going to be a problem
    - why should they care about maintaining their code
2. What is GraphQL?
    - explain what is GraphQL
3. What is Apollo?
    - explain what is Apollo
    - how can they generate data model schema
    - how can they define queries and mutations
4. Putting it all together
    - how do they put it all together
    - which tools should they use
    - which JS frameworks can they use

You see some sections of the structure have more points than others. Take a closer look at each of the sections and make sure you did not miss any important aspect your readers should know about.
1. Introduce the problem
    - why is the tightly coupling of components and their backend code a problem
    - why is the transfer of knowledge to a new developer going to be a problem
    - why should they care about maintaining their code
2. What is GraphQL?
    - explain what is GraphQL
    - **compare to REST API and describe GraphQL benefits**
    - **enables separation of front-end and back-end**
3. What is Apollo?
    - explain what is Apollo
    - how can they generate data model schema
    - how can they define queries and mutations
    - **note the difference between Apollo client and Apollo server**
4. Putting it all together
    - how do they put it all together
    - which tools should they use
      - **briefly explain Express and React**
    - which JS frameworks can they use
    - **link the boilerplate on GitHub**

The structure looks better and better! Sleep on it and try to polish it a few more times until you're happy with the result.

The main point of all this work is to ensure a good flow of content. It shapes your ideas so that you don't jump from one to another and confuse your readers. It is a critical step as good flow will make sure that already hooked readers will continue reading till the end of the article.

For more thorough information about writing perfect outlines please refer to following blog post: [How to Write a Blog Post Outline: A Simple Formula to Follow](https://blog.hubspot.com/marketing/how-to-write-blog-post-outline)


## Summary

At the end of your article briefly summarize what you wrote about and emphasize the key takeaways. If there is more to read on the subject, make sure to include links to that content here and point the reader in the right direction.
