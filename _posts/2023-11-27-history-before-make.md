

Before I apply for a job, I like to know what I'm supposed to accomplish before I consider joining the project. My first question to the hiring team is often "what do you expect me to accomplish in three to six months?" If I like their answer, I might accept an offer. Otherwise I keep looking. Three to six months of my time is a precious investment, and I want to be sure that when I look back, that time was well spent. 

On the other side of the table, when I'm hiring for my team, I've found the best predictor of a candidate's future success is their past success. How did they spend their last six months? What did they accomplish in the past six years? Where is their trajectory headed? As [[John Ousterhout]] says: [[Hire for Slope]]. The quicker they reached the clouds, the sooner they'll reach the stratosphere.

So I say: write your history before you make it. Write your CV as you want it to be, then go and make it be.

This philosophy applies just as well in system design: describe the system as you want it to be, then carry out the actions required to deliver that result. [[TDD]] epitomises this philosophy. First write your tests (your success metrics), then write the code to make the tests pass. SQL is another example. We don’t tell our databases *how* to get the data we’re looking for. We simply declare what we would like to see and, poof! The results materialize. Similarly, in #event-driven design we issue a series of commands describing our desired behaviour. Once processed, the system produces a stream of events capturing what actually happened (i.e: a history). This is also a common pattern in distributed systems and database internals, e.g. a [[Write-ahead Log (WAL)]]. All these systems share one thing in common: we describe our end state and then it figures out how to get there. In other words: We write our history before making it.

Thinking about systems this way helps us [[Regret Minimisation Strategy|minimise regret]]. It forces us to be precise and purposeful about the systems we wish build. Careers are no different. Thinking about a career as something to be designed for and “built”, forces us to be precise and purposeful in our approach to building our career—just as we would b aim to be precise and purposeful when building a system. 

[[Hal Abelson]] famously said in his [[Hal Abelson - MIT Oral History|Oral History at MIT]] (paraphrased): “\[in the 1960s and 70’s] we used to spend a few hours discussing the future we wished to build, and then spend years making that future a reality. Nowadays it’s the other way round: people spend years talking about what they’re going to do, and very little time actually accomplishing it!”

Figure out what you want to accomplish, then put your head down until you accomplish it. 

Where you place your foot next will dictate the steps you take afterwards. When you look back at your footsteps, will you be happy with the path you took?

Pay attention to the legacy you want to create, and then go forth and create it.

Write your history, then go make it. 

--Abdullah Ariff