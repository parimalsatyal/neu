In Defense of The Small Web

*Most websites today are built like commercial products: made to draw the largest audience, optimised to generate engagement, designed by professionals or companies and "pushed" either via search engine optimisation and online advertising. But there is also a smaller web that is less visible, designed by regular people simply to share their interests and hobbies with the world. A web that is unpolished, often quirky but also creative and informative.*

<p>Every website design begins with inspiration. </p>

<p>For this one, there were two: Anders' <a href="anders.unix.se">clean, readable 10k website</a>, which inspired the homepage, and a site I stumbled upon called <a href="https://marijnflorence.neocities.org/index.html">Marijn's site</a>, which reminded me just how _fun_ the web can be. The colours, graphics, <a href="https://marijnflorence.neocities.org/music/">creative navigation</a>, <a href="https://en.wikipedia.org/wiki/Holocene_calendar">interesting ideas</a>... the simple fact of clicking through pages of someone's personal website in 2020 made me nostalgic of the web of the late 90s and early 2000s that I grew up with.</p>

<p>Some of you might have read my previous article, [Against an Increasingly User Hostile Web](../against-a-user-hostile-web/). In it, I argue that we are replacing an open web that connects and empowers with one that restricts and commoditises people. I talk about how the modern web of surveillance, bloat and walled gardens is at odds with the open web that I grew up with. I was pleasantly surprised by how much the sentiment seemed to be shared by so many other people who emailed me, <a href="https://www.eduardomorais.com/stream/id/3519">wrote responses on their own blog</a> or <a href="https://news.ycombinator.com/item?id=15611122">discussed it</a> on <a href="https://lobste.rs/s/5bi46y/against_increasingly_user_hostile_web">online forums</a>. Despite being two and a half years old, that article still disappointingly reflects the state of the web today. </p>

<p>But stumbling upon Marijn’s site gave me hope. It led me down a rabbit hole of many other small websites made by people with all kinds of interests: movies, aviation, music, art, computers. It reminded me that the creative, personal, _fun_ web I grew up with is not a thing of the past. In 2020, it’s still here. You just have to know where to look.</p>

<p>This essay is my attempt to show you what the small and independent web can look like, why it’s different from the the sites that dominate web traffic today and how easy it is for anyone to be a part of it. Including you, if you want to.
</p>

<p>This essay is somewhat long; you might find this table of contents handy:</p>

1. Retro Redesign
2. The First Webpages
3. Masters and Navigators
4. Modern Gatekeepers
5. The Commercial Web (of Marketing)
6. The Product-centric Website
7. The Web as a Creative Space
8. Highlights from the Small Web
9. Your Own Corner of the Web
10. Thoughts and Feedback

<h2>Retro Redesign</h2>

<p>On my homepage, I mention that this website is “a tribute to the creative web of the 90s”. This is not simply because this website has animated gifs and a [guestbook](https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60). The *way* I built it — the "technology stack" as one might call it today — is also inspired by my earliest websites. In fact, it's mainly just one thing: <strong>plain HTML</strong>.</p>

<p>No content management systems, no generators, no templates, no themes, no plugins. Just plain markup and styling, the most basic of the basic building blocks of the web. </p>

<p>I didn’t originally plan to do it like this. I previously <a href="../crafting-a-simple-blog-with-metalsmith">used a static site generator</a> to output plain HTML and was simply working on a new design template for that. But my three-year-old node.js setup was now spewing error messages, telling me some dependencies had to be updated and that a plugin was no longer compatible. Because I'm lazy and didn't want to fix any of that, I wondered if I couldn’t just do it all manually instead and save myself the trouble. </p>

<p>So I did. I decided to hand-code everything in plain HTML and CSS, manually link all the pages and even hand-write the RSS feed. And to be honest, I haven’t had this much fun making a website since when I first started playing around with <a href="https://www.webdesignmuseum.org/old-software/html-editors/microsoft-frontpage-97">Microsoft Frontpage</a> and <a href="https://www.webdesignmuseum.org/old-software/graphic-software/adobe-photoshop-4-0">Adobe Photoshop 4.0</a> in the late 90s and early 2000s.</p>

