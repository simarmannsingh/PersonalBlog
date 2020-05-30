# [Blog](https://simarmannsingh.de/)

![Blog Preview](https://github.com/simarmannsingh/personalblog/blob/gh-pages/preview.png "Preview generated as on 4th May 2020")

## About

This is the public repository which serves as the web-hosting for the personal blog website 
<https://simarmannsingh.de/>. The blog is essentially a collection of lucid blog posts written
specifically to explain technical concepts in a layman words. No-prior knowledge is required to understand the blog posts.

Readers are encouraged to post honest opinions in comments and to share the content with their friends and family. It also helps me to clarify many concepts for myself because it is a fact that when you have to explain something to someone else, you study it thoroughly and hence you understand it better.

Readers are encourage to also start writing blogs themselves and try to write it in as easy language as possible. You can share your links with me via email or you can also post them as comments on my blog post. However, please do NOT spam the links everywhere.


## Security and Data Collection
I am pleased to announce that the website collects no user data whatsoever, absolutely NONE. As a matter of fact, I hate the websites which keep tracking the user's activity by placing cookies. You can check for yourself that this website does not use any cookie at all.

However, For the secure functioning of the website itself, the CloudFlare Servers uses one cookie 
called **_cfduid**. The cookie does not collect any kind of data, but it serves the purpose of authenticating a user. So, the servers can know if it is a bonafied user or a malicious program/hacker trying to break in.
How does the cookie do that? The cookie randomly generates a unique number long (long enough to be unique) and stores that number as a cookie. So whenever the user makes a request again, the same cookies is sent to the server authenticating that the user is indeed a genuine user. This also serves in distinguishing the number of views (or hits) a website gets as the subsequent requests containing a cookie are not considered multiple views. So, no matter how many times a user views the contents, it is still counted as one view, until the cookie is destroyed and a new cookie is fetched from the server.
Further details about the functioning of this specific cookie can be found [here](https://support.cloudflare.com/hc/en-us/articles/200170156-Understanding-the-Cloudflare-Cookies#12345682)

### Note to Security Researchers 
Securtiy researchers can now report vulnerabilites in the website using secure channel. The standard Security.txt file can be accessed at [this location](https://simarmannsingh.de/.well-known/security.txt). The file security.txt contains details on how to contact the developer and report vulnerabilites using excrypted email. The file also contains sha256 checksum for pgp_public.asc file. So you can check the sha256 checksum and verify if the file you got is the actual file you think it is. In case someone made any changes to the file, the checksum would not be same.

Use the following command in terminal (for linux baes OS) to get the sha256 checksum.
    sha256sum <filename>

## Copyright and License

Copyright 2020 Simar Mann Singh Chawala. Code released under the [MIT](https://github.com/simarmannsingh/personalblog/blob/gh-pages/LICENSE) license.

All the text content written on the blog, many of the illustrations are copyrighted content and hence cannot be used for personal or commercial purposes without permission. No part or whole of the blog post can be reproduced without permission. However, readers are allowed to use the content and infact encouraged to do so, provided they give proper credits to the author. At this point, I would like to mention that the template that this website is based on (called startBootstrap), is not my copyrighted content. It is an open-source Bootstrap project with an MIT license.

I would like to thank (and give credit to) David Miller, the founder of Start Bootstrap project. He is also the founder of BlackrockDigital LLC, the company name he operates under. Further details about David can be found on his website http://davidmiller.io.

Readers are encouraged to visit the website <https://simarmannsingh.de> and comment after reading the blog posts. All a Blogger wants is to share his ideas with the world and seeks nothing in return.

*The present day world needs more Open-source developers than everything else.*