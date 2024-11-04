---
title: "Kill Pragmatism with a Hot Knife"
date: 2024-11-4
author: Thomas Townsley
description:  
isStarred: false
---

Today is the first real day where I would normally be working as a software consultant.
Starting at 7am, I'd quickly brew some coffee, storm off to the YMCA for a 30-45 min
workout, busily come home, shower, eat a vegan breakfast (hopefully) and leave for the office at roughly 9am.
I would do this on repeat Monday through Thursday, having stopped working from home 
because the torture of my work was throwing off the sanctity of my townhouse. 

My employer was (is) a fair company in many respects. Many people starting off in
the tech industry would thrilled to be a part of it and much of the people we hire
are new to the field. I was hired during the surge of 2020 for more talent. And when I started, 
I thought I was the luckiest guy on earth. A nice salary, the chance to build *real* software. 
Before, I'd only ever been on small web projects and bioinformatics research teams. My idea of what real software was like
was this utopian dream of unit tests, compassionate but firm code reviews from my 
higher-ups, working with extremely smart people, etc.

What I found instead was **pragmatism**.

Here is how I would define that vile word in the context of software development: 

### "We are going to work with what we have, under the time we have left, to deliver what we can."

I firmly believe this is a recipe for failure. It is in fact a philosophy of engineering whose sole
input variable is money.



### 1. "We are going to work with what we have..."

Imagine this. You are working on a feature for some app that maybe if you're lucky, are happy
to build and a team that is enjoyable to work with. You are given your first ticket and asked
to complete it by the end of the week. 

So you get to work on this ticket and pretty soon, you find that your work cannot proceed without
someone else finishing their work. You are blocked. The next day you inform everyone in your standup
that you are blocked. The lead engineer, instead of telling you to wait, comes up with some whacky way to get around being blocked so you can continue your work. This has to be done by the
end of the week!

But now, your work is no longer targeting the dependency that blocked you in the first place. When
that dependent work does finish up, you are going to have a much more challenging time going
back and glueing things together. If a team works this way over time, the result is a fucking mess.

A good lead engineer would instead ask you to do the following:

"Ok no worries. While you are waiting for the other piece to fall in line,
go back and look at your current work. Is there anything you can simplify and make more readable
to others? Can you evaulate the existing solution and be sure it makes sense for us?
*Is there anything we can eliminate?*"

2. "...under the time we have left"

In software consulting world, we do everything in terms of SOWs (Statements of Work). It is 
effectively a contract that should provide a good estimate of the amount of time and money
it takes to complete a piece of software, or component of it.

In reality, the peope who write the SOWs are not the people buiding the software. And these
people...lets call them "Engineering Leads"...very often have no fucking idea what technology
truly fits the solution. They self-select solutions based on what they know, and they scope hours
for the developers working on the project based on what they think it would take *them* to 
complete it.

Imagine I draw a picture of a boat on a piece of paper and I give it to you. I say, "You see that
guy over there? He's paying us a lot of money to build this boat I drew for you. He doesn't build boats but for the next three months but he's going to meet with you twice a week first thing in the morning to tell you what the boat should be like. Don't worry just look at this picture I drew. Also it needs to cross the English Channel by December 21st."

This situation in my view, can be compeletely ameliorated by having the people who *build*
the software also be the ones who drafted the SOW in the first place. Yes, that means even
the junior developers should have a say so they can scope their time effectively. This gets
rid of this weird false urgency created by time constraints that were arbitrarily created
in the first place. 

3. "...to deliver what we can."

I've been a part of a lot of projects where there was no "delivery", in part, because
I don't think software consulting is incentivized to care. If we burn the hours in SOW
and we're all out, then that's too fucking bad for the client. We did our tour in Vietnam
and it's time to go home now. 

Except I think there's a real mental and emotional cost for *those who build*. What did
you even spend the last six months working on? All that time, energy, and emotion...
Can you even point to something you are proud of?

I realized that I spent the past four years of my life - learning a ton don't get me wrong - but
can't point to much in terms of things I built that I'm proud of. In large part, because
this delivery model doesn't seem to care about delivery at all. 

Not to mention, I have a hard time not caring about my clients and wanting them to be happy, 
as much as I hate to admit that. They paid for a product, and instead they got to spend 
money on an ever expanding mountain of technical debt and poor decision making.

The solution I think, is to really pair down what it is a client wants into something
you can reasonably deliver. Do not overpromise. Do not say "Oh yea we can do that no problem."
Stop bullshitting them just to get their business. Clients tend to be overenthusiastic and
unrealistic but to indulge them in that and believe you can work out the details later,
is in my view, a disgrace to the art.

### Conclusion

I spent the weekend vexxing about the best possible way to wire an ESP32 board
to an external WAV Trigger Board. That solution took days and the result was
four simple wires total. The code is clear and concise. I have documentation, even if only I will ever see it. Man that feels good. There is no pragmatism involved.

I can feel my spirits lifting. The light of progress grows brighter each day.