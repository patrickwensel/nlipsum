# Introduction #
Below are examples of how one might use NLipsum.
If you download the [Subversion source](http://code.google.com/p/nlipsum/source/) there is an Example web site with these examples in action and some more detailed documentation.

**This document and the example site are both a work in progress and are not finished.**

## A Single Sentence ##
**Note:** The `GenerateSentences` and `GenerateParagraphs` methods return string arrays.

Code:
```
NLipsum.Core.LipsumGenerator.GenerateSentences(1)[0]
```
Output:
```
magna eos consectetuer lorem diam et et vulputate 
```
### Formatting ###
_Use the sentence as a header_

Code:
```
generator.GenerateSentences(1, "&lt;h3&gt;{0}&lt;/h3&gt;")[0] 
```
Output:
```
<h3>no elitr vel takimata lorem voluptua</h3> 
```

## Web Page Filler Text ##
You can embed this into a Web Form (.aspx) page to have the Html generated right inside your page using the static LipsumGenerator.GenerateHtml method.
```
 <h1>Html Lipsum</h1>
 <div><%= NLipsum.Core.LipsumGenerator.GenerateHtml(3) %></div>
```