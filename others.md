
### Other Interests & Projects

These are not tightly related to my main line of interest, but stand to show my skills and achievements in other fields, giving me an insight into computer internals, programming languages and web technologies.

#### Bugout Dynamo Concept

One hobby project I am proud of is a [Dynamo-like distributed data store](https://attish.github.io/bugout-dynamo-concept/bugout-dynamo-concept.html) implemented entirely in browser, being as serverless as possible. Built around Bugout, a library that uses the distributed Bittorrent network to discover peers. This feasibility study implements a simple key-value store. Later plans would include redundancy, and building a simple note keeping app that is entirely serverless, where each participant helps keep all others' data secure.

#### Heapkeeper

Heapkeeper is a Python application that is a cross between a mailing list and a wiki. New entries are fetched via IMAP, and kept in a structure similar to an Obsidian vault. The entries can then be edited, displayed and searched via CLI, static and dynamic web interfaces. Started as a mailing list/wiki for a community of friends, later found use as a personal "second brain". Its main selling point was email access: whenever something crossed my mind, I just sent an email, something that was available in the often restricted university and work environments of the time. I worked on it with a friend, a professional developer. His goals was learning test-driven development, while I enjoyed a boost in my Python coding skills (previously I did all my coding in C), and learnt using tools like Git and Vim.

#### LapOS

As a kid, I was fascinated with computer internals. I had a book about Commodore 64 assembly programming, and I managed to chew my way through it, then came x86 assembly. Eventually, I was able to break out of the confines of Real Mode, and enjoyed roaming around in the full address space of a 486 in Protected Mode. But what I was never able to achieve as a kid was using paging, mapping logical memory addresses to physical ones, which allows for separation of address spaces and fine-grained control of memory access for processes. I managed to turn on paging, and decided to go on, entertaining the idea of improving this into a toy kernel. And now I was no longer limited to handwritten assembly: this new effort utilized the standard GNU C toolchain. I continue to go pack to this project every once in a while, and tinker a bit, enjoying its slow growth over the years. Now I am glad to announce that after a decade of tinkering, interrupts are in place, and keyboard input works, and some rudimentary multitasking is also taking shape. See more at [Lapos Git repository](https://github.com/attish/lapos/). ("Lap" means "page" in Hungarian, and "lapos" translates to "flat", as initially the goal was to get paging done in an identity mapping, a "flat" address space.)

#### AVR Game of Life

I enjoy not just coding but sometimes soldering as well. Once upon a time I made a handheld gadget implementation of Game of Life built around an AVR. Later plans would include extending it into a handheld game console for Snake (yes, that's a Nokia 3410 LCD display :') )



I invite you have a look at [my GitHub repos](https://github.com/attish/) to find out about my other projects and interests.
