# Rediscovering the Small Web

*Most websites today are built like commercial products: made to draw the largest audience, optimised to generate engagement, designed by professionals or companies and "pushed" either via search engine optimisation or advertising. But there is also a smaller web that is less visible, designed by regular people simply to share their interests and hobbies with the world. A web that is unpolished, often quirky but also creative and informative.  This is a guide to discover the joys and venture into the small web.*

Every website design begins with inspiration. 

For this one, there were two: Anders' very [clean, readable 10k website](anders.unix.se), which inspired the homepage, and a site I stumbled upon called [Marijn's site](https://marijnflorence.neocities.org/index.html), which reminded me just how _fun_ the web can be. The colours, graphics, [creative navigation](https://marijnflorence.neocities.org/shelves.html), interesting themes (some of which I knew [nothing about](https://en.wikipedia.org/wiki/Holocene_calendar))... the simple fact of clicking through pages of someone's personal website in 2020 made me nostalgic of the web of the late 90s and early 2000s that I grew up with.

Some of you might have read my previous article, [Against an Increasingly User Hostile Web](../against-a-user-hostile-web/). In it, I argue that we are replacing an open web that connects and empowers with one that restricts and commoditises people. I talk about how the modern web of surveillance, bloat and walled gardens is at odds with the open web that I grew up with. I was pleasantly surprised by how much the sentiment seemed to be shared by so many other people who wrote to me, wrote responses in their own blog or discussed it on discussion forums. Unfortunately, despite being two and a half years old, that article still reflects the state of the web today. 

But stumbling upon Marijn’s site gave me hope. It led me down a rabbit hole of many other small websites made by people with all kinds of interests: movies, aviation, music, art, computers. It reminded me that the creative, personal, _fun_ web I grew up with is not a thing of the past. In 2020, it’s still here. You just have to know where to look.

This essay is my attempt to show you what the small and independent web can look like, why it’s different from the the sites that dominate web traffic today and how easy it is for anyone to be a part of it. Including you, if you want to.

This essay is somewhat long; you might find this table of contents handy:

1. Retro Redesign
2. The First Webpages
3. Masters and Explorers, Authors and Navigators
4. The Web as a Creative Space
5. Highlights fro the Small Web
6. Try it Yourself

## Retro Redesign

I'll start with the redesign, because part of the beauty of the small web is how easy it is to be a part of it by _creating_ something.

On my homepage, I mention that this website is “a tribute to the creative web of the 90s”. I don’t say this simply because I have animated gifs and a [guestbook](https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60). The *way* I built it — the "technology stack" as one might call it today — is also similar to how I designed my earliest websites, and it is exceedingly basic. In fact, it's just two things: plain HTML and CSS.

No content management systems, no generators, no templates, no themes, no plugins. Just plain markup and styling, the basic building blocks of the web. 

I didn’t originally plan to do it like this. I previously used a static site generator to output plain HTML and was simply working on a new design template for that. But my three-year-old node.js setup was now spewing error messages, telling me some dependencies had to be updated and that a plugin was no longer compatible. I'm lazy and didn't want to fix any of that, so I wondered if I couldn’t just do it all manually instead and save myself the trouble. So I did. I decided to hand-code everything in plain HTML and CSS, manually link all pages and even hand-write the RSS feed. And to be honest, I haven’t had this much fun making a website since the late 90s and early 2000s, when I first started playing around with Microsoft Frontpage and Macromedia Dreamweaver. 

This approach wouldn't work for big websites. But for a small one like mine with about 10 total pages and a laid-back update cycle (if I’m being generous), it has many obvious benefits: next to no dependencies, easy to maintain, reasonably future proof, easily portable and most important of all, terribly fun to work on! I stayed up till six in the morning for two straight days, not because I couldn’t sleep but because I didn’t want to stop. Admittedly, I spent about 30% of that time scouring GifCities.org and the [Internet Archive](https://archive.org/web/) for animated GIFs and backgrounds (which is different for each page; that's an added benefit of using plain HTML).

