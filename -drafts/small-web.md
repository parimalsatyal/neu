# In Defense of The Small Web

*Most websites today are built like commercial products: made to draw the largest audience, optimised to generate engagement, designed by professionals or companies and "pushed" either via search engine optimisation or advertising. But there is also a smaller web that is less visible, designed by regular people simply to share their interests and hobbies with the world. A web that is unpolished, often quirky but also creative and informative.*

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

On my homepage, I mention that this website is “a tribute to the creative web of the 90s”. This is not simply because this website has animated gifs and a [guestbook](https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60). The *way* I built it — the "technology stack" as one might call it today — is also similar to my earliest websites. In fact, it's just one thing: <strong>plain HTML</strong>.

No content management systems, no generators, no templates, no themes, no plugins. Just plain markup and styling, the basic building blocks of the web. 

I didn’t originally plan to do it like this. I previously <a href="../crafting-a-simple-blog-with-metalsmith">used a static site generator</a> to output plain HTML and was simply working on a new design template for that. But my three-year-old node.js setup was now spewing error messages, telling me some dependencies had to be updated and that a plugin was no longer compatible. Because I'm lazy and didn't want to fix any of that, I wondered if I couldn’t just do it all manually instead and save myself the trouble. 

So I did. I decided to hand-code everything in plain HTML and CSS, manually link all the pages and even hand-write the RSS feed. And to be honest, I haven’t had this much fun making a website since when I first started playing around with Microsoft Frontpage and Macromedia Dreamweaver in the late 90s and early 2000s.

This approach wouldn't work for a bigger website. But for a small one like mine with about 10 total pages, it has many obvious benefits: next to no dependencies, easy to maintain, reasonably future proof, easily portable and most important of all, terribly fun to work on! I stayed up till six in the morning for two straight days working on the redesign, not because I couldn’t sleep but because I didn’t want to stop. Admittedly, about 30% of that time was spent scouring <a href="https://gifcities.org/">GifCities.org</a> and the <a href="https://archive.org/web/">Internet Archive</a> for animated GIFs and backgrounds (which is different for each page; that's an added benefit of using plain HTML).

The process of redesigning my website this way inspired me to scour archives of old websites for interesting relics from the early web. This in turned led me to the creative, fun, independent websites that are actively maintained even today. 

To understand what these small websites represent and why I think they are important, we need to start in the past.

## The First Webpages

The web was still in its infancy in the early 90s. 

It had only just been <a href="https://home.cern/science/computing/birth-web/short-history-web">invented by Sir Tim Berners-Lee</a> in 1991 and released into the <a href="https://home.cern/science/computing/birth-web/licensing-web">public domain</a> just two years after, making it available for free to anyone in the world to build on and extend. In its very early days, however, it was really only accessible to the more technical crowd, much like other internet protocols at the time, like <em>Gopher</em>, <em>FTP</em> and <em>Usenet</em>. It wasn't until the first easy-to-use graphical browser <a href="http://www.ncsa.illinois.edu/enabling/mosaic">Mosaic</a> was released for free in 1993 that regular computer users discovered the web for the first time. Others like myself discovered it later still when the Mosaic-spinoff <a href="http://sillydog.org/netscape/">Netscape Navigator</a> (the foundation of today's <a href="https://www.mozilla.org/en-GB/firefox/new/">Firefox</a>) and Internet Explorer became commonplace. 

It was all terribly exciting. Unlike traditional media, you could now speak back and participate. It was the first interplanetary communication system where anyone, anywhere in the world, could make a page and share their thoughts and ideas with the world. Netscape would later even include <a href="https://www.ccsf.edu/Pub/Fac/composer.html">an editor</a> that let users make webpages visually, like using a word-processor ("WYSIWYG", as it was called back then: <em>what you see is what you get</em>).

But if you wanted your web page to be "on the web", where would you put it? 

You needed a host of some sort to store the pages and share a public address so other people could visit. It would ideally also have to be free so that <em>anyone</em> at all could participate. The answer was, by the early 2000s, quite obvious. <a href="https://web.archive.org/web/19980704165228/http://www20.geocities.com/join/freehp.html">Geocities</a> was perhaps the single biggest catalyst to democratising the web. Anyone could create a free account and build a website, either by uploading their HTML files or by using their online builder. 

It was so simple, really <em>anyone</em> who wanted to could set up their website and share their hobbies and ideas. And share they did! People made websites about virtually everything: music, philosophy, ancient civilisations, <a href="https://web.archive.org/web/20011004132631/http://www.geocities.com/~intransit1/home/home_frm.html">art projects</a>, <a href="https://web.archive.org/web/20010424064639/http://www.geocities.com/spunk1111/">ASCII art</a>, <a href="https://web.archive.org/web/20000815075236/http://www.pezcentral.com/pezmenu.html">candy</a>, and about their lives. A key detail was that most people who made these websites were neither professionals nor companies; they were people who just wanted to share their interests. Like I did back in 2001 with my <a href="">unofficial fansite for German metal band Gamma Ray</a>: 