<p>This approach won't work for a bigger website. But for a small one like mine with about 10 total pages, it has many obvious benefits: next to no dependencies, easy to maintain, reasonably future proof, easily portable and most important of all, terribly fun to work on! I stayed up till six in the morning for two straight days working on the redesign, not because I couldn’t sleep but because I didn’t want to stop. Admittedly, about 30% of that time was spent scouring <a href="https://gifcities.org/">GifCities.org</a> and the <a href="https://archive.org/web/">Internet Archive</a> for animated GIFs and backgrounds (which is different for each page; that's an added benefit of using plain HTML).</p>

<p>The process of redesigning my website this way inspired me to scour archives of old websites for interesting relics from the early web. This in turned led me to the creative, fun, independent websites that are actively maintained even today. </p>

<p>To understand what these small websites represent and why I think they are important, we need to start in the past.</p>

<h2>The First Webpages</h2>

<p>The web was still in its infancy in the early 90s. You probably know the story.</p>

<p>It had only just been <a href="https://home.cern/science/computing/birth-web/short-history-web">invented by Sir Tim Berners-Lee</a> in 1991 and released into the <a href="https://home.cern/science/computing/birth-web/licensing-web">public domain</a> in 1993, making it available for free to anyone in the world to use and build on. In its very early days, it was really only accessible to the more technical crowd, much like <em>Gopher</em>, <em>FTP</em>, <em>Usenet</em> and other internet protocols at the time. It wasn't until the first easy-to-use graphical browser <a href="http://www.ncsa.illinois.edu/enabling/mosaic">Mosaic</a> was released for free in 1993 that regular computer users discovered the web for the first time. Others like myself discovered it later still when the Mosaic-spinoff <a href="http://sillydog.org/netscape/">Netscape Navigator</a> (the foundation of today's <a href="https://www.mozilla.org/en-GB/firefox/new/">Firefox</a>) and Internet Explorer became commonplace. </p>

<p>It was all terribly exciting. Unlike traditional media, you could now speak back and participate. It was the first interplanetary communication system where anyone, anywhere in the world, could make a page and share their thoughts and ideas with the world. Netscape would later even include <a href="https://www.ccsf.edu/Pub/Fac/composer.html">an editor</a> that let users make webpages visually, like using a word-processor ("WYSIWYG", as it was called back then: <em>what you see is what you get</em>). The goal was to enable anyone, even those without the technical skills, to put a page up.</p>

<p>But if you wanted your web page to be "on the web", where would you put it? </p>

<p>You needed a web host of some sort to store the pages and share a public address so other people could visit. It would ideally also be free so people could try things for fun without thinking about it too much. There's where <a href="https://web.archive.org/web/19980704165228/http://www20.geocities.com/join/freehp.html">Geocities</a> came in, along with other free web hosts like <a href="https://web.archive.org/web/20000815052634/http://www.tripod.lycos.com/">Tripod</a>, <a href="https://web.archive.org/web/20000229235048/http://www.fortunecity.com/build/index.html">Fortunecity</a> and <a href="https://web.archive.org/web/20000815053429/http://www.freeservers.com/">Freeservers</a>. They were perhaps perhaps the biggest catalysts to democratising the web. </p>

[IMG: Geocities from the past]

[IMG: Freeservers from the past]

<p>It was so simple, anyone who wanted to could set up their website could create a free account and build a website to share their hobbies and ideas. And share they did! People made websites about virtually everything: music, philosophy, ancient civilisations, <a href="https://web.archive.org/web/20011004132631/http://www.geocities.com/~intransit1/home/home_frm.html">art projects</a>, <a href="https://web.archive.org/web/20010424064639/http://www.geocities.com/spunk1111/">ASCII art</a>, <a href="https://web.archive.org/web/20000815075236/http://www.pezcentral.com/pezmenu.html">candy</a>, and about their lives. </p>

