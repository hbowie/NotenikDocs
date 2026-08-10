Title:  Volume 1, Issue 3 - Reason to Rock Refresh

Seq:    1.3

Level:  3

Body:

I'm currently working on a refresh of the *Reason to Rock* web book, which was originally published back in 2001 – a quarter of a century ago!

If you'd like to see both old and new:

+ The 2001 version (for now) is still at [ReasonToRock.com](https://reasontorock.com)
+ The 2026 version (still a work-in-progress) is at [ReasonToRock.com/refresh/](https://www.reasontorock.com/refresh/)

I'm making a number of changes to the site and the way it is put together, and I thought it might be interesting to describe these, both as a historical record of the site, but also as a way of comparing the web of today to the World Wide Web of '01. 

So, here goes!

{{toc}}

## It still works! 

The first thing worth noting is that the web site I put together in '01 still loads in everyone's web browser today, and still looks pretty much the way it was meant to look when I created it twenty-five years ago. 

It's easy to overlook this and take it for granted, but this speaks to the tremendous reliability of the web's foundational technologies: HTML, CSS, Javascript and web browsers. 

## BBEdit still doesn't suck!

I used BBEdit as a text editor back in '01, and I'm still happily using it today.

## The words hold up

In reading over my words written 25 years ago, I'm still very happy with them. I'm making a few tweaks here and there but, all in all, I still believe the site contains some very worthwhile content that is worth preserving (and perhaps deserving of a wider audience – but, then, I'm a bit biased). 

## Google search results

When I first launched the site, it was briefly at the top of Google results when searching for "rock music," but the site has been gradually buried in the flood of content now available on the web. In particular, written content of enduring value has continually lost ground to other sorts of stuff, such as videos and news sites – anything to feed the insatiable desire for something "new" to keep people's attention, and fuel the advertising business that keeps coffers full. 

## Textile to Markdown

When I started work on the site, I was writing in raw HTML. And then, when [lightweight markup languages](https://en.wikipedia.org/wiki/Lightweight_markup_language) became a thing, I switched over to [Textile](https://en.wikipedia.org/wiki/Textile_(markup_language)). But [Markdown](https://daringfireball.net/projects/markdown/) is now deservedly the king of this particular hill, and so I'm using [Typora](https://typora.io) to convert from one to the other. 

## PSTextMerge to Notenik

I originally wrote [PSTextMerge](https://github.com/hbowie/pstextmerge) to read spreadsheets and [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) files full of document and file metadata in order to drive the creation of a website, and this was the approach I originally used here. With the refresh, this metadata is stored within [Notenik](https://notenik.app) [fields](https://notenik.app/kb/fields.html), just above the Markdown text, making it much neater and easier to maintain. 

## Dark Mode

I've learned to really appreciate [Dark mode](https://en.wikipedia.org/wiki/Dark_mode) on my Mac, and it's a joy for me to see my original content presented in this style. The new site adopts whatever system appearance the user has set.

## Link Rot, Paywalls and Wikipedia

Back in '01, I was freely linking to all sorts of sites containing relevant content related to my interests. 

Alas, these are mostly dead links today. 

And, if I look to update them to currently available links, I'm generally simply linking to the appropriate page on Wikipedia. 

I think there are several lessons here. 

+ One of the original promises of the Web has not panned out. That is, the idea that every unique page will have its own immutable URL, and that other sites can safely link to these identifiers, with a reasonable level of confidence that their readers won't encounter broken links. 

+ Most worthwhile content still around has been monetized in one way or another, meaning it is behind a paywall, or it is so riddled with ads as to be nearly unreadable, or both. 

+ We should never take [Wikipedia](https://en.wikipedia.org/) for granted. If you haven't donated to them lately then I suggest you stop what you're doing and [do so immediately](https://donate.wikimedia.org), if it's within your financial means to do so. (And I say this as someone whose attempts to get Notenik a page on that site have been soundly and repeatedly rejected, for admittedly defensible reasons.)

## Wiki links

While linking to another website has proven increasingly problematic, many Markdown editors (including Notenik) now support wiki links that can be used to easily link from one page within a site/book/wiki to another. Since *Reason to Rock* has many internal links, these have been coverted to more-or-less standard wiki links, using the familiar double square bracket enclosure syntax. 

## Doubling down on the Web Book

From the beginning, I've talked about *Reason to Rock* as a book that happens to be published on the web, instead of in print. Matthew Butterick has also come out in favor of the "web-based book," as [he calls it](https://practicaltypography.com/why-theres-no-e-book-or-pdf.html). Not a lot of others have jumped on this particular bandwagon, but that's ok: I'm happy to be in good company. 

Today I'm even more thrilled than in '01 to be publishing something deserving to be called a "book," but freely available on the web, and taking full advantage of web technologies. And my app Notenik has been gradually but steadily evolving in a direction that makes this sort of publishing easier than ever.

## A Simple Export

When I first published *Reason to Rock* I used lots of CSV files and scripts and templates to create the finished website. 

Now I'm just using a simple web book export out of Notenik. 