[IMG: My Geocities site about Gamme Ray]

But how would someone go about finding these pages? We didn't have Google in the early days. Other search engines like <a href="https://web.archive.org/web/19980214192548/http://www.lycos.com/">Lycos</a>, <a href="https://web.archive.org/web/19970630113649/http://www06.excite.com/">Excite</a> and <a href="https://web.archive.org/web/19980206192654/http://www.northernlight.com/">Northern Lights</a> did exist but were nowhere near as efficient as modern search engines. Finding something you were interested in was not as simple as typing a few words and getting to that information in one click.

No, the web was much more of an adventure. It was a _place_ that you wandered to discover new places, like exploring the vast open seas. A new virtual space that lead to all kinds of strange, interesting, exciting places. This is what the web was like, at least, in our collective imagination.


## Masters and Navigators

The web had was a different kind of place in those early years, and we had different words to talk about it. In an article titled <a href="https://rhizome.org/editorial/2015/nov/30/oldweb-today/">Cyberspace, the old-fashioned way</a>, authors at the Rhizome project make a very important point:

<blockquote>Today's web browsers want to be invisible, merging with the visual environment of the desktop in an effort to convince users to treat "the cloud" as just an extension of their hard drive. <strong>In the 1990s, browser design took nearly the opposite approach, using iconography associated with travel to convey the feeling of going on a journey.</strong> Netscape Navigator, which used a ship's helm as its logo, made a very direct link with the nautical origins of the prefix cyber-, while Internet Explorer’s logo promised to take the user around the whole globe. </blockquote>

[IMG: Logos of Internet Explorer and Netscape Navigator]

Navigation. Exploration. Browsing. Surfing.  The web was akin to a virtual manifestation of physical space. We even had a word for it: "webspace". In Geocities, this was expressed with the notion of <em><a href="https://web.archive.org/web/19980704165140/http://www20.geocities.com/neighborhoods/">neighborhoods</a></em>, creatively-named categories like <em>Area51</em> for sci-fi, <em>Heartland</em> for families and pets, <em>RainForest</em> for the environment, <em>Vienna</em> for classical music. 

[IMG: List of Geocities neighbourhoods]

Another word that was very common back in the Geocities days that has since died out is the word "webmaster" (mostly gender-neutral, although sometimes declined to the feminine "webmistress"). The idea was that you created a <em>space</em> on the web, of which you were the <em>master</em>. You welcomed visitors (sometimes with a splash screen), you guided them around by explaining what they might find and the different spaces available to them (usually on the home page) and reminded them to leave a word on the guestbook on their way out (as you can on <a href="https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60"> my guestbook</a>). 

But the semantics of the web of yore made sense in the context of how you _practically_ interacted with it. You very rarely just came in for one specific thing and left; you usually <em>entered</em> a website and looked around. You _browsed_.

Which takes us back to the original question of how you found websites to visit in the first place. You were lucky if your small site showed up in pre-Google search engines, but even if it did, it would mean that somebody would have to be looking for it. But not everybody who visited your website <em>was</em> looking for anything specific. They might simply have wanted to find other websites on a topic they were interested it.

One way of doing so was by browsing directories, like the Geocities neighbourhoods: lists of websites often arranged by categories and sub-categories. In fact, most search engines were also directories, or _portals_ as they were called back then.

[IMG: Screenshot of search engine directory from the past]

One of the biggest ones was the <a href="https://web.archive.org/web/20010206123038/http://www.dmoz.org/about.html">DMOZ open-directory project</a>, based on the original Mozilla directories, whose goal was to <em>"produce the most comprehensive directory of the web, by relying on a vast army of volunteer editors"</em>. You can still browse <a href="https://web.archive.org/web/20010224172816/http://www.dmoz.org/">a 2001 archive of the old directory</a> to get a sense of how it worked. 

The other way to discover new websites relied on a key feature of the web: hyperlinks. You would go to one website and find your way to many others, much like you can if you go to my "<a href="../../retro-stuff">Retro Stuff</a>" page, where I collect links to interesting things elsewhere on the web. This idea of linking to things <em>elsewhere</em> was particularly common; most websites had a "links" page with their own personal collection of interesting webpages.

This cross-linking was the main way I personally discovered my favourite websites, which I would then add to my bookmarks to be able to find them again later. In fact, the practice of cross-linking had an intersting cultural element: <em>webrings</em>. 

