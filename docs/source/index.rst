Loop Optimization: List Filters (In Progress)
-------------------------------

```eval_rst
.. contents:: Table of Contents
    :local:
```

### What are "List Filter" tags?
List filter tags return new lists with your desired output, without using foreaches! You can use `list.filter` to remove bad words from player messages, only get a list of players that are sneaking, and so many other things. You can even return a list with a completely different output from the original one using `listtag.parse`, like if you wanted to list all the online player's names, but we'll talk about that later. Some other cool things involve sorting lists by number/value and finding the highest/lowest number.

### Foreach exists... Why would I use this?
It's true that you can simply use a `foreach` command to achieve your desired output, but list filters exist for the purpose of filtering and parsing lists, meaning using these tags would be much faster and well-optimized. On the other hand, `foreach` is typically used for making a variety of changes to lists.

###The `listtag.filter` Tag
fuck this, im tired

### The One Liner Rabbit Hole
Now now... I know what you're thinking. "YO THIS IS SICK! I'M JUST GOING TO USE THESE TAGS FROM NOW ON, SCREW FOREACHES". **Abusing these tags can and will turn very messy.** Trust me, I know. The second it starts getting messy and/or confusing, you should probably use the `foreach` command instead.



### Related Technical Docs

If you want to read some more about list filters, here are a few technical guides you might consider...

#alphanumeric and numeric?
- [List.filter tag doc](https://meta.denizenscript.com/Docs/Tags/list.filter)
- [List.parse tag doc](https://meta.denizenscript.com/Docs/Tags/list.parse)
- [List.sort_by_number tag doc](https://meta.denizenscript.com/Docs/Tags/list.sort_by_number)
- [List.sort_by_value tag doc](https://meta.denizenscript.com/Docs/Tags/list.sort_by_value)
- [List.highest tag doc](https://meta.denizenscript.com/Docs/Tags/list.highest)
- [List.lowest tag doc](https://meta.denizenscript.com/Docs/Tags/list.lowest)
