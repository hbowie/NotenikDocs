Title:  Create Notenik Merge Templates

Seq:    12

Level:  2

Class:  chapter

Body:

Now create a [Merge Template](https://notenik.app/kb/merge-templates.html) for each page layout. These would contain HTML tags, as well as your Merge Commands and Merge Variables. You would create these with your trusty text editor. 

### Example

The Website starter pack contains three merge templates, and these are representative of ones you would typically create. Two of these are used to display content pages for your two content types, and the remaining one is used to create an include file of teasers. 

The HTML commands you see in the template files are pretty basic, and I will not provide any further explanation here. 

In addition to the HTML, you will find some [Merge commands](https://notenik.app/kb/merge-commands.html) and [Merge variables](https://notenik.app/kb/merge-variables.html). 

Let me discuss a few examples of each. 

#### Nextrec command

A `nextrec` command such as the following indicates to Notenik that the lines of code following the command should be generated for each input Note. 

```
<?nextrec?>
```

#### Output command

An `output` command indicates the name and location of the output file which is to receive the following lines of code. 

Here is an example:

```
<?output "../../web/=$title&f$=.html"?>
```

#### Title field 

Note that the string `=$title&f$=` represents a merge variable: in this case, the title field. The `&f` within represents a variable modifier: in this case, a request to modify the title field to make it more web-friendly [file name](https://notenik.app/kb/file-name-f.html). 

#### Loop command

A `loop` command must always follow a `nextrec` command, to indicate the end of the code to be produced repetitively. See below for an example. 

```
<?loop?>
```

#### Body field

Here is one more important example of a merge variable with modifiers. 

```
=$body&w1o$=
```

This will cause the body of the Note to appear within the output page, but it has two important modifiers. The [`o` modifier](https://notenik.app/kb/markdown-to-html-o.html) will convert the Markdown syntax to HTML. The preceding [`w1` modifier](https://notenik.app/kb/markdown-to-html-o.html) will cause any embedded [wiki-style links](https://notenik.app/kb/wiki-style-links.html) to be appropriately formatted for inter-page linkage on your website. 
