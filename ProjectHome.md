# NLipsum :  _[Lorem Ipsum](http://en.wikipedia.org/wiki/Lorem_ipsum) (Lipsum) Generator and Library for the .NET Framework (C#)_ #
_Works in versions: 2.0 and higher (3.0, 3.5, 4.0)_

This project was vaguely inspired by  [Lipsum : the text generator written in Python and wxPython](http://lipsum.sourceforge.net/)

http://lipsum.sourceforge.net/

Similar to the Python Lipsum, you are not bound to generate only "Lorem ipsum..." style text.  There are a dozen different text-generation sources in several languages, all of which come from the Python Lipsum.  You can also easily include your own text source!

The built in text sources:
  * [Lorem Ipsum (Lipsum)](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/loremipsum.xml) (of course)
  * [Childe Harold's Pilgrimage (Lord Byron)](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/childharold.xml)
  * [Decameron - Novella Prima (Giovanni Boccaccio)](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/decameron.xml)
  * [Faust (Goethe), German](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/faust.xml)
  * [In der Fremde (Heinrich Heine), German](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/inderfremde.xml)
  * [Le Bateau Ivre (Arthur Baudelaire), French](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/lebateauivre.xml)
  * [Le Masque (Arthur Rembaud), French](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/lemasque.xml)
  * [Nagyon fáj (József Attila), Hungarian](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/nagyonfaj.xml)
  * [Ómagyar-Mária siralom (Ismeretlen), Hungarian](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/omagyar.xml)
  * [Robinsono Kruso (Daniel Defoe), Esperanto](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/robinsonokruso.xml)
  * [The Raven (Edward Allen Poe), English](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/theraven.xml)
  * [Tierra y Luna (Federico García Lorca), Spanish](http://nlipsum.googlecode.com/svn/trunk/NLipsum.Core/resources/tierrayluna.xml)


NLipsum will choose a random selection of words from your text source and combine them into sentences and combine those sentences into paragraphs.  You can request very specific criteria for your generated text or just let the defaults go to work.  Generating text in HTML format is a breeze and there are built-in utility methods for HTML generation (paragraph tags).

All code was written in C# using the .NET Framework 2.0, Visual Studio 2005.  Support for the .NET 1.1 framework may be included at a future date depending on demand.  Also, since this is open source you're always welcome to modify the code and submit your own changes for compatibility.

### In the Wild ###

  * [Rapid Prototyping, the MVC Working Model by Edward Charbeneau](http://www.simple-talk.com/dotnet/asp.net/rapid-prototyping,-the-mvc-working-model/)
  * [WP7 Port by Dan Clarke](http://dan.clarke.name/2011/05/nlipsum-for-windows-phone-7-auto-generate-lorem-ipsum-for-wp7/)
  * [On Nuget thanks to wullinkm](https://nuget.org/packages/NLipsum)
  * [Test Data Generator by garykenneally](http://code.google.com/p/testdatagenerator/source/browse/trunk/DataGenerator/DataGenerator/TextRandomDataGenerator.cs?r=3)

Please feel free to send me any feedback or tell me about a project in which you've used NLipsum. I'd love to hear about it.