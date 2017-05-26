go-confluence
=============

added support for adding content, Labels and Ancestors

Go library wrapping the [confluence REST API](https://docs.atlassian.com/confluence/REST/latest/).

Currently implemented
---------------------

- Authentication:
  - Basic Authentication
  - Token Key authentication
- Manipulating existing wiki content, i.e:
  - `DeleteContent`
  - `GetContent`
  - `UpdateContent`
  - `AddContent`

This is everything I needed for my project. I might add some more functionality when I find the time. Feel free to send pull requests.
