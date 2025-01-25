Title:  Notenik 101 Script

Seq:    1.1

Level:  3

Body:

# Notenik Screencast Script

*(Open with light appearance, on the Notenik website.)*

Hey there, Herb Bowie here, Notenik developer. 

Today I'm going to give you a brief introduction to some of the Notenik basics. 

Let's start on the app's website, which you can find at Notenik.app. Lots of good info here, but right now we'll just click on the big button in the upper right corner to download Notenik from the Mac App Store. 

Once you're in the App Store, just click to download and install. Notenik is completely free, so no up-front purchases, no in-app purchases, no advertising, and no collection of users' data. 

Once you have the app installed, go ahead and open it. 

Now right now, I have my Systems Preferences General Appearance set to Light, so you're seeing both the website and the app in light mode as well. But if I change my System Pref to Dark... then both the website and the app follow suit. For this demo, I'll stick to dark mode, but you can use whichever setting you prefer. 

The first time you launch Notenik, you'll see a brief written Intro to the app. Feel free to read through this later, but for this video demo today we won't be making use of this. 

Before we go any further, I want to show you how to access the Knowledge Base, by just clicking on that item beneath the Help menu. This contains pretty much everything there is to know about Notenik, and you will want to use it as a reference as you dive deeper into the application's capabilities. Just know that it's there for now, and available whenever you have questions about anything in Notenik. 

*(Close the Knowledge Base.)*

So now I'm going to show you how to create your first Collection. A Collection is just a folder full of Notes, and a Note is just a plain text file with a bit of special formatting.  

So let's go up to the File menu, and select `New Collection`. You'll see a new window here, with three tabs. 

The first step here is to select the general location where you'd like to store your new Collection of Notes. You have two choices. 

+ If you select the first, then your Collection will be stored in a special iCloud folder reserved for use by Notenik. This is generally the best option, especially when first starting out. 

+ The second option would allow you to select your Documents folder, or any other folder where you would like to store your Notes. You may later discover some reasons for using this second option but, for today, let's just stick to the iCloud option. 

So now we'll just click `Next`, to take us to the second tab. 

Here we specify the name of the Collection, which will also become the name of the folder in which your Collection will be stored. Enter something brief but meaningful here. For this demo, I'll just enter 'Important Notes', then click `Next`.

The third tab allows us to pick a "model" to use as a starting point for our new Collection. You can click on the Dropdown menu to see what's available. Don't worry too much about this, because you can always change any of these options later: this tab just gives you a quick and easy starting point for a number of common Notenik use cases. 

For today's demo, let's select `Basic Notes`, then click `Next` once more. 

Now you'll see two new windows. In the background, you'll see your new Notenik Collection. In the foreground, you will see the Preferences that apply to this particular Collection. You can call these same Prefs up later by selecting the item beneath the Collection menu, and you can change them later as well. 

There are a lot of options here and, for today, I'll just run over a few of them. 

First, you'll see the name you picked for your Collection Title. You can change this, but this will not change the name of your actual folder -- just the title displayed within Notenik. 

Next, you'll see your preferred file extension. The default is `txt`, and this should be fine for today, but just note that you can pick another one if you'd like. And you can change this later as well. 

Now if we look on the right side of the Collection Preferences, we see some columns of checkboxes and labels. These are the various field labels, and associated field types, that you can choose from for your Collection. 

So now we have come to what we might call the key feature of Notenik, compared to other Note-taking applications. Each Note has a Title, and a Body, of course. But each Note can also contain other fields. And each Collection that you create can have a different set of fields. This can be a bit mind-boggling at first, but once you get used to it, you'll find that it gives you tremendous flexibility. 

For now, though, just note that, because we selected the `Basic Notes` model as our starting point, the `Title`, `Tags` and `Body` fields have been automatically selected for us. For today's demo, let's check a couple of additional fields: `Link` and `Seq`. ('Seq' stands for 'Sequence', by the way, and can be used for any sort of sequence number.) 

And now we can click `OK` to record our changes and dismiss the prefs window. 

So now we've arrived at the main window for Notenik, where you will be doing most of your work. Notice that the left side of the window shows us the Collection as a whole, while the right side shows us only the currently selected Note. 

Now, if we just focus on the right side for a moment, we can see two tabs, labeled `Display` and `Edit`. We're always on the `Display` tab to start. But now let's switch to Edit mode, which we can do by clicking on the `Edit` tab, or by selecting `Edit Note` beneath the `Note` menu, or by just using the keyboard shortcut of `CMD-E`. 

Once we're in Edit mode, you'll see that each possible field in the Collection is shown, along with the current contents of each field, for this particular Note. You can type into any of these fields in order to make changes. When you're done, just click on the `Display` tab again, or select `Save Note` beneath the `Note` menu, or enter `CMD-S`, to save your changes and take you back to the Note's Display. 

So now let's add a new Note. You start by hitting the `+` sign in the toolbar, or selecting `New Note` beneath the `Note` menu, or entering `CMD-N`. 

Note that you're now back on the `Edit` tab, but with a generally blank set of field values. 

Let's give this first Note a `Title` of 'First Note', and enter `1` into the `Seq` field. Now I'll enter a little text into the `Body` field. 

```
This is an unordered list within the first note. 

+ This is the first item in the list. 
+ This is the next item in the list. 
```

Now let's save the Note, just in the same way we saved our editing changes earlier. 

Here I'll just pause to point out that the body of our Note has been nicely formatted for us, using the Markdown syntax. I won't go into any details of the syntax, but you can find out all about it from the `Daring Fireball` website. 

Now let's add a second Note. Let's title it 'Another Note' and give it a Sequence value of 2. And now I'll just type some sample text in the Body field. 

```
Even better than the [[First Note]]!
```

Now let's save our newest Note. Now notice that `first note` is highlighted, and when we click on this link -- it takes us to the First Note! This is known as double-bracket wiki-style linking, and is a powerful feature of Notenik. 

Now let's turn our attention to the List of Notes on the left. Notice that it now shows the Notes sorted in ascending order by the Title field. 

But it doesn't have to be this way!

Look under the `Collection` menu, and you'll find a sub-menu titled `Sort`. Look beneath `Sort`, and you'll see a number of different options. Let's pick `Seq + Title`, the second option on the list. 

Now you'll see that the Sequence value appears on the `List` tab, and the Notes have been rearranged so that they are in order by ‌their sequence numbers. 

Now let's delete the Note titled `Notenik`. Just select the Note to be deleted on the `List` tab, then hit the `-` (minus) sign in the toolbar, or select `Delete Note` beneath the `Note` menu, or just hit the Delete key on your keyboard. You'll then get a confirmation dialog. Once you've clicked `OK` here, the Note will be deleted. 

So that rounds out our brief introduction to Notenik. Hopefully this gives you a feel for some of the basic operations you can perform with the app. Feel free to explore further on your own, and don't forget about the Knowledge Base that's always available beneath the `Help` menu. 
 






