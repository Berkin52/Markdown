# Markdown

## Text Editing
Italic _italic_
Bold **Bold**
Italic and Bold **_italic and bold_**
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

- The other image style is called reference image.for a reference image, you'll follow the same pattern as a reference link. You'll precede the Markdown with an exclamation point, then provide two brackets for the alt text, and then two more for the image tag, like this: ![Iron Maiden Album Cover][Iron Maiden] At the bottom of your Markdown page, you'll define an image for the tag, like this: [Iron Maiden]:https://images-na.ssl-images-amazon.com/images/I/81J4jpxoScL._SL1500_.jpg.      
-  ![Iron Maiden Cover][Cover]
-  [Cover]:https://townsquare.media/site/366/files/2017/04/Iron-Maiden-Seventh-Son-of-a-Seventh-Son-Anniversary.jpg?w=1200&h=0&zc=1&s=0&a=t&q=89

### Image Resizing
With this technique you can resize your images and also center them.
<p align="center">
<img src="https://images-na.ssl-images-amazon.com/images/I/81J4jpxoScL._SL1500_.jpg" width="200" height="200"/></p>

## Blockquotes
I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

## Lists

### Non Ordered lists
* Flour
* Cheese
* Tomatoes

### Ordered Lists
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

### List With Italic or Bold
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (**_Anthemideae Chrysanthemum_**)
* Dahlia (_Coreopsideae Dahlia_)

### Sub Lists
* Calculus, 
 * A professor
 * Has no hair
 * Often wears green
* Castafiore 
 * An opera singer
 * Has white hair
    * Is possibly mentally unwell

### Lists and Indentations
1. Cut the cheese
  
 Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes
  
 Be careful when holding the knife.
  
 For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.
