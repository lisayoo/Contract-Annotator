# Contract Annotator
#### HackMIT 2018 project by Lisa Yoo and Kat Wicks || Runner-Up for Best Use of DocuSign's eSignature API

## Inspiration
Contracts are confusing! They're long, they have obscure jargon, but they need to be carefully read and understood. We created this tool in order to make this process easier by highlighting the most important parts of your contract so you don't miss them. Contract Annotator streamlines contract comprehension, and allows entrepreneurs, students, and all people who don't have the time or money to retain and wait for a lawyer to work with contracts effectively.

## What it does
Given a file of an unannotated contract, Contract Annotator uses NLP to find the most important parts of a document and return an annotated copy of the contract. It uses TextRank to select important parts of the contract using extractive summarization, augmented using domain knowledge regarding contract law and conventions in business documents. It also tokenizes sentences and runs a keyword, then generates a Word document with the appropriate highlight and exports it as a PDF to send back through email. Using DocuSign's API, it sends contracts to collaborators and keeps track of progress towards an agreement.

## What we learned
We learned about how hackathons work (this was our first one!), and about using OAuth to access company APIs. Furthermore, this is the first time we've gone into the contract space, and learning about the ins and outs of it from a legal perspective was really interesting.

## What's next for Contract Annotator
We want to build up the UI to make the experience and usage more smooth and easy to control. We want to incorporate an email interface, where like the workflow with lawyers, you can email your contract to us, and our script will return the annotated version in DocuSign.

