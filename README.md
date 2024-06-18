# ShakespeareGPT - Your Friendly Shakespearean Document Completer

ShakespeareGPT is a project where I delve into the world of character-level transformer models using PyTorch. This decoder-only GPT model is designed to mimic the literary style of William Shakespeare, trained on a curated dataset of his works stored in input.txt. Seeing as chatGPT is all the rage right now, I decided to take a look under the hood. 

ShakespeareGPT shows promising results, demonstrating an understanding of Shakespearean structure while also producing some less coherent outputs characteristic of character-level models.
The output after training for about 4500 steps is the following:
```
RIVERSS:
I cannot nor tetding those sit you shalt do
To well o'er the top offenders, for my honour.
We have no fger than groan the steeds and well, and
chelt his head one. Let me be spoke for another;
he was another being formed, but banish him;
he, for a pippe. I see, thought leave thee saw
In those that I condemn to unwish! If thou be
no great opparent to be in sudden formity,
who lately wear theirs past that revenge this outwo
compass.

ESCALUS:
Why do you this?

LUCIO:
Doth ship forfeitly that consul, Signio?

ANGELO:
Well; bring of all.

ESCALUS:
It is for your wisdom be the nopent. The wish, the
apperonce is a guilty will tread yourself and
profit, your sea, that the wretchedness in our sleep,
the fier eventon you as the sword or waking
and her constempore by what short is no year.

First Senator:
Weeping we well ender, were the case you--
He as sure.

AUTOLYCUS:
Gentle Pardon, my friend Potist ballads;--here is in
performity; how art like to visit the worst along,
that Aufidius, i'll seek to the people hour of the world,
because herd in French with a gage. Sile, sometime!

First Servingman:
Happily away a would to make you woman?

Second Servingman:
Now are you gerant friends; I hope, sTeeld.

Second Servingman:
In the sky cententing'd for his country, I
have almost forgotten his resolutoming friends, thature
passishes; you are puff'd for the chancemony; whom the
kings becond rootm of rast was an employman. Ladders admine
to put what you to my wench, misgive me up
not with me: but only the abprisonment die
in him. Follows true, Post lay along:
Look pale hour, shall we hear the bog
of his pon the sen flower.

POLIXENES:
O, good my lords,
Thou wilt read to the banish,
He tender with his that flattered me by hell
Some practise fit for him; and formally proceed
Such factions as we will shrink.

POLIXENES:
What is your will
Came with Aufidius like me asha, as his merripely
embashed.

COMINIUS:
Pray you, do.
```
Not bad if you consider the fact that the model has trained only for 45 minutes on a modest GPU :P

<h2> What does this mean in the context of LLMs? </h2>

In the realm of Large Languege Models, ShakespeareGPT functions as a document completer, adept at generating text in the style of its training data. This marks the initial phase akin to pre-training in transformer models.

<h2> What happens next?</h2>
Large language models undergo a process called RLHF (Reinforcement Learning from Human Feedback). This process aims to train the GPT on a smaller, specialized dataset. This phase aims to refine its capabilities, enhancing both coherence and creativity in text generation tasks.
