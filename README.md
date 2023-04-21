## This is a demo project for students to write a basic README for their projects

Remember to check Githun Awesome list of README examples: [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)

## Introduction

*The Commodore 64, also known as the C64, is an 8-bit home computer introduced in January 1982 by Commodore International (first shown at the Consumer Electronics Show, January 7–10, 1982, in Las Vegas). It has been listed in the Guinness World Records as the highest-selling single computer model of all time, with independent estimates placing the number sold between 12.5 and 17 million units.*

(Source: [Wikipedia: https://en.wikipedia.org/wiki/Commodore_64](https://en.wikipedia.org/wiki/Commodore_64))

## Commodore 64 basic and sprite graphics

The Commodore 64 User's Guide has some helpful programming tutorials and code samples how to develope with C64 and how to program with Commodore Basic language. Basic language was licensed from Microsoft. Following example is somewhat famous up, up, and away sprite graphics demonstration, where C64 is programmed to display moving hot air balloon on the TV screen or monitor.

Sprite design involved usually a grid paper drawing and planning. Then developer does binary arithmetics to get the related data values of the sprite. For example, the line number 200 and second data value 127 (64+32+16+8+4+2+1) there represents the first row and middle column of the sprite. The first columnt and first row value is zero because there are no any bits set.

![Alt text](images/balloon.png?raw=true "Balloon")

This code clears screen and sets values to video memory from data lines. When balloon sprite is moved across the screen with loop (line 70 goto)

![Alt text](images/basic_code.png?raw=true "Basic code for three balloons")


## License

This info page is using MIT license. Details: [https://github.com/t2946282/demoproject/blob/main/LICENSE](https://github.com/t2946282/demoproject/blob/main/LICENSE)

## Extra info

- [Sprite Graphics \(PDF\)](https://www.commodore.ca/manuals/c64_users_guide/c64-users_guide-06-sprite_graphics.pdf)
- [Programming Graphics on the Commodore 64, page 181 \(PDF\)](https://www.commodore.ca/manuals/c64_programmers_reference/c64-programmers_reference_guide-03-programming_graphics.pdf)
- [Nostalgia - C64 Manuals](https://codeincomplete.com/articles/c64-manual-nostalgia/)


