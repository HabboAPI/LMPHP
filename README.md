# Multi Language PHP
Multi-language management and support on the php (web).

## Features 

  - Easy
  - Compact
  - Useful

## Functions

| Function Name  | Goal | Parameter(s) | Return |
| ------------- | ------------- | ------------- | ------------- |
| word_add  	| Add a word to active language. | $name(name of the word) , __Optional__ : $value(value of the word) | Bool |
| word_get  |  Get a word from active language. | $name(name of the word) | The value of word. |
|  word_add_to | Add a word to custom language. | $lang(language name) , $name(name of the word) , __Optional__ : $value(value of the word) | Bool |
|  language_add | Add a new language. | $key(language name) | Bool |
|  language_remove | Remove a language. | $key(language name) | Bool |
| language_active  |  Activate a language. |  $key(language name) | Bool |
| language_current  | Get current active language. |  | Name of the active language. |
| language_exists  | Check a language is exists or not.  | $key (language name)  | Bool |
| language  |  Get list of the languages or list of the words of a language. | __Optional__ : $filter(language name)  | Array |

## Introduction

This library is simple and lightweight and can be used for language management.

This project started to be used for personal use.
At the very beginning, the project was used in the infrastructure of the servers of a project in India.
To be able to manage language and vocabulary more easily. (International projects)

With my decision, this project was put up for free.
