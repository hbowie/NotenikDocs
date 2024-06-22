Title:  Notenik 201 Script

Seq:    2.2

Level:  3

Body:

#### Introduction

Hey there, Herb Bowie here, Notenik developer.

Today I’m going to begin to cover some of Notenik's more advanced features. 

If you're new to this app, then best to begin with the Notenik 101 video, which will provide a good introduction to the basic functionality. 

In this video I'm going to show you how to customize a Notenik collection for a specific purpose, by adding appropriate fields to each note. 

For demonstration purposes, let's customize a Collection of Notes to keep track of books we want to read, or have already read. 

There are several different approaches to this customization process, and I will walk you through each of them one at a time. 

#### Open Knowledge Base

Let's start, though, by opening the Notenik Knowledge Base, and selecting the section titled 'Field Labels and Types', and then 'Lists of Labels and Types'. 

Here you will find lists of all the different types of fields that Notenik recognizes. Click on a Field Type in order to see complete documentation describing how to use each type of field. 

These are the field types you will have to draw upon when customizing a new Collection for a particular purpose, so you will refer to this information often when creating Collections. 

#### Pick Some Sort of Collection to Start 

But now let's go ahead and create a new Collection. 

To keep things simple, we'll just create it within the Notenik iCloud folder. 

And let's call it `Book Notes`, since we'll be keeping notes about books. 

Now Notenik asks us what sort of Collection we would like. So this is the first way we can customize a Collection: by picking something other than basic Notes. 

Again, the Knowledge Base provides helpful reference information. Go to the section titled 'Creating and Tailoring a Collection of Notes', and then select 'Starting Collection Types'. Click on any of these starting types to find out more about them.

We don't see anything here that looks like what we want at the moment, so let's just pick `Basic Notes` in order to get started. 

#### Add Additional Fields from Collection Settings

Now we see the Collection Settings window, and on the right we see a list of possible fields we might want to use. Note that this list is not comprehensive, but only includes some of the most common field types. Some of these might be useful for our purpose today, so let's check a few of these:

+ Link
+ Status
+ Seq
+ Date
+ Author
+ Timestamp

Now let's click `OK` and see what we've got. 

So far we only have a basic starting Note for the Collection, but if we click on the `Edit` tab, we can now see all of the fields that are available for entry. 

#### Rename/Add Fields

Now let's do a little more customization. If you look beneath the `Collection` menu, you'll find an option to `Rename, Add or Remove a Field`. Let's use this to rename a couple of fields. 

+ Rename `Seq` to `Priority`, keeping the type of `seq`. Wc can then use this to assign a reading priority to the unread books on our list. 

+ Rename `Date` to `Pub Date`, keeping the type of `date`. We can use this to enter the publication date for each book. 

Now let's use this same menu item to add a field. Let's call it 'Date Read', and give it a type of `date`. We'll use this to store the date we finished reading a book. 

#### Edit the Template File

Now let's do a few more customizations. 

Right now the `Status` values available to us are not very helpful, so let's change those. To make this change, we will make use of another option. Looking beneath the `Collection` menu, we'll see an option to `Text Edit the Collection's template file`. Let's select this. 

Now another application will be opened, outside of Notenik. This will be whatever app you use on your Mac as a text editor. In my case, it's BBEdit. Your editing window may look a little different, depending on the text editor that you use. 

What you are seeing now is the `template` file stored within your Collection folder. On each line you'll see a field label, followed by a field type, optionally followed by some configuration info. This information should look familiar. 

Now let's change the `Status` values that are available. Notice that each status has both a digit and a label associated with it. Let's replace the default values with the following:

```
0 - Interested; 2 - Acquired; 4 - Reading Now; 6 - Finished; 8 - Gave Up; 9 - Dispositioned; 
```

Next let's call add a field called `Rating`, and give it a type of `rank`, with the following configuration values:

```
1 - fave, 2 - great, 3 - ok, 4 - disappointing, 5 - terrible
```

 We can use this field to rate each book after we've read it, assigning each book a rating of 1 to 5, with 1 being the best.

Next let's add a Disposition field, with a type of `pickfrom`, and values of '`passed on`' and '`shelved`'. We can use this to track what we did with the book after we finished reading it. 

And then let's add two more fields: one called '`Series Name`', with a type of `combo`, and another called '`Series Seq`', with a type of `seq`. We can use these two fields to keep track of books that are part of a series. 

Now let's move fields around a bit, to place them in a more natural sequence. Just remember that the `Title` field must always be first, and the `Body` field must always be last. 

Now whenever you use your text editor to modify a Collection template file, you must remember to perform two important actions:

1. Save your changes within your text editor. In BBEdit, this just means hitting CMD-S. 

2. Go back to Notenik, and use OPT-CMD-J to reload the template file within Notenik. (I use the letter `J` to mean reload, by the way, because the shape of the letter seems to symbolize the reload process for me.)

#### Add Some Notes

Now let's add a book or two, to see how everything is working. 

We'll start with *I Cheefully Refuse*, by Leif Enger. 

And then, once we've added some real notes, we can delete the note titled 'Notenik' that was present when the new Collection was initialized. 

And then let's add *Slough House*, by Mick Herron, from 2021, which is the 7th book in the "Slough House" series. 
 
#### Sort As Needed
