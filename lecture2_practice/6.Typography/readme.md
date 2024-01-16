Notes are based on W3schools. 
# Typography

Choosing the right font has a huge impact on how the readers experience a website.

The right font can create a strong identity for your brand.

Two main classes of fonts can be differentiated based on their look and feel. Take a look at the two font styles below. 

![Alt text](serif.gif "a title")


## Activity 1

1. open the index.html file (that we worked on in the last lecture). Try to change the font family to `sans-serif` and `sans` (one after another) and see the difference. Also, try with other families. 
2. Now type `verdana` and hit enter to auto-complete the code in VS code. You will notice the following:

    `font-family: Verdana, sans-serif`



It sets the font family for all the text inside the body, but it first asks the browser to try and render all the text in the Verdana font.

Now, if for some reason the browser or the operating system doesn't have this font installed, then it will default to  sans serif font is installed on their
system.

However, this is not perfect for the best user experience because you always want the browser to render the font size you initially set. 

## Activity 2

Take a look at the web safe fonts here: https://www.w3schools.com/cssref/css_websafe_fonts.php


## Activity 3

Go to the https://www.cssfontstack.com/ and look at the supported font-styles for different operating systems. 

Is there any better way? The answer is Google fonts.

## Activity 4
1. Head over to the https://fonts.google.com/. 
2. choose any font-family that you like.
3. copy the <link> </link> code and add it to your web page's head section.
4. Then go to the `CSS rules to specify families` section on the Google website and copy and paste the CSS rule to the style section on your HTML page. 
5. You can repeate this step in case you want to use different font styles. 






