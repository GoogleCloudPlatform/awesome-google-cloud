# How to become a contributor

## Contributor License Agreements

We'd love to accept your awesome suggestions! Before we can take them, we have
to jump a couple of legal hurdles.

Please fill out either the individual or corporate Contributor License Agreement
(CLA).

  * If you are an individual writing original source code and you're sure you
    own the intellectual property, then you'll need to sign an [individual CLA]
    (https://developers.google.com/open-source/cla/individual).
  * If you work for a company that wants to allow you to contribute your work,
    then you'll need to sign a [corporate CLA]
    (https://developers.google.com/open-source/cla/corporate).

Follow either of the two links above to access the appropriate CLA and
instructions for how to sign and return it. Once we receive it, we'll be able to
accept your pull requests.


## Adding an awesome link to this list

1. Sign a Contributor License Agreement (see details above).
1. Fork the repo, and add the link to the `README.md` file. See [the general
   instructions for adding something to an awesome
   list](https://github.com/sindresorhus/awesome/blob/master/contributing.md#adding-something-to-an-awesome-list)
   for more detailed instructions for how to do this.
1. Submit a pull request.

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a
  duplicate.
- Make sure the list is useful before submitting. That implies it has enough
  content and every item has a good succinct description.
- Make an individual pull request for each suggestion.
- Use [title-casing](http://titlecapitalization.com) (AP style).
- Use the following format: `[List Name](link)`
- Link additions should be added to the bottom of the relevant category.
- New categories or improvements to the existing categorization are welcome.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request and commit should have a useful title. An example of a
  useful title would be "Add 'Foobot', a bot running on Kubernetes to reply
  with a random variable name". This is useful because it includes the name of
  the awesome thing, how it uses the Google Cloud Platform, and what it does.
- The body of your commit message should contain a link to the awesome thing.

Thank you for your suggestions!


## Adding a heading?

We use [DocToc](https://github.com/thlorenz/doctoc) to maintain the table of
contents.

    npm install -g doctoc

Command to regenerate table of contents:

    doctoc --title '**Table of Contents**' README.md