The process of redesigning my website this way also rekindled my interest in scouring archives of old websites from the 90s and early 200s for interesting relics from the early web. And that led me to discovering creative, informative, independent websites that are actively maintained even today. 

## The First Webpages

To understand what these small websites represent, we need to go into the past.

The web was still in its infancy in the early 90s. In 1991 it had just been <a href="https://home.cern/science/computing/birth-web/short-history-web">invented by Sir Tim Berners-Lee</a> and released into the <a href="https://home.cern/science/computing/birth-web/licensing-web">public domain</a> in 1993, making it available for anyone in the world to build on top of it. In its early days, however, it was really only accessible to the more technical crowd, much like other internet protocols at the time, like Gopher, FPT and Usenet. It wasn't until the first easy-to-use graphical browser <a href="http://www.ncsa.illinois.edu/enabling/mosaic">Mosaic</a> was released for free in 1993 that regular computer users discovered the web for the first time. For others like myself, it came later still when browsers like Mosaic-spinoff <a href="http://sillydog.org/netscape/">Netscape Navigator</a> (the foundation of today's <a href="https://www.mozilla.org/en-GB/firefox/new/">Firefox</a>) and Internet Explorer became commonplace. 

It was terribly exciting. Unlike traditional media, you could now speak back. It was the first interplanetary communication system where anyone, anywhere in the world, could make a page and share their thoughts and ideas with the world. Netscape would later even include <a href="https://www.ccsf.edu/Pub/Fac/composer.html">an editor</a> that made it easy for anyone to make their webpages visually, like in a word-processor ("WYSIWYG", as it was called back then: what you see is what you get).

But if you wanted your web page to be "on the web", where would you put it? You needed a host of some sort to store the pages and share a public address so other people could visit. It would also have to be free so that <em>anyone</em> at all could participate. The answer is obvious: https://web.archive.org/web/20000815075123/http://geocities.yahoo.com/main/about.html <a href="https://web.archive.org/web/19980704165228/http://www20.geocities.com/join/freehp.html">Geocities</a>, perhaps the single biggest catalyst to democratising the web. Anyone could create a free account and build a website, either by uploading their HTML files via FTP or using their online builder. It was so simple, really <em>anyone</em> who wanted to could set up their website and share their hobbies and ideas. And share they did! People made websites about virtually everything: music, philosophy, ancient civilisations, <a href="https://web.archive.org/web/20011004132631/http://www.geocities.com/~intransit1/home/home_frm.html">art projects</a>, <a href="https://web.archive.org/web/20010424064639/http://www.geocities.com/spunk1111/">ASCII art</a>, <a href="https://web.archive.org/web/20000815075236/http://www.pezcentral.com/pezmenu.html">candy</a>, and about themselves. A key difference was that most people who made these websites were neither professionals nor companies; they were people who just wanted to share their interests. Like I did back in 2001 with my <a href="">unofficial fansite for German metal band Gamma Ray</a>: 

<--- My Geocities site about Gamme Ray image --->

But how would someone go about finding these pages? We didn't have Google in the early days. Sure, other search engines like Lycos, Altavista and Northern Lights did exist but were nowhere near as efficient as modern search engines. Finding something you were interested in was not as simple as typing a few words, and getting to that information in one click.

No, the web was much more of an adventure. It was a _place_ that you browsed to discover new corners, like exploring the vast open seas. It was, at least, in our collective imagination.


## Masters and Explorers, Authors and Navigators

The web had was a different kind of place in those early years, and we used different words to describe it. In an article titled <a href="https://rhizome.org/editorial/2015/nov/30/oldweb-today/">Cyberspace, the old-fashioned way</a>, authors at the Rhizome project make a very important point:

<blockquote>Today's web browsers want to be invisible, merging with the visual environment of the desktop in an effort to convince users to treat "the cloud" as just an extension of their hard drive. <strong>In the 1990s, browser design took nearly the opposite approach, using iconography associated with travel to convey the feeling of going on a journey.</strong> Netscape Navigator, which used a ship's helm as its logo, made a very direct link with the nautical origins of the prefix cyber-, while Internet Explorer’s logo promised to take the user around the whole globe. </blockquote>

