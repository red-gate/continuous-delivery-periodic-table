# Contribute to the Elements
Hello continuous deliverers! This is a usefully short guide on how to contribute to this list / visualisation of the elements of Continuous Delivery.


## Contributor license agreement
By submitting code you agree to the [LICENSE](/license.md) of this repository.

##The goal is to create a sensible Periodic Table of Continuous Delivery, not an endless list of terms and concepts.
This list can't be infinite! We still want it to build a sensible-looking periodic table, with groups, symbols and further reading. To that end, look for terms which can be pruned as well as what's missing.

## Everyone is welcome to suggest new / alternative elements (and associated further reading) or groups to the list.
It's true - you're all welcome to suggest better elements and references to the list. And by free, we mean free, really free.

## Steps to add or update an element

1. Pick the term you think should be pruned, altered or added, and match it to a category.
2. Decide how "heavy" the term is (i.e. the more opaque a term / the more you need to know about CD to understand it, the "heavier" it is), relative to the other elements in that category
3. Place the element in the list (ordered according to "weight", and list 
	1. The elemental symbol
	2. The element name 
	3. A short (~1 para) explanation of the term 
	4. A link to further reading.

### Guidelines

1. Unlike some projects, we prefer multiple small commits rather than one large change in a pull request - it's fine to have one pull request, but please make sure your title reflects what you've changed.
2. Use our standard for formatting the .md file. Check it out: [Formatting](#formatting)
3. Please try to order terms according to jargon "weight" *within each category* (i.e. the more opaque a term / the more you need to know about CD to understand it, the "heavier" it is).


### Formatting
+ All lists are ```.md``` files. Try to learn Github's Markdown syntax. It's simple!
+ The list of [elements](/elements.md) is currently just a flat list (See below). It's messy, so it'll need refactoring sooner rather than later. In the meantime, if you can suggest a better way to structure it, update the [TODO](/TODO.md) with the refactoring and raise an issue!

Current example from Infrastructure.md:
```
[...]
- Os		Operating system - [Short description] - [URL to further reading]
- V		Virtualization - [Short description] - [URL to further reading]
- Eip	External integration points - [Short description] - [URL to further reading]
- Cl		Cloud - [Short description] - [URL to further reading]

```

And that's it! 
