# Freenet

This book aims to popularize how Freenet works. To be short Freenet is a network allowing users to publish and retrieve files anonymously.

Quick list of what will be discussed in this book
* global structure of the network
* nodes behavior and what they do constantly
* node `location` and its impact
* WebOfTrust, how it works and its API
* what is the purge-db4o build
* Inventory of communication plugins such as Freetalk, FMS, Frost, Sone …
* abstract and explanation of the paper "Measuring Freenet in the Wild"
* Explanation of how Freenet stores its data on a node (`storage` and `cache`)
* Details about Freenet URL and key systems
* Explanation of the different ` core settings`

And in a second time
* Limits of the anonymous sytem, from a technical point of view, e.g. opennet IPs and DPI, attacks over the network
* some user recommandations about what to post (social aspect)
* Limits of come current implementations, to answer "Why is WoT so slow?"


This should give a general aspect of what I want to put in that book, if you see anything else to add please contact me.

## About this book

I want this book to be as easy to read as possible. It will talk about the technical aspects of Freenet in more detailed way than the official documentation. Citing the source code itself when it's possible.

This book is available in [English](https://www.gitbook.com/book/alexandrerio/freenet-internals) but also in [French](https://www.gitbook.com/book/alexandrerio/freenet-internals-french-version/details), my native language.

## About the author

I'm Alexandre Rio, I'm not one the Freenet developpers but I use it for many years.

I created this book because I was tired to look for hours for a simple question. Tired to look in outdated documentation and finally end up asking on IRC.

At the moment I don't have all the answers to my questions. I wrote the summary based on what I think is important.

Feel free to suggest other ideas.

## License

I still have to figure out which license to use. I want it to be as free as possible but I will also have to use existing texts and schemas, probably a GPL-compatible license.