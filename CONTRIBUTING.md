# How to Contribute

Thank you for your desire to contribute. Any help in spreading or improving the information that is contained here is appreciated. That said, we have a few guidelines on what is accepted and the norm here.

Here are a few resources:
* [Discord](https://discordapp.com/invite/zUbNX9t) in channels `#learn-java` and `#learn-java-discussion`. Run `?rank Java Student` in the `#bots` channel to gain access. Please look look at the rules and the topic for each channel to be sure that your message is in the right place and will find help the fastest.

## Definitions:

**Content Article**: An article that is focused on teaching a concept. Content articles are the main body of the chapter, while non-content articles such as indices, reviews, and exercises are there to reinforce the body.

# Contributing:

We accept corrections and new submissions for tutorials. For these, we use Pull Requests. For more information on Pull Requests, please read [this](https://help.github.com/articles/about-pull-requests/). 

## Code Corrections:

If the code in a tutorial will not compile or has an error, feel free to submit a code correction. Please include a clear list of what you've done, and link the issue (or create one) that is fixed in the pull request ([see here](https://blog.github.com/2013-05-14-closing-issues-via-pull-requests/)) or in the commit. Make sure that your commits are atomic (one issue/feature per commit).

Example commit message:
```
$ git commit -m "Fixes #0
>
> Add missing semicolon."
```

## Language Corrections:

If the language in a tutorial is confusing or in improper english, feel free to submit a language correction. Please include a clear list of what the issues you saw were (create an issue!), and how you fixed them. Make sure that your commits are atomic (one article per commit).

Example commit message:
```
$ git commit -m "Fixes #0
>
> Convert confusing sentence structure to parallel sentence structure."
```

## Tutorial Articles:

All tutorials follow this same template:

```md
<!-- Header -->
<h1 align='center'>0.0 Title</h1>
<p align='center'><em>Subtitle</em></p>
<p align='center'><a href='./CHANGEME.md'><<</a> | <a href='../readme.md'>Index</a> | <a href='./CHANGEME.md'>>></a></p>

---

<!-- Content -->



<!-- Footer -->

---

<p align='center'><a href='./CHANGEME.md'><<</a> | <a href='../readme.md'>Index</a> | <a href='./CHANGEME.md'>>></a></p>

<sub>© 2018 Author All Rights Reserved</sub>
```

Each article should include examples for what is being illustrated, both with a real-world explanation and code samples, if applicable. Each content article should also be finished with a Review section in which the content that has been outlined is summarized. Please read through a few of the articles that already exist to get the hang of it.