<--- IMG: Logos of Internet Explorer and Netscape Navigator --->


Navigation. Exploration. Even words like "browsing" and "surfing" have spatial motion associated with them. 

The web itself was akin to a virtual manifestation of physical space, the "webspace". In Geocities, this was expressed with the idea of <em><a href="https://web.archive.org/web/19980704165140/http://www20.geocities.com/neighborhoods/">neighborhoods</a></em> in the "city": creatively-named categories like <em>Area51</em> for sci-fi, <em>Heartland</em> for families and pets, <em>RainForest</em> for the environment, <em>Vienna</em> for classical music, and so forth. 

<--- Image list of Geocities neighbourhoods --- >

An interesting word was very common back in the Geocities days that has since died out is the word "webmaster" (mostly gender-neutral, although sometimes declined to the feminine "webmistress"). The idea was that you created a <em>space</em> on the web, of which you were the <em>master</em>. You welcomed visitors (sometimes with a splash screen), you guided them around by explaining what they might find and the different spaces available to them (usually on the home page) and reminded them to leave a word on the guestbook on their way out (as you can on <a href="https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60"> my guestbook</a>). 

But the semantics of the web of yore made sense in the context of how you _practically_ interacted with it. Unlike the web of today, you very rarely just came in for one specific thing and left; you usually stayed and looked around. You _browsed_.

Which takes us back to the original question of how you found websites to visit. You were lucky if your small site showed up in pre-Google search engines, but even if it did, it would mean that somebody would have to be looking for that information. But not everybody who visited your website <em>were</em> looking for anything specific at all. They might simply have wanted to find other websites on a topic they were interested it.

One way of doing so was by browsing directories, like the Geocities neighbourhoods: lists of websites often arranged by categories and sub-categories. In fact, most search engines were also directories.


<—-- Image: Screenshot of search engine directory from the past> 

One of the biggest ones was DMOZ open-directory, based on the original Mozilla directories, where anyone could choose to be "editors" of certain categories and collect links. In fact, you can still browse an <a href="http://dmoztools.net/">archive browse the old directory</a> today to get a sense of how it worked. 

The other way to discover new websites was a natural consequence of one of the key features of the web: hyperlinks. You would go to one website and find your way to many others, much like you can if you go to my "Retro Stuff" page, where I collect links to interesting things elsewhere on the web. This idea of linking to things <em>elsewhere</em> was particularly common; most websites had a "links" page with their own personal collection of interesting webpages, or simply websites belonging to your friends or family.

This cross-linking was the main way I personally discovered my favourite websites, which I would then add to my bookmarks to be able to find them again later. In fact, the practice of cross-linking had an intersting cultural element: webrings. 

Webrings were "circular" collections of websites, often around a topic or a theme. The idea was that you could go from one website to another by clicking on the "next" or "previous" buttons usually placed on the footer of each member. These have also largely disappeared.

## Small vs. Big Web

Today, our relationship with the modern web is very different for three main reasons:

### More Concentrated

In the Geocities days, the web was more or less decentralized and everyone's starting point could be quite different. The downside was that if you did not somehow came across a website through the course of your navigation (through a link on someone's website, for example), you could possibly never see it at all. Over time, search engines made it easier for people to look up information, but there still wasn't a singular point of entry. Search engines also worked somewhat differently back in the day, and you were more likely to look for _websites_ instead of individual pages or very specific information.

Today, most of the time spent on the web is either _on_ a small number of very dominant platforms like Facebook, Twitter and LinkedIn, or mediated _through_ them. There is so much "content" that is constantly pushed at you as a user that very few of us actually venture out to browse like in the old days. And since these platforms themselves thrive on "user engagement"—likes, comments and shares—their algorithms are more likely to give visibility to content that evokes this behavior. I suspect this is one of the reasons that controversial/"alternative" facts get so much attention; outcry and controversy are profitable for platforms that make money off of their users' attention.

