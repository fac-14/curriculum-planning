# Curriculum Planning - Monday 17/09/2018

Notes by Jessie

### Contents

* Week 2 - Testing
* Week 3 - API Week
* Week 4 - Node Week 1
* Week 5 - Node Week 2	

## Week 2 - Testing

### Intro to NPM

No comments

When talking about week 3 this came up.
Introduce gitignore here?

### Intro to testing and TDD

Michael: Suggestion, WS says “if you finish early, look at code coverage” - would supertest be better? Needed in test

Natalie: Didn’t get point of TDD in workshop. Don’t have idea of what to improve put would be good to understand more the point of TDD.

Michael: Suggesting Supertest as an ‘if you finish’ - not compulsory. Not sure on solution, but should be introduced to tests relevant to the project. 

Eve: Agrees with Nathalie. Didn’t feel it was useful at the time, only realised at Week 8 how crucial it was. Didn’t believe it was use 

Jessie: Week 2 was a lot of DOM manipulation, not supertest GET/POST, so agree with michael that relevant testing is good but not supertest in week 2

Nathalie: Feels like TDD is difference between coding cowboy and a professional, potentially introduce in precourse material? You should come into course understanding need for testing. 

Michael: We had some good speakers on testing that got that across well. It would be good to find ways to make testing do-able quicker. 

Dom: codewars gives you some idea of testing. Concern with pre-course is there is already a lot of content, may not get done. 

Armand: Maybe use Kata as example, something familiar that helps demystify TDD

Michael: Agree, great idea. Would be good for mentors in that week to include

Nathalie: Would it be useful to give examples of what tests to write? A suite that is a good starting point.

Dom: TDD Roman numerals, going back granularly, would take too long. Useful to know how to scope tests for challenge at hand. 

Michael: About code along (next item), but it was too abstract 

Joe: repetition was useful to learn format, but very samey. Maybe taking some of that time to introduce a kata would improve it

Eve: We’re encouraged to do unit testing, which is related to functional programming, I feel like introducing functional programming alongside testing would be useful in the week’s introduction. To give us some programming context. 

Michael: Could that come in a research topic? I’m not sure how useful the research topics were

Emma: technical spikes, what are they?

Jessie: Take out of curriculum technical spikes if it isn’t used as a research topic.

Dom: Is tape the best thing to teach?

Armand: I agree, course tries to be cutting edge, it seems weird to use archaic testing framework. I think Jest or whatever would be great

Michael: If we agree to replace tape, we must implement across every workshop in the whole 8 weeks. Are we willing as a group to do that?

Nathalie: One workshop randomly uses Qunit, which was a bit jarring. Can we align it with the rest of the course?

Joe: Good action point on this - depends on whether we decide on any other significant overhauls. If we think that would be valuable and want to prioritise, I think it would be good.

Dom: Potentially create a branch where we slowly implement Jest, and bring in as and when we complete

Armand: Agree, tape and Jest are very similar

Michael: No point seeing it as baby step, this is a big thing, we should do it or not do it

Nathalie: I think it’s really important, we should try and do it

### Roman Numeral Code Along

Nathalie: I would prefer the workshop to be more Q&A - not doing all the numbers, thinking how do we start, asking us what next step is.

Michael: Very much agree, whoever runs WS should do that as far as poss, its very passive to sit there typing

Joe: It felt very rushed, for us as well as the mentors. Can we look at how to make it shorter in order to allow questions / Q&A?

Nathalie: We had that guy Dan come in for a surprise talk which was partly why it felt rushed

Art: I would have benefited more from Q&A format, felt I was playing catch up

Nathalie: Testing is really good one for letting students figure out how to write the code, taking them on a journey.

Michael: Agree, don’t see why it had to be rushed, learning tests more important than a working Roman Numeral function.

Dom: Was bad that the speaker also did the Roman Numeral challenge, should be coordination to avoid that

Michael: doing 5 minute timer!


### Morning Challenge - Dom manipulation

No comments

### Pure Functions Workshop

Eve: This is the one where they should have introduced Functional Programming. Give context on the wider world of programming and context. How OOP and FP are somewhat opposing ideas.

Nathalie: Good to bring up here that as projects grow, tests can be useful

### Introducing Project

Joe: This project, we either need comments in the code. It’s useful to have starting code, but we need more notes for mentors to explain code. We spent 

Nathalie: Comment says it needs an event listener - You Don’t!!

Eve: Mentors should do walkthrough of starting code with everyone - general consensus

