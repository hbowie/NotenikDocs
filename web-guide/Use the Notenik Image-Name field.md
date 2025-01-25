Title:  Use the Notenik Image-Name field

Seq:    13.3

Level:  3

Class:  detail

Body:

This option will allow you to optionally place one image at the top of each piece of content. 

There are several different Notenik pieces here that need to be coordinated. 

a. As with option #2, above, you will need to Enable Local Image References on your [Collection Settings](https://notenik.app/kb/tailor-collection-settings.html).

b. You will need to add the [Image Name](https://notenik.app/kb/image-name.html) field to your [Collection Template file](https://notenik.app/kb/the-collection-template-file.html). 

c. You may wish to also add fields named `Image Alt`, `Image Caption`, `Image Credit` and/or `Image Credit Link`, if you wish to supply any of this information along with your images. 

d. You may then add one image file to each of your Notes as a [File Attachment](https://notenik.app/kb/file-attachments.html), generally just by dragging an image file from the Finder and then dropping it onto the row for the intended Note on the List tab of your Collection window. These image files will then be stored in the `files` folder inside of your content folder. 

e. If the desired file is not already showing up at the top of your Display, then you may edit your Note and explicitly select the desired file from the `Image Name` dropdown. You may also wish to fill in the associated metadata fields, if you have included them in your Collection template file. 

f. In your [Merge Template(s)](https://notenik.app/kb/merge-templates.html) then, you can use the [Image Slug](https://notenik.app/kb/image-slug.html) derived variable to nicely format each image at the top of each page. 

g. Just preceding the appearance of the `Image Slug` variable, you can then include a [copyfile merge command](https://notenik.app/kb/copyfile-command.html). The two lines together, then, might look as follows. 

```
<?copyfile "../../content/files/=$imagename$=" "../../web/images/=$imagename&f$=" ?>
=$image-slug$=
```

This command, then, as shown above, would copy each named image file from your content `files` folder to your web `images` folder.
