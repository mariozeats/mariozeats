+++
draft = true
+++

This is the code I want to insert.
The adsense page says to place it between <head> </head> tags

<script data-ad-client="ca-pub-2177559163030064" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

I first tried going into mariozeats\themes\huge-future-imperfect\layouts\partials and creating an adsense.html file and just dropping in the script. And then trying to insert a  {{ partial "adsense" . }} into mariozeats\themes\huge-future-imperfect\layouts\single.html

Couldn't even commit changes since it says error code 1 was called. looking up online says this may happen if you have nested git repositories I think?

Then I tried just adding the script into mariozeats\themes\huge-future-imperfect\layouts\partials\header.html

Nope.

I notice that when I try changing the stuff within themes that in VSCode, the source control shows changes in both my mariozeats git AND my huge-future-imperfect git. Whatever that means. 
When I edit or create just a post like this one, for example, I only see just a change in mariozeats git.

Not sure if this makes sense. If you just try to insert the script into the partials header.html you can probs replicate the bug.

thank you smart one.

BLAHHHHHH