Armand: Wow, bad memories. I was replicating function that was already in the code. It needs fixing.

Michael: We were told we needed to test pure functions, but not if it was a pure function. They introduced stuff that was not mentionned previously

### Research Topics: 

Technical Spikes was instead Callback functions

Michael: maybe more than 4 people should be introduced to this…

Eve: Callbacks, don’t see the point of doing it as research topic intro. We should learn by doing. OOP vs FP as research topic instead? Unhelpful to half learn callbacks then.

### Event Loop video

Armand: Some people felt it wasn’t clear. Speaker took a lot of things for granted. Some people it didn’t help at all

Michael: If anyone planning this week, look at thing I made about callbacks. The callback bake off. People need a proper intro to callbacks before traffic lights, otherwise the challenge becomes a nightmare.

Emma: Michael can be a speaker!

Nathalie: Question, I’m in the camp didn’t internalise that, should we replace video with callbacks? 

Michael: I found it useful, not sure everyone did. Maybe shouldn’t be first intro.

### Morning Challenge - Traffic Light Callbacks

Dom: I had used callbacks before, but the set timeout really added to complexity and confusion. Even when familiar with callbacks, it’s hard to follow along.

Nathalie: For me, the asynchronicity of callbacks is hard. Having something that captured the element of ‘send kids to the shop wait for them to come back’ would be good

Armand: I think challenge should not go, its good and quite fun

Art: Not best intro to callbacks, not necessarily entry level

Sangita: I found this the right level of challenge, I couldn’t do it alone at home, but in this environment its possible

Armand: I think as a challenge it’s a good challenge, but a prior introduction would be super useful or pushing it back in the course

Joe: It seems like this week needs quite a bit of rejigging. Potentially doing it as a code along / Q&A, we completed it but didn’t get that much out of it. I think there’s some validity to the WS, but as a morning challenge you can forget about it, which is not what you want for callbacks

Michael: Mentors were quite discouraging, refused to help. You need to recognise groups who are really struggling and enable them to get something out of it 

Monika: I didn’t know what to even ask with this challenge

Michael: Traffic lights didn’t explain why callbacks are useful and necessary. Both this challenge and event loop need to be brought down to a more understandable level

Joe: It sounds like we need a better introduction to the theory of callbacks, the traffic light is useful for repetition of callback code 

### Projects

Joe: Make sure speaker doesn’t do Roman Numerals

### General Comments?

Nathalie: Question: why are we building a todo app this week?

Michael: To write pure functions and test them. I think it’s important to emphasise testing and support people on that.

Armand: I don’t feel like I fully learnt or implemented stuff until a couple of weeks after, which seems to often be the case. 

Michael: I agree, although project is to ‘use TDD to build a todo app’ - we should have skills to do that project

Nathalie: Could we guide people through TDD aspect of project? Guide them through why we’re doing this etc

Michael: I agree, If everyone struggles with an aspect of a project, we should stop, deal with it and move on. 

Emma: Could it be as simple as adding a couple of example tests in the project?

Dom: Maybe even comments in the test file “you should be testing these things”



## Week 3 - API Week

RE SGC - reminder that mentors should reiterate pair programming methods and encourage their use. 

### Introductory Workshop

Joe: Really Quick - reminder to actually show the outcomes as its nice to set context for the week

Michael: As a teacher, you would get a FAIL for not telling students what they’re expected to learn

### XHR Workshop

Nathalie: OMG - so much reading, reading, reading, until noon. Can we make this more interactive??

Eve: We’re not here to read in silence. We need to know this stuff, but not best format?

Michael: it could be research, but its just 2 hours of reading.

Nathalie: There is a way to make this engaging, request and response, I feel this could be more effectively taught. Its give and take, back and forth, two mentors could act this out.

Emma: This whole thing here, text block, is just explaining the parts of the XHR. Could be done in 10 mins in presentation

Michael: I feel like this came up at the time, but people have different ways of learning, some like reading, others don’t, we should mix it up.

Nathalie: There’s a lot of new terminology. Could we extract key things that everyone in the room has heard spoken out loud by the end of the exercise

Dom: I’m repeating, but mentors could present key points and the record is there for further reading

Art: as someone who does learn by reading block text in the quiet, it would be good to learn by mixing it up with shorter text, discussion, maybe a video.

Michael: There are some good interactive elements, but other places it goes too long without interaction

