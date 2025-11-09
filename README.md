# MCP Guideline Snippet (Home CLAUDE.md)

[![Claude Code](https://img.shields.io/badge/Claude-Code-8A2BE2?style=for-the-badge&logo=anthropic)](https://claude.ai/claude-code)
[![Claude Code Projects](https://img.shields.io/badge/Claude_Code-Projects-8A2BE2?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Claude-Code-Repos-Index)
[![Master Index](https://img.shields.io/badge/Master-Index-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Github-Master-Index)

[![View Snippet](https://img.shields.io/badge/View-Snippet-blue?style=for-the-badge&logo=markdown)](snippet.md)

The snippet (snippet.md) is an attempt to add a little determinative guidance to Claude Code on how to use MCPs that it encounters across environments (ie, which are installed with the user scope).

There are some MCPs, I have found, which require a little bit of "explaining" but which don't have a defined env variable to provide some needed context. 

In other cases: there is a "conflict" between an MCP and an internal Claude tool: take Firebase. Claude its own fetch mechanism. If you have Firebase available across the system, is Claude to understand that it should *always* be preferred over its own retrieval or only in certain cases?

The idea behind this snippet is to try to clear up taht ambiguity in order to provide for more predictable invoking of MCP servers. 

Additional notes:

As with most of the things I try to make AI systems as useful and performant as possible: this is an experiment in progress. Also: the pace of AI development is such that what are user hacks one day (like this) often become part of the system the next and thus these ideas are of very short lived utility and relevance.

Either way: feel free to adadpt to your MCPs and try on your own instance!

---

To view an index of my Claude Code related projects, [click here](https://github.com/danielrosehill/Claude-Code-Repos-Index).