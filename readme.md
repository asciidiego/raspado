Raspado
=======

> Raspado is a *lean* web scraper intended to parse data from many
sources. Its goal is not **speed**, but **flexibility**

At [Code for Venezuela](#) we have projects that depend on data. But,
many times, because of the difficult situation of the country, the data
is not easy to digest. 

As usual, data tends to be *dirty* but, at the organization, it comes
from *many sources*. This is where `raspado` comes into play.

. Since we will
have to extract many sites, we follow

> Configuration over implementation

This means that the core of the project must be simple to extend and
configure, without putting much effort in efficiency or speed.

Besides simplicity, the only requirements are the usual web scraping
requirements: **respecting the content server**. Now, the project
is new and used for small-scale operations. But, a single machine can
already attack servers (i.e. Denial of Service) and, thus, hurt the
experience for both server(s) and clients.

Enjoy and happy scraping!