Monika: It was helpful for me to be sent stuff to read in the morning, like in DB week, it was the easiest week for me to understand from doing pre-reading in my own space. I might like to do this in other weeks?

Nathalie: Next WS works with actual XHR, can we move stuff around? Maybe stuff in there is good, just needs to be done in different order

### Afternoon Workshop

Nathalie: I don’t remember this at all. Can we bake this into the other stuff? We’re jumping around a lot.

Michael: We all got APIs, we didn’t struggle. Maybe this is one where we don’t need to reinvent the wheel

Joe: In places it could be presented better, mentors tend to shy from presenting and get people to read the readme. But they could cut through stuff faster by summarising. Mentors should add ‘sazzle’?!

Dom: Agree this week was good on the whole. Only comment was it was hard to find right URL endpoint for github.

### Flexbox Froggy

Armand: Should we talk about flexbox vs grid?

Michael: Only latest browsers use grid, not widespread, you can do the same with both. 

Michael: Ultimately we got exposure to both, but doing flexbox first is logical and good. 

### Flexbox Dice Challenge

No comments

### Software Architecture Workshop

Joe: Nice that it wasn’t too prescriptive, just got us to talk and discuss. Maybe a lookahead to what your future projects would look like / example file structures would be a nice addition.

### Software Design Workshop

Nathalie: This one, there was a mention of first-class object, we had to ask about this, the structure was confusing. Mentors could go through this more clearly.

Dom: Agree, it was laid out strangely, some of us did the wrong exercise.

Michael: Too much reading here, loads of code blocks with one line explanations. A repl/sandbox would be a lot more helpful

Nathalie: Bullet point ”more coming soon” - can this go?!

Michael: In a massive workshop that was a time stretch, didn’t feel good to have ‘more coming soon’ at the end!

### Introduce Projects

Dom: Cors reqests in the readme, they come in a lot later but could be mentionned?

Nathalie: Was it week 3 that had Qunit mentionned? (people think yes, one of the long WS) Can we get rid of that. 

Emma: config.env for API keys, not made clear enough / emphasised.

Dom: Wasn’t sure if we needed Node to conceal API keys. 

Emma: apparently you make a config.js file and put that in the gitignore.

Michael: API workshop with Qunit, needs to change

Nathalie: Maybe in week 2 when we implement npm, make a bigger deal of gitignore (we put our node modules on github…)

### Waterfall Morning Challenge

Joe: let’s read through SGC. ‘no one completed it’ If it’s not possible for you to achieve a challenge, it’s not a challenge. It stressed people out. Mentors kept asking if we’d finished when we hadn’t even finished reading…

Emma: We should get rid of it and replace it with something else. No one in previous cohorts has said they used it/got anything out of it. 

Dom: We nearly got it, but weren’t sure we were on right path

Michael: Only a tiny handful were close. It’s too early for it as its very offputting.

Emily: First challenge where looking at solution didn’t make me understand it any more. Not good.

Michael: Why is this still here? Who thinks this is still important and why? There is surely something more supportive that could go in there?

Sangita: The recursion is what made it so difficult

Nathalie: Apparently was done as a workshop for FAC9, maybe it was a walkthrough? Then made it in as a challenge?

Michael: This is steering people towards chaining callbacks, which is important for projects, but this doesn’t necessarily teach it in the nice why.

Emma: Can we ask previous cohorts what they got out of it?

Eve: They all remember it, its infamous, no real positives I’ve heard. 

Joe: question is how can we chain callbacks as we’re chaining API calls in project. Would it be spoon feeding to walk through that?

Michael: yes, a challenge around that would be good.

Joe: The promises workshop with pokemon API, might be nice to mirror that with chaining callbacks - the non promise based solution. General consensus!


## Week 4 - Node Week 1

### Node intro workshop

No comments

### Node Girls workshop - 1 of 2

Nathalie: That’s the one where at the end you delete everything. Can we change that?

Eve: WTF, doing the exact same thing 3 times over pissed me off. 

Joe: It also meant that a lot of people didn’t get to the POST bit, which is really useful. Kate & I did because we didn’t delete everything… WS is good, deletion is unecessary.

Eve: My pair decided deleting and writing again was pointless, we didn’t delete.

General consensus deletion is pointless and post more valuable.

### ES6 Morning Challenge

Monika: 96% of browsers now accept ES6 - why don’t we start course with ES6?

Michael: We write in ES5 for front end for backwards compatability.

Dom: is Babel simple enough to use for both front end and back end?