<p>A key detail was that most people who made these websites were neither professionals nor companies; they were people who just wanted to share their interests. Like I did back in 2001 with my <a href="">unofficial fansite for German metal band Gamma Ray</a>: </p>

[IMG: My Geocities site about Gamme Ray]

<p>But how would someone go about finding these pages? We didn't have Google in the early days. Other search engines like <a href="https://web.archive.org/web/19980214192548/http://www.lycos.com/">Lycos</a>, <a href="https://web.archive.org/web/19970630113649/http://www06.excite.com/">Excite</a> and <a href="https://web.archive.org/web/19980206192654/http://www.northernlight.com/">Northern Lights</a> did exist but were nowhere near as efficient as modern search engines. Finding something you were interested in was not as simple as typing a few words and getting to that information in one click.</p>

<p>No, the web was much more of an adventure. It was a _place_ that you wandered to discover new places, like exploring the vast open seas, with and its fair share of dangers (viruses, trojans, annoying pop-ups). A new virtual space that lead to all kinds of strange, interesting, exciting places. This is what the web was like, at least, in our collective imagination.</p>


<h2>Masters and Navigators</h2>

<p>The web had was a different kind of place in those early years, and we had different words to talk about it. In an article titled <a href="https://rhizome.org/editorial/2015/nov/30/oldweb-today/">Cyberspace, the old-fashioned way</a>, authors at the Rhizome project make a very important point:</p>

<blockquote>Today's web browsers want to be invisible, merging with the visual environment of the desktop in an effort to convince users to treat "the cloud" as just an extension of their hard drive. <strong>In the 1990s, browser design took nearly the opposite approach, using iconography associated with travel to convey the feeling of going on a journey.</strong> Netscape Navigator, which used a ship's helm as its logo, made a very direct link with the nautical origins of the prefix cyber-, while Internet Explorer’s logo promised to take the user around the whole globe. </blockquote>

[IMG: Logos of Internet Explorer and Netscape Navigator]

<p>Navigation. Exploration. Browsing. Surfing.  The web was akin to a virtual manifestation of physical space. We even had a word for it: "webspace". In Geocities, this was expressed with the notion of <em><a href="https://web.archive.org/web/19980704165140/http://www20.geocities.com/neighborhoods/">neighborhoods</a></em>, creatively-named categories like <em>Area51</em> for sci-fi, <em>Heartland</em> for families and pets, <em>RainForest</em> for the environment, <em>Vienna</em> for classical music, <em>CapeCanaveral</em> for science and mathematics.</p>

[IMG: List of Geocities neighbourhoods]

<p>Another word that was very common back in the Geocities days that has since died out is the word "webmaster" (mostly gender-neutral, although sometimes declined to the feminine "webmistress"). The idea was that you created a <em>space</em> on the web, of which you were the <em>master</em>. You welcomed visitors (sometimes with a splash screen), you guided them around by explaining what they might find and the different spaces available to them (usually on the home page) and reminded them to leave a word on the guestbook on their way out.</p>

<p>But the semantics of the web of yore made sense in the context of how you _practically_ interacted with it. You very rarely just came in for one specific thing and left; you usually <em>entered</em> a website and looked around. You _browsed_.</p>

<p>Which takes us back to the original question of how you found websites to visit in the first place. You were lucky if your small site showed up in pre-Google search engines, but even if it did, it would mean that somebody would have to be looking for it. But not everybody who visited your website <em>was</em> looking for anything specific. They might simply have wanted to find other websites on a topic they were interested it.</p>

<p>One way of doing so was by browsing directories, like the Geocities neighbourhoods: lists of websites often arranged by categories and sub-categories. In fact, most search engines were also directories, or _portals_ as they were called back then.
</p>

[IMG: Screenshot of search engine directory from the past, Lycos or something]

<p>One of the biggest ones was the <a href="https://web.archive.org/web/20010206123038/http://www.dmoz.org/about.html">DMOZ open-directory project</a>, based on the original Mozilla directories, whose goal was to <em>"produce the most comprehensive directory of the web, by relying on a vast army of volunteer editors"</em>. You can still browse <a href="https://web.archive.org/web/20010224172816/http://www.dmoz.org/">a 2001 archive of the old directory</a> to get a sense of how it worked.</p>

