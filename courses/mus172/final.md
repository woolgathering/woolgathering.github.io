---
layout: default
permalink: /courses/mus172/final
---
# Music 172 - Final Prompt

The final project should contain a substantial amount of DSP processing via synthesis, analysis, manipulation, or the like. That being said, the final does not necessarily have to use material we've directly covered in class but should in some way utilize the core concepts, ideas, or techniques. I'm thinking specifically of someone who wants to learn to use the GEM visuals library in Pd and control them via sound. Collaboration with classmates is accepted so long as each contributor provides a necessary and substantial contribution to the final project.

I encourage you all to think about your aesthetic and technical interests and to propose a project which follows those in some way. The most useful projects will not only teach you something but will also have life after the end of the course.

## What to submit
Submit at least one paragraph with your proposed idea. The proposal should contain a basic format of how you will proceed and any techniques you foresee being useful. If you don't know what techniques might be useful, that's totally acceptable since this will require you to actually figure out what is required. If your idea changes form over the course of you working on it, that, too, is acceptable so long as it conforms with the general requirements of the final. References are encouraged (i.e. previous works that use a similar idea, papers, articles, etc). You are also encouraged to submit any drawings, schematics, or technical documentation as well. __Due anytime before Monday of Week 9, though early submission will help us help you narrow down your proposal.__ You are welcome to submit either via your Google Drive folder or email directly to myself and the TAs if you want a more immediate response.

If you propose something very difficult or that has not yet been attempted in the literature, you can still receive full credit if the effort at realization is comparable to that of an easier but fully realized project. This would be more along the lines of a proof-of-concept.

### Example ideas for a final
- Implementation of a synthesis/analysis paradigm in a published paper ([example](https://ieeexplore.ieee.org/document/1395943), [example](http://www.music.mcgill.ca/~gary/courses/papers/Jaffe-Extensions-CMJ-1983.pdf), etc). This can also include building upon a technique we coverd in the course (the latter example given is an extension to Karplus-Strong).
  - Build your own reverb.
  - Build a spatializer.
- Replicate the sound and functionality of a classic synthesizer (MiniMoog, etc).
- Build an effects pedal-like patch that accepts live input (octave doubler, auto-wah, etc). Live input is either via [adc~] or even from a synthesizer built in Pd itself. The project would need to be substantial enough to warrant merit as a "final". It is also possible to build a "family" of patches (i.e. a complete effects rig).
- Propose a piece of music/art that uses DSP as a significant component.
  - It would need to have a substantial amount of programming built in; i.e. synthesis, software control, sensor input, etc.
  - Proof-of-concepts are encouraged.
- Build a DSP-related tool that fulfills a function in another, larger, project.
- This list is not exhaustive and if you have something else in mind we can almost certainly make it work.

__Finals are due on June 13, 2020 at 11:59pm. Turn them in as you would any other assignment. In contrast to the lax attitude we've had throughout the quarter regarding paths for sound files, abstractions, etc, you will be deducted points for patches that fail to run correctly due to pathing issues. For externals, just note what externals you used so we can install them for our own operating system (your binaries may not work on our machines).__

__If you were not able to fulfill what you set out to do in your proposal, please include a short writeup on what the difficulties were and how you might go about solving it were you to have more time. You won't lose points for not acheiving what you set out to do (it means it was a good challenge!) but I'm asking you to justify and explain what the difficulties were. Again, a proof of concept, if that's all it turns out to be, is absolutely acceptable.__

__All finals will require a demo (live performance, sequence, etc). Please submit this (video, sound) with your patch.__