[IMG: Webring]

Webrings were "circular" collections of websites, often around a topic or a theme. The idea was that you could go from one website to another by clicking on the "next" or "previous" buttons usually placed on the footer of each member. These have also largely disappeared.

## Modern Gatekeepers

Today, most of the time spent on the web is either _on_ a small number of very dominant platforms like Facebook, Twitter and LinkedIn, or mediated _through_ them. 

There is so much "content" that is constantly pushed at you as a user that very few of us actually venture out to browse and explore. We simply don't need to. But since these platforms themselves thrive on "user engagement"—likes, comments and shares—their algorithms are more likely to give visibility to content that generates this behavior.

When you're not _receiving_ information passively and instead actually actively looking for something, you most likely have the same singular point of entry as <a href="https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/">87% of all web users</a>: Google. 

Google has become the de facto gatekeeper of the web, an arbiter of what is useful and should get visibility. Except, most websites that appear on the first page—<a href="https://backlinko.com/google-ctr-stats">less than 1% click on something in the second page</a>—are actively designed to be there, owning to search engine optimisation.  One consequence of this though is that most of the websites that people get to "organically" are created by professionals and companies who "position" themselves on those keywords and not by regular people  wanting to share their thoughts and ideas.

Not only is Google largely a _monopoly_— other search engines like Bing, DuckDuckGo and Qwant are becoming more popular but are <a href="https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/">still far behind in adoption</a>, and most still rely on Google's results anyway—it is also a major ad platform using this position and power to actively push its vision of the web.



And this web is quite different from the kind of "small web" crafted by Geocities webmasters. Google's web has a <a href="https://web.archive.org/web/20190214003848/https://marketingplatform.google.com/about/analytics/">different set of values and vocabulary</a> that come with it: personalisation, insights, engagement, conversion, performance, optimisation. 


## The Commercial Web (of Strategy and Marketing)

There has always been a place for commerce and marketing on the web.

Amazon was already selling books online back in 1995, eBay was launched in 1996, Pets.com was big for two years in 1998 . By the 2000s, despite the dot com bust, online commerce started becoming commonplace. This was a natural evolution; the web allowed both individuals and companies to sell to more distant clients without having to rely on phone orders, fax or the postal system. The commercial web co-existed with the personal, artisinal one. The open nature of the web meant that anyone could have a presence. 
	
But today's web is _mostly_ commercial. The smaller web of individuals has neither the resources nor the will to compete for visibility and audience the way the commercial web does. 

Companies and marketers understood that the web presented new opportunities to sell more and _target_ users based on their online activity. They started pouring money into digital ad strategies, analysing how people used the internet, what they talk about, what they search for and what they click on. Marketing companies convinced brands that you had to be online and produce concent to more relevant because that's where their customers already were. They invented words like "native advertising" and "sponsored content", essentially writing made to look like a normal blog post but is really paid advertising. Companies started pouring money their digital strategies to understand and alter online behavior to their advantage.

With content startegy, analytics (the surveillance infrastructure that is present on pretty much all websites you visit that I <a href="../against-a-user-hostile-web">spoke about in my previous article</a>), search engine optimisation, the commercial web had a completely different set of priorities: to <em>engage</em> their "audience", <em>convert</em> them and <em>retain</em> them for as long as possible. 

The web became another marketing channel.

Compared to the same web of regular people, this commercial web is tactical, predatory and aggressive. In just last year, digital ad budget was estimated to be <a href="https://www.emarketer.com/content/global-digital-ad-spending-2019">over 300 billion euros</a>, most of this money going to the same platforms and gatekeepers—Google, and Facebook—that sell their ability to better target you based on the information you give them. 

We now have a situation where you have a very visible commercial web that most of internet users now spend interact with, and a very long tail of smaller, non-commercial websites that are hidden in the noise. 

# The Website as a Product

The modern commercial web is also "sanitised" :  it is polished, follows conventions and is clean and simple. This is one of the reasons so many websites you go to today look and feel the same. The codes of the commercial web have become so dominant that we have forgotten that the small web exists and has a completely different priorities.  

Today's web design principles are very rarely directed at regular people looking to make a website on something they are interested in. No, the focus of modern web design is to create effecient websites that perform well:

Don't use too many colours.  Write short, catchy headlines. Don't let content be too long. Optimise for SEO. Produce video content, people are more engaged. Have a an obvious call to action. Keep important information above the fold. Don't make users think. Follow conventions. That kind of thing.