<p>The other way to discover new websites relied on a key feature of the web: hyperlinks. You would go to one website and find your way to many others, much like if you go to my "<a href="../../retro-stuff">Retro Stuff</a>" page and follow one of the links to something interesting elsewhere on the web. This idea of linking to things <em>elsewhere</em> was particularly common; most websites had a "links" page with their own personal collection of interesting webpages.</p>

<p>This cross-linking was the main way I personally discovered my favourite websites, which I would then add to my bookmarks to be able to find them again later. In fact, the practice of cross-linking had an intersting cultural element: <em>webrings</em>. </p>

[IMG: Webring]

<p>Webrings were "circular" collections of websites, often around a topic or a theme. The idea was that you could go from one website to another by clicking on the "next" or "previous" buttons usually placed on the footer of each member. These have also largely disappeared.</p>

<h2>Modern Gatekeepers</h2>

<p>Today, most of the time spent on the web is either _on_ a small number of very dominant platforms like Facebook and LinkedIn, or mediated _through_ them. </p>

<p>There is so much "content" that is constantly pushed at you as a user that very few of us actually venture out to browse and explore anymore. We simply don't need to. But these platforms thrive on "user engagement"—likes, comments, clicks and shares—and their algorithms are more likely to give visibility to content that generates this behavior. Instead of browsing, the web is for many an endless and often overwhelming stream of content and commentary picked for you by algorithms based on what they think you already like and will <em>engage</em> with. It's the opposite of exploration. </p>

<p>When you're not _receiving_ information passively and instead actually actively looking for something, you most likely have the same singular point of entry as about <a href="https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/">87% of all web users</a>: Google.</p>

<p>Google has become the de facto gatekeeper of the web, an arbiter of what is useful and what should get visibility. Except, most websites that appear on the first page, the links that you are most likely to click on—<a href="https://backlinko.com/google-ctr-stats">less than 1% of searchers click on something in the second page</a>—are designed by be there by optimising for Google's algorithms. One consequence of this  is that most of the websites that people get to "organically" are created by professionals and companies who "position" themselves on those keywords. This means that the smaller, amateur web gets hidden in the shadows of web professionals who design to be visible for certains keywords and audiences.</p>

<p>Not only is Google largely a monopoly in search— other search engines like Bing, DuckDuckGo and Qwant are <a href="https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/">still far behind in adoption</a>—it is also the biggest ad selling platform. Last year, it represented "31.1% of worldwide ad spending, or $103.73 billion" (<a href="https://www.emarketer.com/content/global-digital-ad-spending-2019">source</a>). The power that comes from being in such a position, along with being present almost all major websites (through their widely-used analytics platform, despite the <a href="https://www.emerald.com/insight/content/doi/10.1108/OIR-02-2018-0056/full/pdf?title=protecting-privacy-on-the-web-a-study-of-https-and-google-analytics-implementation-in-academic-library-websites">numerous privacy concerns</a>) means it can actively push its own vision of the web.</p>

<p>And this web is quite different from the kind of "small web" crafted by webmasters of the 90s and early 2000s. Google's web has a <a href="https://web.archive.org/web/20190214003848/https://marketingplatform.google.com/about/analytics/">different set of values and vocabulary</a> that come with it: personalisation, insights, engagement, conversion, performance, optimisation. </p>


<h2>The Commercial Web (of Marketing)</h2>

<p>There has always been a place for commerce and marketing on the web.</p>

<p><a href="https://www.webdesignmuseum.org/web-design-history/amazon-com-1995">Amazon</a> was already selling books online back in 1995, <a href="https://www.webdesignmuseum.org/web-design-history/ebay-1997">eBay</a> was launched in 1997, <a href="https://web.archive.org/web/19970605120422/http://www.dell.com/">Dell</a> sold over a million dollars worth of equipment by the end of 1997. By the 2000s, despite the <a href="https://ideas.ted.com/an-eye-opening-look-at-the-dot-com-bubble-of-2000-and-how-it-shapes-our-lives-today/">dot com bust</a>, online commerce was growing. This development was natural; the web enabled sellers to reach more distant clients without having to rely on phone orders, fax or the postal system. The commercial web co-existed and grew with the personal, amateur one. The open nature of the web meant that all kinds of websites could thrive.</p>
	
