# Links

[how-to-markdown] is a workshopper that teaches you how to write Markdown.





[how-to-markdown]: //git.io/how-to-markdown





<!--

## LINKS (Exercise 5 of 12)  

  We often need to make a reference for something. There are two ways to  
  create links: inline-style and reference-style.  

  By the way, the easiest way to create a link is to just paste the link  
  into a Markdown file. URLs and URLs in angle brackets will automatically  
  get turned into links:  

     http://www.example.com or <http://www.example.com>  

  |> (http://www.example.com) or <http://www.example.com>  

 ### Inline style  

  Links in Markdown have this format:  

     [text](href "alt")  

  Above, text is text that will be a link, href is your reference to the  
  resource (similar to href attribute in HTML), alt is an alternative text  
  for link (similar to alt attribute in HTML). Text in a link may have any  
  formatting, which means you are able to use emphasis in your links, if  
  needed.  

  Here are more real world examples:  

     [Google](https://www.google.com)  
     [Google Homepage](https://www.google.com "Google Homepage")  

 ## Reference style  

  Sometimes you have to use the same link in different places, so it would  
  be convenient to use one reference for all of these links. So you may do  
  this like so:  

     [NodeSchool Site][ref]  
     [GitHub][1]  
     [Remark parser]  

     Some text to show that the reference links can follow later:  

     [ref]: http://www.nodeschool.io  
     [1]: https://github.com/  
     [Remark parser]: http://remark.js.org/  

  As you may notice above, references are case-insensitive and you are free  
  to use numbers for creating references or use link text itself as its  
  reference.  

  # Amazing!

 References are very handy in cases when you have to write a big document,
 such as documentation for your project. If you have a lot of links and you
 want to easily manage them, you can create a section at the bottom of your
 file and leave all your references there. For example:

    A lot of text. Many [useful] and [important] information here.

    <!-- My References -->
    <!--
    [useful]: http://useful.site
    [important]: https://important.site

 Above, <!-- My References --> <!-- is an HTML-comment that will be omit. You
 can skip this comment, but actually it helps to recognize a section with
 references. This approach helps you to keep track of all of your links.

 By the way, references also work for images as well!

 ## THE CHALLENGE  

  At the top of the file, add a first-level heading with Links text.  

  Here you have some text:  

     how-to-markdown is a workshopper that teaches you how to write Markdown.  

  Please, copy this text to the new file and mark 'how-to-markdown' phrase  
  as reference-style link with reference to itself. Below in your file, add  
  a relevant reference which will reference to the //git.io/how-to-markdown.

-->
