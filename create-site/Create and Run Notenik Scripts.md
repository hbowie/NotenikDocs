Title:  Create and Run Notenik Scripts

Seq:    14

Level:  2

Class:  chapter

Body:

Finally create and run your [Script Files](https://notenik.app/kb/script-files.html). Your script files pull everything together, reading from your Collections, sorting and filtering those Notes, and then using your templates to generate actual web pages. Your script files will typically contain many steps. I often use Notenik to create the first step, and then go back to my trusty text editor to create others, copying and pasting and tweaking as I go. 

### Example

The Website starter pack contains one script file, named `web-gen.tcz`. 

Note that this file is in a [tab-delimited](https://en.wikipedia.org/wiki/Tab-separated_values) format, with five columns. 

You will notice that the file contains the following different *module* values. 

+ input — defines the input file/collection to be used. 
+ filter — defines any criteria needed to filter the input appropriately
+ sort — defines the fields by which the input should be sorted
+ template — specified a merge template to be used to generate output

The easiest way to run a script is to open the entire project as a parent realm, and then double-click on the script file to open that in the Scripter window, and then hit the Go button to run the script.