Eve: Should we now be using ES6 on front end? Everywhere supports it.

Jessie: Not about syntax as much as it about understanding callbacks, the need for promises, asynchronicity

### Node Girls workshop - 2 of 2

See above

### Introduce Project inc Design Challenge

Dom: why bold the unmatched portion? Not very common to actually do that

Dom: Also HTML5 Datalist warning - does the job but is quite limiting in terms of accessibility and styling? Advise people not to do that?

Michael: I actually think unmatched portion makes sense and is used. 

Emma: for autocomplete, maybe add useful links for data sources?

Dom: yeah, make it clear you don’t really want to use API calls, should give some example data sources. 

### Research Afternoon

No comments

### Modularisation Morning Challenge

Nathalie: Spelling error in the readme - “super simple started kid”

Dom: Do a PR?

Michael: There is an issue with this challenge - check out notes in spreadsheet as it uses a different server set up to what we had used previously.

Dom: Whoever does this week, maybe do a file structre set up thing

### General Project Feedback

Nathalie: This is where they started getting on our backs about commit messages / commit sharing, could this be done better?

Michael: can we introduce earlier? Make it a challenge / criteria within the project?

Armand: Yes, give clear expectations

Nathalie: Parissa brought up using issues as to do list for own use. This could be introduced better / earlier. 

Dom: Overall, as learning outcome/challenge - act as if you’re in a company, use issues, commits should relate to issues, try to write descriptive commit messages

Michael: we suddenly got pulled up on this, which was the problem. 

Emma: How about if we have a md file somewhere with Git best practices, which is brought up each project. 

Nathalie: Parissa did go through slides talking about issues. Only made the connection at the end that we were really relevant to the proejct

Emma: yeah, an md file that you can refer back to would be good

Michael: They challenged us, but maybe in the wrong way. They should set expectation that they will be looking at these things to help us.

Nathalie: Only once I got introduced into git in my team that I understood that FAC was run through git issues etc. Maybe add a ‘btw’ - this is how FAC works

Joe: That’s really true. Going back to what michael said earlier, raising issues on projects earlier on could be really good, where we’re exploring github and integrating that would be interesting

Nathalie: There aren’t many issues on coursebook week 1 as people weren’t familiar

Emily: Hard to raise issue retrospectively as you don’t feel the same, but didn’t feel comfortable at the time. 

Michael: Maybe after first code review in week 1, we are taught to add issues to coursebook.

## Week 5 - Node Week 2

### Workshop on TDD Node Server

No comments

### Workshop on error handling

Nathalie: This was very random and covered a lot, we weren’t sure which one to use having done it

Dom: Came out like, that was great, but which one should I use

Eve: most people didn’t finish so only did 1 or 2 types of error handling

Michael: error first callbacks are most important here, not try catch etc

### Node shell workshop

Dom: Not sure on usefulness of this challenge? Haven’t used it since

Michael: A lot of job ads reference shell scripting. Martin is the only one that loves it, has come up with a lot of applications. Could there be more guidance on usefulness/applications?

Nathalie: Could the workshop build a build-a-folder-structure script? This helps you understand you can read files but not other applications

Eve: Even though we didn’t use the stuff again, it was good for basic understanding of command line and how a computer works. One problem we will have when we get a job is we don’t have that comp sci background. This is useful for those reasons, even if we don’t realise it.

Michael: Completely agree, but shouldn’t be hung up on lack of CS background 

### Introduce Projects

Michael: Tom’s talk on Nock should be introduced prior to this. Its an API call mocker, prevents you overusing your API key. Like supertest for API responses. 

Research Topics

Michael: This was quite a good one, all very practical with real applications. A lot of us wrote guides & cheatsheets for this, we should centralise these resources. 

Emma: Dwyl have a good guide on Travis

### Morning Challenge: Build Request Module

No comments

### Introduction to Linters

Eve: Has to give you an idea how to disable certain damn rules that don’t help you. Hard to find in docs, really should be there.

Nathalie: AirBnb didn’t work great as an example, bad rules

Armand: Include Ivan’s thing

Dom: needs a longer, more detailed, hand-holdy guide to using linters so we get off on right foot. 

Nathalie: We’re removing ESLint from installation list so this is first introduction

Dom/Michael: use Ivan’s guide - prettier etc, not airbnb

### Other comments

Dom: In earlier weeks we need an accessible guide to escaping Vim…

Eve: You should be able to set the default text editor on mac/windows. Should that go in installation party?