The basic assumption in modern web design is that you are are a company or a marketer trying to sell something on your website, and "user-centric" means that are trying to reduce the distance between the users' expectations and needs, and what you offer. <a href="https://www.smashingmagazine.com/2008/01/10-principles-of-effective-web-design/">This 2008 article</a> by Smashing Magazine is the top result when I search for "good web design". There are many others, some more recent, but they all pretty much say the same thing. The author of this one even clearly begins by stating that <em>"[...] user-centric design has established as a standard approach for successful and profit-oriented web design</em>".

But the web is not always "profit-oriented" and it certainly does not always need be "user-centric" (and I'm sayign this as a UX consultant). If it were, there would be very little creativity and self-expression. I think the web can also be "me-centered" and ignore every single guideline. 

Because, just like in the Geocities days, a website does not have to be a product; it can also be art.

## The Web as a Creative Space

With the dominance of the commercial web, and the normalisation of its code and values, it is easy for most people to think that the web is a complex machine. Most websites today are built with sophisticated content management systems, have SEO and social media strategies, have Google analytics and audience tracking, require multiple plugins, are responsive and optimized for different devices andd served via a global CDN. 

But the web is really a lot simpler than that. You really only need two things: a web host and HTML (and basic CSS for layout). And you don't need to make it "user-centered" at all. Much like the early webmasters on Geocities carving out their own corner of the web, you can express yourself any way you want. It’s the difference between product and art.

Modern websites are often products — they are designed to direct user behavior towards certain goals: a purchase, a click, a share or a sign-up. The words, the colours, the message are tailored to these goals, much like packaging on products in the super market. 

But the small web is different. A website can simply be an expression of the author’s interests and personality. A painter wouldn’t add more red to her painting, or change the composition, because research shows that people would like it like that. It’s her creative vision; some people might like it, others might despise it. But it is her creation, with her own rules. The question of "performance" is simply irrelevant.

If the commercial web is "industrial", you could say that the small web is "artisinal". One is not better than the other, they serve different needs and both can co-exist. It would nevertheless be a shame to limit our interaction with commercial web and not get to experience the diversity, creativity and quirkiness of the small web.

To show you what it can look like, I have collected a few examples that I think best illustrate the value of the small web.

## Highlights from the Small Web

We will first look at websites from the past and then move on to small websites that are up and running today. 

To present past websites, I rely on the wonderful (and important) internet archival work done by Internet Archive and Restorativland. Inter Archive's "Wayback Machine" lets you turn back the clock and see  what websites looked like in the past, all the way into the 90s. Restorativland is a project by X to _excavate_ and restore old Geocities websites, and re-organise them into their original neighbourgoods. 

Here are some examples:

## 

As excited as I was to find these wonderful relics, I was perhaps even more excited to learn that the small web exists today just as it did back in the Geocities days. It's just less visibile. Among the projects contributing to the small web, two are particularly exciting:  Wiby.me is a search engine for old-school, interesting and informative webpages, with a useful "surprise me" button that takes you to random results. Neocities.org is a modern web host inspired by Geocities with the very similar goal of provoding webspace for anytone to create basic websites, and form a community to follow and keep tabs on your favourite sites. (This website is hosted on Neocities, but I am not related to the project, apart from being a very happy user and member of the community).

Here are some examples:



## Your Own Corner of the Web

So the small web still exists, and is still giving us all kinds of websites to browse through and discover. 

As fun as it is to browse the small web and discover new websites, the best part is really to make your own website and join in. Not on closed platforms, social media mediated by ad companies, or on a discussion forum, but simply in your own little corner of the web. It's the best way to see how simple and open the web really is.

All you would need is to learn basic HTML and CSS, set up a site for free at Neocities.org and start playing. If you have zero experience, It might take you a while to get a hang of how to change text sizes, colours, link between pages and add images, but I think that’s part of the fun. It’s the difference between buying art and learning how to paint, or sculpt. The end result might be the same — a painting — but the exercise is very different. Using a pre-made template is practical but is nothing like creating an HTML page from scratch and put it up on the web for the world to see.

Sure, if you've never coded before, it might seem daunting. But really, you only need the basics to get started. There are services out there that let you create a site without knowing HTML and CSS, but that's if you _need_ a site. Learning basic HTML and CSS is like learning to paint; sure you can commission or buy a painting, but it's not the same thing as learning to paint.

You can always view the source of any public website to take inspiration and learn. Make sure you pick simple, basic ones; the modern web is full of bloated websites that make HTML unreadable.  This website, for example, only uses basic HTML and CSS and I invite you to play with the code to your heart’s extent. It’s all in the public domain, so you can even copy all of it and modify it (and you don’t have to credit me or even link back, it’s all free). 

And if you do make a website, I’d love to see it (and perhaps even add it on here): send me an email at felix@neustadt.fr or send me a tweet at @parimalsatyal. 