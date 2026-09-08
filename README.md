# Quarkus AI

This git project is an umbrella project for Quarkus AI development.  Quarkus AI is a conglomeration of a few different
projects:

* LC4J
* Quarkus LC4J
* LangFuse
* Quarkus LangFuse

And probably more as time goes on.

## What's in this repo?

* High level issues and discussions that link to issues in the individual projects mentioned above.  Because
we are trying to coordinate a bunch of different repos, it's logical to have an umbrella repo for these issues.
* The Quarkus AI webpage. (Link to be added)
* Quarkus AI blueprint sample applications

## Contributing to Quarkus AI Web Page

We've been using our favorite coding agent to develop the web page.  ThContent will be defined in markdown files in the [website](website) directory
and synced to the appropriate .html files within that same directory.

When you want to change the content of the web page, please do your work in the corresponding markdown file.  Then use your
favorite coding agent to sync the markdown file with the .html file you want to change.

For instance, here's a prompt that is used
```java
sync rag.md markdown file with the RAG tile in index.html
```
Your coding agent should be able to do this easily and nicely.  We want to keep content in markdown files to make it easier to add
text content.