<p>But today's web is _mostly_ commercial. The smaller web of individuals has neither the resources nor the will to compete for visibility and audience the way the commercial web does.</p>

<p>Companies and marketers understood that the web presented new opportunities to sell more and _target_ users based on their online activity. They started pouring money into digital ad strategies, analysing how people used the web, what they talk about, what they search for and what they click on. Marketing companies convinced brands that you had to be online and produce content to be more relevant because that's where their customers already were. They invented words like "native advertising" and "sponsored content" (essentially writing that is made to look like a normal blog post but is really paid advertising). Companies started pouring money into their digital strategies to understand and alter influence the behavior of internet users to their advantage.</p>

<p>With its content startegy, analytics (the surveillance infrastructure that I <a href="../against-a-user-hostile-web">spoke about in my previous article</a>) and search engine optimisation, the commercial web brought a completely different set of priorities: to <em>engage</em> their "audience", <em>convert</em> them and <em>retain</em> them for as long as possible.</p>

<p>For them, the web is just another marketing channel.</p>

<p>Compared to the small web, this commercial web is tactical and predatory. It can dynamically generate hundreds of pages around common search queries. It can follow web users across different websites, analyse their interactions, and use that information to target them more precisely. It also has serious resources. Just last year, companies spent over <a href="https://www.emarketer.com/content/global-digital-ad-spending-2019">over 300 billion euros</a> in online digital advertising, most of this money going to the same platforms and gatekeepers—Google and Facebook—that sell their ability to better target you based on the information you give them. </p>

<p>What this means is that most internet users interact and spend their time on the visible commercial web, while the very long tail of smaller, amateur websites remains hidden in the noise. 
</p>

<h2>The Product-oriented Website</h2>

<p>The design of the modern commercial web is also "sanitised": it is polished, follows conventions and is optimised for efficiency. This is one of the reasons so many websites you go to today look and feel the same. The codes of the commercial web have become so dominant that we have forgotten that the small web still exists and has a completely different priorities.</p>

<p>Modern web design principles are very rarely directed at regular people looking to make a website on something they are interested in. Instead, the focus is on creating websites that perform well:</p>

<p><em>Don't use too many colours.  Write short, catchy headlines. Don't let content be too long. Optimise for SEO. Produce video content, attention span is decreasing. Have a an obvious call to action. Push your newsletter. Keep important information above the fold. Don't make users think. Follow conventions.</em> That kind of thing.</p>

<p>Modern websites are designed to direct user behavior towards certain goals: a purchase, a click, a share or a sign-up. The words, the colours, the message are tailored to these goals, much like packaging on products in the super market. </p>

<p>A 2008 article called by Smashing Magazine called <a href="https://www.smashingmagazine.com/2008/01/10-principles-of-effective-web-design/">10 Principles Of Good Website Design</a> was the top result when I search for "good web design" whilst writing this essay. There are many others, some more recent, but they all pretty much say the same thing. The author of this one even clearly begins by stating that <em>"[...] user-centric design has established as a standard approach for successful and profit-oriented web design</em>".</p>

<p>But the web is not always "profit-oriented" and it certainly does not need be "user-centric" (and I say this as a UX consultant). If it were, there would be very little creativity and self-expression left. The rich diversity of the web would be reduced to the online equivalent of an orderly, clinical, consistent shopping mall meant to drive sales. No, the web can just as well be "author-centered", topic-centered, or hobby-centered. Heck, it can even be dog-centered.</p>

<p>It is worth remembering a website does not have to be a product; it can also be art. <strong>The web is also a creative and cultural space that need nod confine itself to the conventions defined by commercial product design and marketing</strong>.</p>

<h2>The Web as a Creative Space</h2>

