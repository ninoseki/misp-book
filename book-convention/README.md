<!-- This is a comment.
If you plan on contributing to misp-book, welcome and enjoy.
In case of any and all questions, feel free to join our gitter:
https://gitter.im/MISP/MISP
For Aiur! -->

---
description: Convention Used in MISP-Book
---

# Convention Used in This Book

`code block or value`

* Used for variable, function or menu names in MISP.

## Language

The language in this book is american english.
All the screenshots and examples are in english.

## CoC

The same code of conduct applies to this book as for the main MISP project.
As a book can some times be considered the inadvertent sould of a piece of software, please take good care and consideration of our `Code of Conduct`. The CoC [can be read here](https://github.com/MISP/MISP/blob/2.4/code_of_conduct.md).

## Example install

The examples and screenshots provided in this book have been created with the MISP Autogenerated VM.

To get a copy of the latest VM [click here](https://www.circl.lu/misp-images/latest/)


## MISP Instance

In general when talking about a network of inter-connected MISP servers, each server is a MISP instance. Whilst we have no strong feelings towards anyones naming schemes, as a rule of thumb try to have a scheme that makes everyday use easy when analysts need to talk about remote MISP instances.
<!--
ToDo: Be more specific give some naming convention examples.
-->

The hostname used for the instance in this book is `misp.local` and we will henceforth refer to it either by name or as `local MISP instance`.


## Example Organisations

As MISP is a platform to support information sharing, example organisations are often used within this book.

A set of users and organisations are used in the different examples.

The following two organisations are regularly used as example:

* Setec Astronomy with UUID `58d38339-7b24-4386-b4b4-4c0f950d210f`
* Acme Finance with UUID `58d38326-eda8-443a-9fa8-4e12950d210f`

Starting from MISP 2.4.71, the example organisations with the above mentioned UUID are **black-listed** to avoid  
large distribution of sample events while testing a MISP instance. If you want to test your distribution, the  
sample organisation black-listing can be removed in `Administration`/`Manage Org Blacklists`.

## Example IOCs

As with the example organisations, we want to make this book as useful as possible by using real life examples.

The following IOC examples have been used:

* [Sirefef](https://www.misp-project.org/galaxy.html#_zeroaccess) (aka ZeroAccess) Sample Event ID: #31337
* [WannaCry](https://www.misp-project.org/galaxy.html#_wannacry) Sample Event ID: #42
* [Dridex](https://www.misp-project.org/galaxy.html#_dridex) Sample Event ID: #23

