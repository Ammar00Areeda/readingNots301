## Who is Roy Fielding?

In addition to his job at Adobe, he is also a Senior Principal Scientist at Sun Microsystems. He drafted the HTTP/1.x and URI standards, contributed to a number of other Web technologies, and established the REST architectural style.

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

Because machines lack a universal word, they are inherently ineffective. The way nouns are discussed varies from programming language to database to system to system. That's why a URL is so critical. It allows all of these systems to communicate about the nouns of one another.


## What is the HTTP protocol that Fielding and his friends created?

The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.


## What does a GET do?

the browser does an HTTP GET on the URL you typed in and back comes a web page.

## What does a POST do?

If one system needs to add something to another system, it would use an HTTP verb of POST.

## What does PUT do?

If a system wants to replace something in another system, it uses an HTTP verb of PUT

## What does PATCH do? 

to do a partial update, it'll hopefully use PATCH.

-----------