<p>With the dominance of the commercial web and the normalisation of its code and techniques, it is easy for most people to think that the web is a complex machine. Most websites today are built with sophisticated content management systems, with SEO and social media strategies, feature detailed analytics and audience tracking, require multiple plugins, are optimized for different devices and served via a global CDN.</p> 

<p>But the web is really a lot simpler than that. You really only need two things: a web host and HTML (and basic CSS for layout). And you don't need to make it "user-centered" or run analytics at all. Much like the early webmasters on Geocities carving out their own corner of the web, you can express yourself any way you want. It’s the difference between product and art.</p>

<p>A painter wouldn’t add more red to her painting, or change the composition, because research shows that people would like it like that. It’s her creative vision; some people might like it, others might not. But it is her creation, with her own rules. The question of "performance" is simply irrelevant. It's the same thing with the small web.</p>

<p>If the commercial web is "industrial", you could say that the small web is "artisanal". One is not better than the other. They serve different needs and both can co-exist in an open web. It would nevertheless be a shame if the only the commercial web got any visibility, and web users never got the opportunity to experience the creativity, passion and quirkiness of the small web.</p>

<p>To show you what the it can look like and how different it can be from modern websites, I have collected a few examples that I think best illustrate the richness of the small web.</p>

<h2>Highlights: From the Past</h2>

<p>We will first look at websites from the past and then move on to small websites that are up and running today. </p>

<p>To be able to dig up these websites from the past, I rely on the wonderful and important internet archival work done by people who care about web history, including: </p>

<ul>
	<li><a href="https://archive.org/web/">Internet Archive</a>, which, thanks to the 439 billion web pages saved since the mid 90s, lets you travel back in time and see how a website looked in the past.</li>
	<li><a href="https://restorativland.org/">Restorativland</a>, a "restored visual gallery of the archived Geocities sites, sorted by neighborhood".</li>
	<li><a href="http://www.fortunecity.ws/">FortuneCityws Archive Project</a>, a searchable archive of old FortuneCity websites.</li>
</ul>

<p>Here are some examples:</p>

<h3>On to Mars!</h3>

<p>The description couldn't be clearer: "<em>This is the homepage about the colonization and terraforming of our neighbor planet Mars.</em>" A very detailed website that describes the red planet in its current state, details about past and potential future manned missions to Mars, an explanation of what <em>terraforming</em> involves and how you would go about it and even a page on interplanetary commerce! This website also shows you how useful the "links" section could be if you wanted to explore this topic futher.</p>

[IMG: Screenshot Mars site]

<p>Visit <a href="https://geocities.restorativland.org/CapeCanaveral/Cockpit/2189/"><strong>On to Mars!</strong></a> on Restorativland.</p>

<h3>The National Coca-Cola Bottle Clearing House</h3>

<p>A website is probably the only (surely definitive) list Commemorative Coca-Cola Bottles on the web. It lists every single version of commemorative bottles since the 70s, organised by bottle/can size. There are some surprising entries. For example, did you know there was an 8oz (~240ml) "Dominos Pizza International Expo 1991" edition, or that such an expo was existed at all? Or an 10oz (~300ml) English Royal Wedding one in 1982?</p>

[IMG: Screenshot of Coca cola site]

<p>It was last updated in the year 2000 but you can visit <a href="https://geocities.restorativland.org/Heartland/2983/"><strong></strong>The National Coca-Cola Bottle Clearing House</a> on Restorativland.</p>

<h3>The Rocky Road Webpage</h3>

