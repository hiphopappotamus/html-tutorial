# html-tutorial
code for 3-step HTML tutorial found at [Itinerant Code](https://itinerantcode.com/tutorials/how-to-set-up-a-basic-html-file/)

## Step 01: Pick an editor (or don’t)

You don’t have to use any fancy IDE (Integrated Development Environment) to get started with HTML. Any simple text editor will do. For this tutorial, just use Notepad or similar system default software. Save your document as `index.html`.

![step 01](https://itinerantcode.com/wp-content/uploads/2021/07/step01.jpg)

## Step 02: Add a Doctype Declaration and tags

Now type the following into your document: `<!doctype html>`. This is known as the HTML Doctype Declaration, and is what browsers use to determine what kind of document they should be displaying. Under that line, type `<html>`. This is what’s known as a tag, which is the most basic building block of HTML. It’s common for most tags to have two parts: An open and close tag, which would be delineated by a slash just before the name, like this: `</html>`. That tells the browser that this particular chunk of code is finished, and it can move on to the next one. In this case, it’s the end of the HTML document, so add the html tag’s corresponding closer while you’re at it: `<html></html>`.

Your code should now look like this:

![step 02](https://itinerantcode.com/wp-content/uploads/2021/07/step02.jpg)

All our code will go between those open and closing `<html>` tags. Next, right underneath the open `<html>` tag, type the open and closing head tags: `<head></head>`. The `<head>` tags are where are the under-the-hood stuff goes, like metadata, favicons, site title, etc. For now, just type in open and closing title tags between the head tags like this: `<title></title>`. That’s where your site title will live, and what will display in the tab of the browser. Add something fun between those tags!

Now, just below the closing `</title>` tag, add an open and closing set of body tags: `<body></body>`. These aptly-named tags are where the body of the website lives. All the text, images, and other goodies will live in this set of tags. Once those tags are ready, add a line of text between two paragraph tags, like this: `<p>Some text here!</p>`

Your file should now look like this:

![step 03](https://itinerantcode.com/wp-content/uploads/2021/07/step03-1.jpg)
## Step 03: Enjoy!

And that’s it! Now you can navigate to your file in your system and double-click it to view it in your browser. All that will show is that rendered `<p>` tag, because everything else is just data.

![enjoy](https://itinerantcode.com/wp-content/uploads/2021/07/step04.jpg)

