# TheDesignPattern

Background

Years ago I wrote a blog series about "The Lazy Programmer" that teased apart long-term (beneficial) vs. short-term (detrimental) laziness to demonstrate the economic benefits of a long-view to reduce risk and efforts spent on maintenance and enhancement. It was a reaction against consulting firms engineered to maximize billable hours rather than being aligned with long-term goals of their clients - which should be to reduce the total cost of ownership (TCO).

A few discoveries were made along the way about just how dysfunctional traditional development practices - and most IT shops - really are. For one, few customers properly assess TCO and the tendency remains to work to arbitrary deadlines based on short-term budget rather than releasing the "right product" - meaning the product is both beneficial to its owners and maximizes efficiency with respect to support, maintenance and enhancement. The right product would minimize TCO, but short-sighted decision makers too often inflate TCO in favour of short-term optics.

Another constraint is our inability to predict the future - we can only plan for imminent enhancements. To plan for more than what we know adds weight and complexity that too often proves a waste. Think back on the promises of object oriented programming (reusable everything!) versus how it all worked out and you should get the idea. While there are many systems we've built more than 3 times - so we know what part of the pattern repeats and what is variable in order to design a generic solution - any given developer working on a problem is limited by context. Our default world-view is "what you see is all there is," so we tend to see only the problem in front of us and don't have the benefit of either knowing a solution already axists, or of knowing that _this_ is an opportunity to write a generic solution. Even when we know the opportunity exists, we can't realize it because the project only considers its own time or budget and not the org's TCO. Too often cutting and pasting a solution discovered online is the right answer for the project even though it increases the complexity of maintenance.

There was one happy discovery with much potential: whole classes of prior work to reduce complexity in specific domains can be applied to architecture at all scopes, from the enterprise on down. Not simply that "databases can be normalized," but that normalization techniques can be dehydrated to basic principles that can be rehydrated and applied in other domains including the refactoring of code. This integration of ideas and other benefits of cross-training are inherent in the work of many good architects.

There are attempts to improve our lot. GitHub is a public code library that supports and encourages re-use. But even the App model now threatens to repeat itself inside orgs, and we'll end up with x^y Contact List templates because no instance is right for every combination of purpose, country, or audience. Do most orgs need or want the diversity typical of a public App marketplace? The point isn't your answer, it's whether you've considered how this all works in the long-run. The math isn't tricky. The complexity of maintaining branches until the org can return to a commodity solution, also known as "technical debt," grows by orders of magnitude. Failure to plan the ecosystem with capabilities-based rather than one-off-feature-based solutions inevitably leads orgs beyond complexity into chaos.

This repo is an attempt to root out the underlying issues, to describe and share solutions. As a Pattern Language, the goal is to tear IT Patterns from the architects and provide everyone: developers, analysts, stakeholders, and yes, architects - let's be novel and call them all people - with tools to effectively share ideas and innovation.


# The Pattern of Design, or A Pattern Grammar 

True design patterns create living things. Design patterns are generative.

There have been minor victories where technical design patterns are successfully and repeatably applied to application architecture and construction.

But to date, the relationships between technical design patterns and the living world in which they exist are barely recognizable. 

There are two reasons for this. 

The first is that technical design patterns are only being used to describe problem domains and solutions, and not processes. they are solution patterns where improving the actual process of design is not the point. 

The second is that the language being used by technical architects bears no relationship to the living world in which it exists. 

They are formulae without life. Automata, not art.

Christopher Alexander founded the design pattern movement. His original patterns were about how people related to their environs, while technical design patterns are entirely disconnected from people. Beyond encoding algorithms, we should be encoding human processes, workflow, the flow of the business in the patterns.

At the enterprise level, we should be describing the flow of information in effecting the cultural DNA of each organization.

Just as Alexander and his proponents identified patterns unfolding in homes, streets, buildings, tracts of land, and cities, we should be describing the unfolding of function and capability into software.

Alexander cites three values inherent in his original design pattern. "First, it has a moral component. Second, it has the aim of creating coherence, morphological coherence in the things which are made with it. And third, it is generative: it allows people to create coherence, morally sound objects, and encourages and enables this process because of its emphasis on the coherence of the created whole."

Of the moral component, "One of the things we looked for was a profound impact on human life. We were able to judge patterns, and tried to judge them, according to the extent that when present in the environment we were confident that they really do make people more whole in themselves."

Of the generative component, "to what extent does the language generate (hence produce) entities that are whole and coherent?"

Of coherence, "We were always looking for the capacity of a pattern language to generate coherence, and that was the most vital test used, again and again, during the process of creating a language. The language was always seen as a whole. We were looking for the extent to which, as a whole, a pattern language would produce a coherent entity." 

Of generative structures, "It turns out that these living structures can only be produced by an unfolding wholeness. . . . You operate on it through things that I have come to call "structure-preserving transformations,” maintaining the whole at each step, but gradually introducing differentiations one after the other. And if these transformations are truly structure-preserving and structure-enhancing, then you will come out at the end with living structure. . . . If a process doesn’t go in the structure-preserving way that I'm talking about, the result is never living structure." 

A pattern language of the worldwide web. 
