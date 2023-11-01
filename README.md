### This is a demo project for students to write a basic README for their projects

Remember to check Github Awesome list of READMEs for more examples: [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)

# Introduction

*The Commodore 64, also known as the C64, is an 8-bit home computer introduced in January 1982 by Commodore International (first shown at the Consumer Electronics Show, January 7–10, 1982, in Las Vegas). It has been listed in the Guinness World Records as the highest-selling single computer model of all time, with independent estimates placing the number sold between 12.5 and 17 million units.*

(Source: [Wikipedia: https://en.wikipedia.org/wiki/Commodore_64](https://en.wikipedia.org/wiki/Commodore_64))

## Commodore 64 basic and sprite graphics

The Commodore 64 User's Guide has some helpful programming tutorials and code samples how to develop with C64. Or more like how to program with Commodore Basic language. Basic language was licensed from Microsoft. Following example is somewhat famous **Up, up, and away** sprite graphics demonstration, where C64 is programmed to display a moving hot air balloon across the TV screen or monitor.

![Alt text](images/balloon.png?raw=true "Balloon")

Early sprite design involves usually a grid paper drawings and planning. Then developer does binary arithmetics to get the related data values of the sprite. For example, the line number 200 and second data value 127 (64+32+16+8+4+2+1) there represents the first row and middle column of the sprite. The first column and first row value is zero because there are no any bits set.

This full code example clears screen and sets values to video memory from data lines (200-240). Then balloon sprite is moved across the screen with loop (line 70 goto).

![Alt text](images/basic_code.png?raw=true "Basic code for three balloons")

This [code example](https://github.com/t2946282/demoproject/blob/be9d359f1be4abd0433715bfd1881238b25569c6/threeballoons.txt) is same but it draws three sprites.

## License

This info page is using MIT license. Details: [https://github.com/t2946282/demoproject/blob/main/LICENSE](https://github.com/t2946282/demoproject/blob/main/LICENSE)

## Extra info

- [Sprite Graphics \(PDF\)](https://www.commodore.ca/manuals/c64_users_guide/c64-users_guide-06-sprite_graphics.pdf)
- [Programming Graphics on the Commodore 64, page 181 \(PDF\)](https://www.commodore.ca/manuals/c64_programmers_reference/c64-programmers_reference_guide-03-programming_graphics.pdf)
- [Nostalgia - C64 Manuals](https://codeincomplete.com/articles/c64-manual-nostalgia/)

## End note: Why do you need a proper readme file for student projects

You should build a university and hobby project portfolio to yourself which you can promote when applying to company oriented projects (3rd and 4th year), internships, summer jobs etc.

Current student project readme files in Github are often just something like “group 4” and that’s it. It does not really tell anything and is not very convincing when applying to somewhere. Essentially you should have at least 2-3 good projects in Github. Public and well documented projects you can promote.

In each project, you should have (in readme markdown file, i.e. the main page of Github project) something like:

- What was the project: For example the project name, primary idea and target, when, why
- Which technologies were used
- Which tools were used
- Who did what parts of the project (if groupwork)
- Application architecture, database schema, APIs, maybe ABIs, UI/UX plan, protocols
- Instructions how to deploy and use the project code
- Link to the server / service where the project is/was running
- Related presentation material(s): slides, images, videos about the project, posters, links or good quality images to basic project management and tool views (kanban stuff, Trello, Taiga, Jira, Github, Jenkins, CI/CD, IaC etc)
- Actual source codes: Commented code, code hierarchy if it is not obvious, using programming language and framework style guide (code entity identifiers like classes, variables etc named ok, syntax is clear overall…), avoid obsolete stuff etc. Code commits, pull requests, issues, merges etc


