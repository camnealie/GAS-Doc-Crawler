# GAS-Doc-Crawler
Crawls internal Google Apps/Drive documents for hyperlinks, for eventual use in a relationship map

Could <i>really</i> do with a cleanup, I'm not good at this...

For use in companies managing their internal documentation with Google Drive, who are having toruble keeping track of which document is 'live' and which one is 'draft'.

This script, hopefully, goes into each linked document, pulls out the links in there, marks down the relationship, and then does the whole thing again to the new links.

It's on my todo list to clean this up, this is not useable just yet.

Once you have an initial set yup use =UNIQUE() to get your nodes, and =FILTER(new!F2:G, not(ISBLANK(new!G2:G)), not(new!G2:G = "N/A")) to get your edges.

Use Gephi to visualize the data
