# Broken Link Checker

Identify, update or remove links that no longer work.

## Use Case

Links are frequently included in documents which may become broken overtime. This tool can be used to scan text documents in repositories to identify, update or remove links that no longer work. This makes it easier to maintain links in a set of documents over time.

## Link Definitions 

### Link

A link will be identified using the following regular expression:

- TODO

### Broken Link

A link is considered to be broken when one of the following conditions is met:

1. When the HTTP response status code is not 200
2. When the HTTP response body does not contain an expected string when provided

## Command Line Features

1. Return True/False for a given link
2. Return True/False for a given link and expected string
3. Return a list of broken links for a given list of links in csv format
4. Return a list of broken links for a given list of links and expected string in csv format
5. Remove broken links from document(s) and return a list of links removed and the respective document
6. Update broken links in document(s) and return a list of updated links and the respective document