<p>A fun little website with riddles, word and logic puzzles, poetry (including Robert Frost’s “<a href=“https://geocities.restorativland.org/Athens/Olympus/1406/poetryms.html#ROADNT”>The Road Not Taken</a>” and William Blake’s “<a href=“https://geocities.restorativland.org/Athens/Olympus/1406/poetrytz.html#TIGER”>The Tiger</a>”), along with a page on the <a href="https://geocities.restorativland.org/Athens/Olympus/1406/optimist.html">author</a> himself. (Hint: You have to click on the spoons to enter each section of the website.)</p>

[IMG: Screenshot ]

<p><a href="https://geocities.restorativland.org/Athens/Olympus/1406/main.html"><strong>Visit the Rocky Road Website</strong></a> on Restorativland.</p>

<h3>Supervillain Central

<p>A website from 1997 "<em>dedicated to the criminally insane!</em>", this website has <a href="https://web.archive.org/web/20021205180116/http://www.geocities.com/televisioncity/set/2800/archives/">an extensive archive</a> of almost all supervillians from cartoons and animated movies, including Mr. Burns, <a href="https://web.archive.org/web/20020214031306/http://www.geocities.com/TelevisionCity/Set/2800/brain/">The Brain</a>, <a href="https://web.archive.org/web/20020114210041/http://www.geocities.com/TelevisionCity/Set/2800/archives/b.html">Boris</a> and <a href="https://web.archive.org/web/20020114210041/http://www.geocities.com/TelevisionCity/Set/2800/archives/n.html">Natasha</a> and even <a href="https://web.archive.org/web/20090804171452/http://geocities.com/TelevisionCity/Set/2800/archives/s.html">Stewie</a>. For each one, the site includes additional information, including alias, day job ("baby" for Stewie), accomplices, known hide-outs, previous offenses and famous quotes.</p>

[IMG: Screenshot]

https://web.archive.org/web/20021205102119/http://www.geocities.com/televisioncity/set/2800/main.html


<h2>Highlights: From the Present</h2>

<p>As excited as I was to find these wonderful relics, I was even more excited to learn that the small web exists today just as it did back when I was a kid. It's just less visibile. Among the projects contributing to keeping the small web alive, three are particularly exciting to me:  </p>

<ul>
	<li><a href="https://wiby.me">Wiby.me</a> is a search engine for old-school, interesting and informative webpages, with a useful "surprise me" button that takes you to random results. </li>
	<li><a href="https://neocities.org">Neocities.org</a> is a modern web host inspired by Geocities with the very similar goal of provoding webspace for anytone to create basic websites, and form a community to follow and keep tabs on your favourite sites. </li>
	<li><a href="https://curlie.org/">Curlie</a> is "the largest human-edited directory of the Web. It is constructed and maintained by a passionate, global community of volunteer editors", much like DMOZ.</li>
</ul>

<p>Here are some examples:</p>

<h3>Ottaviana's Kitchen</h3>

<p>This website from 1996 that is still up today, with Italian family recipes passed down from generation to generation.</p>

[IMG: Screenshot]

<blockquote>My Grandparents were immigrants from Italy. They came to Ellis Island, in search of the great American dream. This was where my mother was born in Newark, NJ. The recipes were passed to her from her mother, and then passed to me from mine. Since I have no
children of my own, what better way to pass on these recipes but
on my we page so everyone can enjoy them, and maybe start their
own tradition with them. So for now, Buon Appetito.</blockquote>

<p>You can read the <a href="http://ottavianaskitchen.com/menu.htm">entire menu</a> and find authentic recipes to <a href="http://ottavianaskitchen.com/sauces.htm">sauces</a>, <a href="http://ottavianaskitchen.com/soups.htm">soups</a>, <a href="http://ottavianaskitchen.com/risotto.htm">risotti</a>, <a href="http://ottavianaskitchen.com/cookies.htm">cookies and dessert</a>, and much much more.
</p>
<a href="http://ottavianaskitchen.com/intro.htm"><strong>Visit Ottaviana's Kitchen</strong></a>.

<h3>Europäische Schmetterlinge</h3>

<p>This is a German website about European butterflies created in 1998 and maintained until 2005 by Mario Maier. But it isn't just _any_ old website about butterflies, this one is a near-exhaustive collection of almost all butterflies in Europe organised by genus/species, each with a description, an indication of its "flight time" and the corresponding caterpillar's plants of choice, along with photos (most taken by the author himself).</p>

[IMG: Screenshot]

<p>Some of the pages like <a href="http://www.butterflies.de/Deutsch/ainsae.htm">this one on <em>Agrodiaetus ainsae</em></a> seem to be have more information than currently <a href="https://en.wikipedia.org/wiki/Polyommatus_fulgens">available on Wikipedia</a>! I originally found the <a href="https://geocities.restorativland.org/Paris/Cafe/1508/">Geocities version</a> on Restorativland and then found this version that is currently up.</p>

<a href="http://www.butterflies.de/"><strong>Visit Europäische Schmetterlinge</strong></a>.

<p class="update">It looks like the same author had a larger website for <em>all</em> butterflies on Earth that was up until 2018. You can visit <a href="https://web.archive.org/web/20180421072253/http://www.butterflycorner.net/Schmetterlinge-aus-aller-Welt.1.0.html">an archived copy of Butterfly Corner</a>.</p>


- 


<h2>Your Own Corner of the Web</h2>

<p>So the small web still exists, and is still giving us all kinds of websites to browse through and discover. 
</p>

<p>As fun as it is to browse the small web and discover new websites, the best part is really to make your own website and join in. Not on closed platforms, social media mediated by ad companies, or on a discussion forum, but simply in your own little corner of the web. It's the best way to see how simple and open the web really is.</p>

<p>You could easily put up those drawings you've been making, or a review of your favourite whiskys. Make a website to share your writing tips, or your best recipes. Make a list of your favourite addresses in your city.</p>

<p>All you would need is to learn basic markup (HTML) and styling (CSS), set up a site at a free host like <a href="https://neocities.org">Neocities.org</a> and start playing. </p>

<p>HTMLDog has excellent tutorials to learn <a href="https://htmldog.com/guides/html/beginner/">basic HTML</a> and <a href="https://htmldog.com/guides/css/beginner/">basic CSS</a>. And if you prefer video, Khan Academy has an excellent free course for beginners called "<a href="https://www.khanacademy.org/computing/computer-programming/html-css">Making Webpages</a>" that looks very complete.</p>

<p>If you have zero experience, It might take you a while to get a hang of how to change text sizes, colours, link between pages and add images, but I think that’s part of the fun. </p>

<p>It’s the difference between buying art and learning how to paint, or sculpt. The end result might be the same but the exercise is very different. Using a pre-made and packaged theme or template to build a site is practical but is nothing like creating an HTML page from scratch and putting it up on the web for the world to see. </p>

<p>Another great thing about the web is that you can always view the source of any public website to take inspiration and learn. Make sure you pick simple, basic ones; the modern web is full of bloated websites that make HTML unreadable. This website, for example, only uses basic HTML and CSS and I invite you to play with the code to your heart’s extent. It’s all in the <a href="../../license.tt">public domain</a>, so you can even copy all of it and modify it (and you don’t have to credit me or even link back, it’s all free).</p>

<p>If you do end up making a website after reading this, I’d love to see it (and perhaps even add it on here): send me an email at felix@neustadt.fr. </p>

<h2>Thoughts and Feedback</h2>

<p>The small web has a lot to offer.</p>

<p>Some of it is rich and informative, some weird and whacky and others downright strange. You can find websites on pretty much anything you are interested it, and discover music, art, software and tutorials. You can learn about how other people live and what they think. It might be tiny and hidden compared to the commercial web, but that's part of its charm; you get to experience "browsing" and scouring the web like we did in the 90s and early 2000s.</p>

<p>And you get to easily join in on the fun and create your own little corner.</p>

<p>I hope this essay has been interesting. If you have thoughts about the topic—you agree, you disagree, you have examples or corrections—I would love to hear from you. You can email me at <a href="mailto:felix@neustadt.fr">felix@neustadt.fr</a>. For the more technical lot, this article (along with everything else on this website) is on <a href="#">GitHub</a>; you can also send me a pull request with edit suggestions.</p>

<p>I hope you enjoyed your stay on my website. Feel free to browse  around, the <a href="../../retro-stuff">Retro Stuff</a> has other relics from the 90s and the 2000s. And of course, you can <a href="https://users2.smartgb.com/g/g.php?a=s&i=g26-37520-60">sign my guestbook</a> on your way out.</p>

