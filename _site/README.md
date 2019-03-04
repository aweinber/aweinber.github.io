TC-2 static Elinktricity

Usage
---

To see the site, click [here](https://aweinber.github.io/)

To run it, clone and navigate to the root
directory. Run `jekyll serve ` to run the site
locally.



Design Decisions
---
The band choice -- a Seattle grunge band -- informs every aspect
of the design of the site. (I picked a Seattle band because
I'm most likely moving there after college and my parents love
Pearl Jam.) I chose to make the site simple with dark, brooding
colors and only the essential information to convey the (perhaps
misunderstood) grunge anti-authority no frills ethos. I don't 
know much about grunge, but my instinct is to think that Kurt
Cobain wouldn't have wanted an ornate website with frills and
merchandise and other extraneous info. Instead, the site
limits itself to the essentials: a way to communicate with fans,
and a way to let fans know when how they can see the band.

To maximize general "coolness" and ease of use, the site uses a top
left button to navigate home. That home button location is familiar to users and should
hopefully be innately understood. Similarly, a central footer with
directions to other locations on the site should be intuitive. Lastly, I chose
a color theme with sharp contrast that fits well with the "band photo." The white
and black theme was inspired by those black and white photos of Nirvana guys
smoking cigarettes (not cool!) and playing guitar back in the day. 

Lastly, I separated out the blog site and the home website. I think that may help
users feel like they are directly communicating with the band and not just
receiving some band manager's gobbledygook.


Challenges
---
Trying to set up a solid base for the jekyll project had its challenges. I hadn't
used it before ever, so it took some time to understand best practices for
establishing file hierarchy and communications betweeen different pages. Additionally,
it took me some time to figure out how to add a layout and url to a page with the metadata
in the header.

I wanted to make a dropdown in the right header that could navigate to all pages
at all times, but I'm afraid my overfamiliarity with certain parts of web development
hurt me here. In React, which is the only front end framework I've used, there
are reusable components offered by Google's materialUI library that abstract
away a lot of the css and js required to do more complex things. As such, I have only
written pure css once or twice. 

I also thought that a site without many frills would seem very punk rock, but I guess
that is in the eye of the beholder.

Like I mentioned early on in the course, my biggest challenge with web development
has been things like understanding how users want or expect sites to be laid out.
I thought starting with something simple and easily navigable here would be a good
building block here -- something to build on. As such, I'd like if possible some feedback
on those questions: here are some things I took a bit of a chance on and hope make
sense to users on the first time they work:

The home link when you click pill popping doctors button top left is not obviously and
self-evidently a button. For style reasons, I wanted it to be white so it would 
lend to the contrast of the page and accentuate the bands grunge-ness. Same question
goes for the navigation links in the footer. Many links are blue; these are not. I limited
fluff on the page so I could tweak the essential features of the site in order to 
maximize the style I am trying to harness here without the users needing to search
for something they would expect to look a little different. I hope I was successful
in doing so.

Lastly, I wanted to maintain a core style on the site (as opposed to the blog). As such,
the layouts are relatively similar and differ largely on style points. A fully fledged
website may have more content that could be reduced into reusable layout templates; this site
strives for simplicity and clarity.

 
Credits
---
The main photo of Curt Kobain stage diving is from this [site](http://www.arte.it/notizie/bologna/nirvana-punk-to-the-people-9009)

Some small css syntax stuff came from stack overflow questions [here](https://stackoverflow.com/questions/4108726/how-to-spread-elements-horizontally-evenly) and w3 [here](https://www.w3schools.com/howto/howto_css_image_center.asp)
and [here](https://www.google.com/search?q=on+hover+css&oq=on+hover+css&aqs=chrome.0.0l6.1141j0j7&sourceid=chrome&ie=UTF-8).

I used the jekyll docs as well.
