# Open Van Park

(Naming stuff is hard)

This is the very early stages of a repository of places you can park vans. Think
something like park4night, but open source and open data.

I plan on making a hugo site for this eventually (hence the hugo skeleton), but
for now, I want to start with collecting data. If you have places you can park
in a van, please consider submitting them.

## What to include

Eventually, places will probably be in something like 

```
content/<country>/<county>/<placename>.md
```

The markdown file should have a frontmatter that specifies things like the
longditude and latitude, height restrictions, whether overnight parking is
permitted etc. However, exactly what is stored is still undecided and open to
further discussion.

If you have places to submit, feel free to create the markdown files in the
format above. However, if you have a json or csv file, for now you can put them
in the data-to-import folder. Name it something sensible for now so we can use
what we need from it in the future.

Thanks in advance

## Privacy

Note that submissions will be tied to your github account. If you submit a bunch
of locations around your house, it may be possible to work out the area in which
you live.


