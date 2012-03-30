# Interactive art is not just technology

  Thank you for attending this talk, its a big leap of faith for something with almost no description on Friday night.
  If all goes according to plan, you will be inspired by awesome interactive art that will blow your minds and ask 'how did they do that', then I will try and convince everyone in this room that they can do ANYTHING they can imagine, and if you don't think I'm a crackpot after that is over, we will get to the meat of the talk where I describe a useful framework that's helped me create art and finish off with some basic training in the tools common to that framework.

  The talk should about 45 minutes, leaving time to discuss and share your own ideas and experiences. Please write down any thoughts during it all! Also, COOKIES!

## WHOAH (Keanu)
  * Bike-In movie
  * Everything from art hack day
  * EyeWriter
  * Jer Thorpe
  * Alicia Gibb
  * Encountering Data
  * Island Labs
  * COOL SHIT RITE?
  
  All the art you just saw was built with a mix of experimentation and collaboration. Just a quick overview of what phases are involved in any creative endeavor:

### Experimental - What if we add X and Y? or subtract Z from 3?
  X & Y can be anything, like rocketskates and labradours.

  This is meaningful because the end goal is learning. As long as you learned something, you win!
  This is useful because it can spawn other ideas and helps develop intuition.
  And, the best part, is when something actually does happen, it is the funnest thing in the world!
  This is also a huge timesink until you develop that intuition.

### Conceptual - Wouldn't it be cool if...
  Start with an idea of you want to happen, then figure out how to make it happen
  Here is where I go a little crazy. I am going to ask you to finish a sentence with the wildest, best ideas you can think of, and convince everyone that you can make it happen. Let's start small:

  Wouldn't it be cool if ...

  * 'Grass could talk?'
  * 'ANOTHER EXAMPLE THAT ACTUALLY EXISTS'
  * 'ANOTHER EXAMPLE'
  * 'ANOTHER EXAMPLE THAT ACTUALLY EXISTS'

  All of these things can be made. In fact some of the ones in that list already exist (WHOOSH, REVEAL)

  I know someone in this room is thinking about the limitations, but I firmly believe EVERYTHING on this board is possible. In fact, I prepared a small list of the most common expressed limitations and how to overcome them.
    		
### 'Limitations'
  Listed in increasing difficulty to overcome

  1. expertise
  2. money
  3. time
  4. laws of physics / natural law


#### expertise
    
  Expertise is just knowledge + experience. Experience you will get by building something, but where do you get knowledge? (*Looks around campus*) Oh I don't know.


  organizations and the communities built around them exist to share knowledge:
  
  - WikiMedia Foundation shares all sorts of knowledge
  - Creative Commons shares creative knowledge
  - Free/Open Source Software shares coding knowledge
  - OpenHardware Consortium shares hardware knowledge


  websites exist to make it easier to share experience:
  
  + instructables for project build logs
  + geekstreams for live builds
  + wikipedia for research (see simple english language too!)
  + kahn acadamy / MitX / courseware or opencourseware


  books!

  - yes, books. __orielly__ if you are engineering something, __phaidon__ if you are artineering something.


#### money
  Dream big. This used to be tough. Its gotten much, much easier. Try out all options to find what works best for you and your project.

  __kickstarter__ deserves its own category:

  * double fine studios, illuminato, etc, etc, etc...
  * donated more money than the NEA!


  __grants__ and __residencies__ are everywhere, if you are better when explaining face to face, this is the way to go.
    ITP Camp, eyebeam residencies, sparkfun/seedstudio sponsered trips to china!

#### time
  Time is directly related to motivation. The reason time is considered hard is more often than not because people assume they HAVE to do some things that aren't actually necessary. I have found myself infinitely more productive just by forcing myself into an environment that fosters creativity. I literally made more time without taking away from anything else I do in my life.

##### HACKERSPACES
  
  Listed from most awesome to slightly less awesome, or distance if you want to be PC

  * _Island Labs
  * NYC Resistor
  * Alpha One Labs
  * MetaLab

##### Shortcuts  
	Crowdsourcing involves distributing your task to a network of people.
  Things like Amazons mechanical turk is neat as hell, inspiring art pieces just by its existence.

	_supplements_
    We are adults here, so I will mention these. Bottom line is, if you need to do a ton of rote work, and don't mind feeling like you have blinders on or losing the ability to think laterally, these can help. The only 'energy drink' I can wholeheartedly recommend is club mate. :)

    A much better alternative to drugs is enlisting a group of friends and strangers to, say, solder 625 LEDs. This alternative a) helps make friends, b) is more fun and c) is more motivating. Just order some pizza, beer, and maybe some club mate!

##### laws of physics
  Yes, you can break the laws of physics, if you are even slightly clever. I will just throw some examples up because I want to move fast, but know that being able to control your art pieces environment will let you seem like you are bending and breaking fundamental rules of the universe. It is trippy and almost always makes everyone smile :)

	toby shaffman, floating sphere
	any magic trick


### Methods
  There are a bunch of different methods to creating art. 
    ( Ask audience here for some methods? List others? Distracting? )

  Most of my art involves immediate feedback. The conceptual framework that helps me focus on the high-level goal while making headway during the build process is a sort of chain. In this chain, physical or virtual sources of data are linked to physical or virtual sinks. There is always some manipulation of the stream of data in between the sources and sinks. Changing how you manipulate the data helps to define a particular feeling. Remember that last point.

  This chain is present in many software programs like Max/MSP/Jitter, Buzz, PureData, etc.

  A helpful concept taught by Adam ___ at HarvestWorks, is 'everything is just data'. Data, as we define it, will just be a number. Later we can look at more high-level representations of data, so if you are thinking about that, awesome, but hold those thoughts (or write them down) for now.

  So if data is just a number, how does that help us in creating art that is interactive? Well, there are a million ways to map actions or events to data, as there are a million ways to tap into that data and react with other actions and events. By the way, I am just going to drop 'physical and virtual' prefixes from now on. If you care to talk about where the line blurs near the edges of those realms, drop me a line after the talk.

  Sources
    - go through examples we've seen
      identify data source
               data sink

      bike-in movie
        source: ??? bike
        sink: ??? movie

      another example

      scratchml
        source: kinda easy, record table, a dj scratching
        sink: ??? no sink!

        a sink: canv.as (4chan), incorporated the data

        floating sphere?
          this is where my method breaks down
          if i wanted to force the chain method with toby's piece, i'd say
            harumph 'clearly, the source is the sphere, and the sink is the people trying to go the bathroom'

  - inputs
  		- since data is all encompasing, it isn't useful to think about on its own
  			- but its super useful to know that everything is just data
  	- 1 or more people manipulating controls
  	- gathering generated data (twitter)
  		- ex: berke's screensaver
  		- ex: the concert @ encountering data

  - outputs
  		- 

Terms
  - Procedural art
    algorithmically generated sights, sounds, and tastes
  - Time-Based media
  	any media that changes over time. you may or may not intend to make time-based media (see statue of liberty)
  - Data
    just a number
  - Map
    to take something and represent it in a reproducable, defined manner

Tools
  - Physical
    - Arduino
    - Raspberry Pi
      - more traditional computers/laptops
      - smartphones

  - Virtual
    - Processing
    - Max/MSP
    - Wekinator
      - Alchemy
      - Flex

  - Protocols
    - OSC, MIDI, websockets

  - Spaces
    - physical
      gallery (319 scholes)
      event (I-Con)
      public (toby's installation in apartment building)
      museum (MoMA)
    - virtual
      (_GALERIES HERE_)
    - transcendant 
      mit touchpoints
