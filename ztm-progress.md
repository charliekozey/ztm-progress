# ZTM Progress

## 1. [Full Guide](https://archive.ph/Gwofg)

### Month 1: The Big Picture + HTML + CSS

#### How to Learn

- [x] [Feynman Technique](https://archive.ph/AOdpk)  

*Takeaways: Learn -> turn it into a story -> explain as if to  a child -> fill your own gaps -> repeat*  

*Action: Develop explanations for what I learn, use them with students, refine* 

- [x] [Trunk Method](https://archive.ph/3jYJ3)

*Takeaways: Identify and emphasize the fundamentals, build intermediate concepts and details after*  

*Action: Explicitly incorporate fundamentals in lesson plans*  

- [x] [How to Learn Anything](https://archive.ph/wip/KmxKA)

*Takeaways: Identity, accountability, habit cues, GET SLEEP, learn by doing and teaching*  

*Action: Track sleep habit streak (bedtime routine by 10:45; in bed, lights out, sleep podcast playing by 11pm)*  

- [x] [Free Resources](https://zerotomastery.io/resources/) - bookmark

#### Web and Computing Fundamentals

- [x] [ZTM Crash Course Intro](https://www.youtube.com/watch?v=0kS3M8a6kP8&list=RDCMUCt7T2EvYBqvlxNU3fbE4Y7g&index=1) - first 40 minutes

*Takeaways:*
- Internet backbone diagram @ 13:00
- WILD diagram of the internet @ 16:30. Network of networks!
- ```traceroute```
- Three ways to increase website speed:
   1. Location of server
   2. How many trips (request/response)
   3. Size of files
- WWW !== The Internet
  - Internet is the network itself (infrastructure)
  - WWW is built on top of the internet, a collection of information that uses http as communication protocol (agreed-upon language, of sorts)
  - Analogy: Internet is bookstore, WWW is the collection of books in the store
- Old way (early 2000s)
  - JQuery
  - LAMP stack (Linux, MySQL, Apache, PHP)

*Action: Recommend this for Phase 1 students. Also try using balsamiq or similar for teaching, very cool!*

- [x] [Computer Networking Playlist](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBpuvPW0aHa7mKdn_k9SPKO)

Can't bring myself to finish this one, tbh. Not a fan of the delivery—overly casual and slow to get to the point—and also it has some ~*fun sexism*~ sprinkled throughout?? (Maybe I'll edit this critique one day to make it more constructive, but for now I'm salty.) Going to just look at the Wikipedia articles for each topic to get an overview. 

- Networks classifiable by size
    - LAN (Local Area Network): Same building, usually; wires and wireless
    - MAN (Metropolitan Area Network): Size of city, roughly; e.g. hospitals, colleges, that want to share data across buildings directly; copper wires, wifi, fiber-optic
    - WAN (Wide Area Network): Made of multiple MANs; > 30 mile span; e.g. phone company, Internet; uses satellite, fiber-optic, copper or telephone wires
- Network Interface Card / wireless network card
  - connects your motherboard with ethernet or wifi
- Protocols are rules for communication 
  - structured interaction analogy
  - my ELI5 example: barista
  
- [ ] [Crash Course: Computer Science](https://www.youtube.com/playlist?list=PLME-KWdxI8dcaHSzzRsNuOLXtM2Ep_C7a)

Fantastic resource. Something to model my teaching and material prep after, especially the animations. (I mean, it's PBS, so of course the production value is high.)

*Takeaways:*
- Computer science != computing
- "Computing" defined differently in different countries
- Fundamentally, computers are simple. They just do the simple thing MANY times, REALLY fast, through many layers of abstraction
- On/off switches (like faucet): two electrodes, one control wire
- mechanical relays --> triode vacuum tubes (1906) --> transistors (1947)
- Transistors use semiconductor as switch, same on/off flow concept
- !! Binary only switches between two extreme states "as far apart as possible": clearer signal, less disturbed by interference (as opposed to ternary, quinary)
- Boolean Algebra: only two values (TRUE, FALSE) and three fundamental operators (NOT, AND, OR)
- Logic gates
  - NOT places output before the transistor; when on, diverts flow to ground and away from output
  - AND: two inputs wired in series
  - OR: two inputs wired in parallel
  - XOR (exclusive or): if *only one* of the two is true
- ALU: Arithmetic and Logic Unit
  - Handles numeric computations
    - Built from logic gates (so many omg)
    - Arithmetic Unit
    - Handles numerical operations
    - Add, subtract, increment, etc
  - Logic Unit
    - Handles true/false
- Registers and RAM:
  - Building a 1-bit memory storage circuit
    - Circuits that loop back on themselves create indempotent gates
    - Self-referential OR is always 1
    - Self-referential AND is always 0
    - Put them together and you can store information and toggle 0/1
    - This is an AND/OR latch
    - Gated Latch: Improved AND/OR latch with data input wire and write-enable wire
  - Register
    - Small linear chunk of memory
    - A group of latches that work together to store multiple bits of information (e.g. 8-bit, 32-bit, etc)
- CPU
  - Phases of operation: fetch, decode, execute
  - Controlled by Control Unit (like orchestra conductor)
  - Fetch - decode - execute cycle moved along by clock
- Instructions
  - Every CPU has a list of instructions corresponding to a binary code (opcode)
  - Intel 4004 had 46; today's CPUs have thousands
  - The lists keep getting bigger bc need to be backwards compatible
- CPU Cache
  - RAM module lives outside CPU, connected by a bus (set of wires)
  - Transaction times add up
  - Problem addressed with CPU cache: a small (kb/mb) amount of memory right on CPU
  - RAM sends a chunk of data at a time rather than one at a time, saves time
  - Dirty bit: marks that the cache has been modified, so it writes data back to RAM before loading new data
  - Cache hit/cache miss
  - Also used as scratch space to store intermediate calculations
  - Can use instruction pipeline *parallelization* to save time (washer/dryer analogy)
  - To prevent conflicts (e.g. fetch something that's about to be changed on execution), CPUs use lookaheads for data dependencies and out-of order execution
  - Lots more cool things
  - Speed measured in flops: FLoating point math OPerations
- Assembly languages
  - have direct 1-to-1 mapping to machine instructions
    - Assembler: a program written in binary that translates assembly language e.g. "LOAD_A 14" to binary operation
    - Compiler: Translates source code into assembly or machine instructions
    - 1st compiler invented by Grace Hopper in 1952
  
   
 
- [ ] [Map of Computer Science](https://archive.ph/qFMgg)
- [ ] [Real Web Developer Roadmap](https://archive.ph/jdzZs)
- [ ] [Harvard CS50](https://www.youtube.com/watch?v=y62zj9ozPOM&list=PLhQjrBD2T3828ZVcVzEIhsHVgjANGZveu)
- [x] [Command Line Crash Course](https://archive.ph/Acwd7)  
*Takeaways:* ```pushd``` *and* ```popd``` *for stack navigation*
- [ ] [How to Build a Website](https://www.youtube.com/watch?v=tq7dqdHCc7U&list=PLoYCgNOIyGAB_8_iq1cL8MVeun7cB6eNc)

#### Front End Basics: HTML and CSS
- [ ] [How HTML + CSS Fit Together](https://www.youtube.com/watch?v=0kS3M8a6kP8&t=2487&list=RDCMUCt7T2EvYBqvlxNU3fbE4Y7g&index=2&ab_channel=ZeroToMastery) - 0:41:00 - 3:06:00
- [ ] [Bootstrap 5 Tutorial](https://www.youtube.com/watch?v=rQryOSyfXmI&list=PLl1gkwYU90QlfX9oIJvC4JJKaucei7Hx8&t=0s)
- [ ] [Bootstrap 5 Docs](https://getbootstrap.com/docs)
- [ ] [Flexbox and CSS](https://www.youtube.com/watch?v=0kS3M8a6kP8&t=11165&list=RDCMUCt7T2EvYBqvlxNU3fbE4Y7g&index=2&ab_channel=ZeroToMastery) - 03:06:00 to end
- [ ] [Flexbox Practice](https://flexiting.com/playground/)
- [ ] [Flexbox Froggy](https://flexboxfroggy.com/)
- [ ] [Grid Garden](http://cssgridgarden.com/)
- [ ] [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [ ] [Learn CSS Grid](https://learncssgrid.com/)
- [ ] Build your own website layout from scratch
- [ ] [Bootstrap Themes](https://startbootstrap.com/themes) - understand how to use
- [ ] [Templates](https://html5up.net/) - understand how to use
- [ ] [freeCodeCamp HTML and Responsive CSS](https://www.freecodecamp.org/learn/2022/responsive-web-design) - skim some courses

## 2. [Junior to Senior](https://archive.ph/0DGwN)

## 3. [Interview, Job, Raise](https://archive.ph/4Okzz)
