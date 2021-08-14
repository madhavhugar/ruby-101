## Ruby for Programmers

- Interpretted language

- Duck typed language: Languages where we don’t have to explicitly state the type of a variable.

- Ruby has meta-programming: avoid it => code can be changed while it is running  Ruby on Rails is an MVC framework

**Strings**

- Two types of string literal: double quotes and single quotes => only double quotes evaluate between "#{variable}" or "#{3+2}"
- << operator can be used to concatenate two strings
  - `welcome = "hello" << "world"`
- `chomp` removes the new-line character `\n` from a given string: `s.chomp`
- `chop` can be used to remove the last character in a given string: `s.chop`
- `printf` can be used for string formatting
- [strings ruby docs](https://ruby-doc.org/core-2.6/String.html)