When you're not _receiving_ information passively, and instead actually actively looking for information, most people still have a singular point of entry. Google has become the de facto gatekeeper of the web, an arbiter of what is useful and not. Except, most websites that appear on the first few pages are actively designed to be there, thanks to "SEO", or search engine optimisation. To want visibility and optimise for it is natural, of course, especially if you are a company or a marketer for whom that audience is very important. One consequence of this though is that most of these websites are created by professionals and companies, not from your average person wanting to share their thoughts and ideas.

Not only is Google largely a _monopology_— other search engines like Bing, DuckDuckGo and Qwant are becoming more popular but are still far behind in adoption—it is also a major ad platform using this position and power to actively push its vision of the web.

And this web is quite different from the "small web" crafted by regular people. Google's web has a different set of values and vocabulary that come with it: engagement, conversion, metrics and optimisation. 


### More Commercial, marketing channel

There has always been a place for the commercial web. Amazon was already selling books online back in <YEAR>, Flower123 did the same for flowers, sd for pets. And it is only natural; the web is for everyone and e-commerce brought even more value to the web. 
	
But today's web is _mostly_ commercial. Since most people get to information through Google, and you can "optimise" your website 

> Traffic %: giants. Long tail.
> Mostly created by professionals or companies
> Search and push, vs browse and “surf”
> Engagement, do everything to engage you and try to retain you. Not make you discover other parts of the web.

### More Closed, Sanitized

> Fewer "create" and more consume
> Less personal, more commercial or professional content
> "Conversion", it's a marketing channel

Segue with the difference, "product" vs. "art".

## The Web as a Creative Space

> User-centered = optimised for the user’s preferences. This one is me-centered; it’s my little corner of the web, where I express myself the way I want to. No need for for “engagement” or optimisations. It’s the difference between product and art.

Modern websites are often products — they are made and optimised to generate interest and “conversion”. This might be in the form of a purchase, a click, a share or a sign-up. The words, the colours, the message are usually tailored to these goals, much like packaging on products in the super market. 

The small web is different, it’s an expression of the author’s interests and personality. A painter wouldn’t add more red to her painting, or change the composition, because research shows that people would like it like that. It’s her creative vision; some people might like it, others might despise it. And that’s that.

The modern web is mostly product. Most sd

## Highlights from the Small Web

A list of really cool websites either from the past (Restorativland and Internet Archive), or present (Neocities and Wiby).



## Your Own Corner of the Web

So the small web still exists, and is still giving us all kinds of websites to browse through and discover. 

As fun as it is to browse the small web and discover new websites, the best part is really to make your own website and join in. Not on closed platforms, social media mediated by ad companies, or on a discussion forum, but simply in your own little corner of the web. It's the best way to see how simple and open the web really is.

All you would need is to learn basic HTML and CSS, set up a site for free at Neocities.org and start playing. If you have zero experience, It might take you a while to get a hang of how to change text sizes, colours, link between pages and add images, but I think that’s part of the fun. It’s like learning how to paint, or sculpt — once you create your first piece, you’ll see how great if feels to have made from scratch and put it up on the web for the world to see.

Sure, if you've never coded before, it might seem daunting. But really, you only need the basics to get started. There are services out there that let you create a site without knowing HTML and CSS, but that's if you _need_ a site. Learning basic HTML and CSS is like learning to paint; sure you can commission or buy a painting, but it's not the same thing as learning to paint.

You can always view the source of any public website to take inspiration and learn. Make sure you pick simple, basic ones; the modern web is full of bloated websites that make HTML unreadable.  This website, for example, only uses basic HTML and CSS and I invite you to play with the code to your heart’s extent. It’s all in the public domain, so you can even copy all of it and modify it (and you don’t have to credit me or even link back, it’s all free). 

And if you do make a website, I’d love to see it (and perhaps even add it on here): send me an email at felix@neustadt.fr or send me a tweet at @parimalsatyal. 