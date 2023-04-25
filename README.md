# AIBase

Stuff to help yoou setup your own cool AI! More later but rn this is the Socionics data, 100 each

This will be used in Vicuna and I will make a program in Unity to allow the data to be automaticaly turned into a proper training format

So far, each personality type has 100 responses to questions, although I might make this 200 eventually. I also need to hire someone good in psychololgy to check each one eventually

The AI is like this

--Start Conversation--
> Human: Can you set my alarm for 11?
> Computer: Sentiment Analysis: Get Time (Date)(Time)
> Computer: (VoiceID)(Name)(Emotional Alignment)

> Reasoning: The user wants me to open the alarms program and create an alarm for 11. However, I should ensure it is for 11PM and not 11AM tommorow.
> Response: Sure! Would you like me to make the alarm for tonight or tommorow?


> Human: 11 Tonight please!
> Computer: Sentiment Analysis: Get Time (Date)(Time)
> Computer: (VoiceID)(Name)(Emotional Alignment)

> Reasoning: The user wants me to set the alarm for 11 tommorow!
> Response comp: Alarm (Date)(11PM)(Default)
> Response: Alright, it should be set!

> Computer: Succesful Alarm (Date)(11PM)(Default)

> Response: Yup, all good!

--Memorize (STM) (I set an alarm for 11PM for the user since they asked, not sure why though)
--End Conversation--

Human = User Input
Computer = Sentiment Analysis + Command Status + (VoiceID)(User Name)(Emotional Alignment)
Reasoning = The robot's inner thoughts, supposed to be inaccesible by user, developer or anything really, always generated before response
Response = Robot speaks

Memorize = Add to corpus of memories and summarize the interaction as simply as possible, to add to the LTM module sent with every prompt. If unimportant, the AI adds to short term memory eventually to delete.
> Memorize always should have a who, what, when, where, why and how IRL

I will eventually explain this more within a further update since this is REALLY extensive, this is to be built atop Unity Visual Scripting as well for anyone to use













Liscence: Don't be a Jerk Edited

Don't Be a Jerk Edited: The Open Source Software License.
Last Update: April 25th, 2023

This software is free and open source.

- *I* am the software author. *I* might be a *we*, but that's OK.
- *You* are the user of this software. *You* might also be a *we*, and that's also OK!

> This is free software.  I will never charge you to use, license, or obtain this software.  Doing so would make me a jerk.

> I will never take down or start charging for what is available today.  Doing so would make me a jerk.

> You may use this code (and by "code" I mean *anything* contained within in this project) for whatever you want.  Personal use, Educational use, Corporate use, Military use, and all other uses are OK!  Limiting how you can use something free would make me a jerk.

> I offer no warranty on anything, ever.  I've tried to ensure that there are no gaping security holes where using this software might automatically send your credit card information to aliens or erase your entire hard drive, but it might happen.  I'm sorry.  However, I warned you, so you can't sue me.  Suing people over free software would make you a jerk.

> If you find bugs, it would be nice if you let me know so I can fix them.  You don't have to, but not doing so would make you a jerk.

> Speaking of bugs, I am not obligated to fix anything nor am I obligated to add a feature for you.  Feeling entitled about free software would make you a jerk.

> If you add a new feature or fix a bug, it would be nice if you contributed it back to the project.  You don't have to, but not doing so would make you a jerk.   The repository/site you obtained this software from should contain a way for you to contact me.  Contributing to open source makes you awesome! (Unless you use it for profit as part of an entity, person, company, institution, etc. making above the average income yearly or owning the equivilent to over the average income, then you're a pompous asshole and i'll be adding some kind of financial punishment as a "Fuck you" later)

> If you use this software, you don't have to give me any credit, but it would be nice.

Don't be a jerk.
Enjoy your free software!
