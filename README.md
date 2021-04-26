# Markdown

## Links
There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an inline link. 
- To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ). For example, to create a hyperlink to www.google.com, with a link text that says, Visit Google!, you'd write this in Markdown:[Visit Google!](www.google.com)
- The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here is an example:

     Here's [a link to something else][another place].
     Here's [yet another link][another-link].
     And now back to [the first link][another place].

     [another place]: www.github.com
     [another-link]: www.google.com
## Images
The difference between links and images is that images are prefaced with an exclamation point ( ! ).
- The first image style is called an inline image link. o create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the link in parenthesis ( ( ) ). Here is an example:
      ![Iron Maiden](https://images-na.ssl-images-amazon.com/images/I/81J4jpxoScL._SL1500_.jpg)
