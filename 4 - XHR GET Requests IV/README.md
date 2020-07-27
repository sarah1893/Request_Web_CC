# XHR GET Requests IV

In the previous exercise, you made a GET request to the Datamuse API to find words that rhyme. In this exercise, we will create a request to set a topic and find adjectives that describe the input word using query strings.

A query string contains additional information to be sent with a request. The Datamuse API allows us to retrieve more specific data with query strings attached to the request URL.

[Wiki: query string](https://en.wikipedia.org/wiki/Query_string)

A query string is separated from the URL using a ? character. After ?, you can then create a parameter which is a key value pair joined by a =. Examine the example below:

```
'https://api.datamuse.com/words?key=value'
```

If you want to add an additional parameter you will have to use the & character to separate your parameters. Like so:

```
'https://api.datamuse.com/words?key=value&anotherKey=anotherValue'
```
 
Let’s incorporate this into our code!