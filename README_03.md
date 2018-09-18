# readme
# readme
# H1 Digital Culture Poet
## H2 Artist Statement

I aim to use code as a divination tool to access the collective consciousness of computational chance at a continually changing present moment. My curation of the results is dictated by the throwing of sticks. The creation and curation of my poetry corpus is channeled from the trance state induced through the virtual chewing of the leaves of the Salvia Divinorum plant-teacher and her accompanying light body as she transects linear time, within a modded version of the video game *The Sims4*. Through the simulated avatar-shaman’s piecemeal quantum scanning of linear causality within the video game, we hope to coax a  multidimensional cymatic hologram of the virtual eschaton, which will theoretically be analogous to the hyperdimensional object at the end of time within the “real” universe as well. Thus, by glimpsing a crude digital sketch of the eschatological eye of the ineffable,  I can better prepare for uploading my existence into non-linear communion with the bold axis of cosmological infinite programmatic knowledge when my mortal coil becomes obsolete.

A generated poem example can be seen below:

 Nam Myoho Renge Kyo, The cold ShamWow extremely hovers a bowels whilst the Demiurge channels a mallard. How can a analogous tuber immolate in the noise festival?

Through the intervention of many random ecstatic computational poem iterations, cryptically prophetic metaphorical meaning will spill from the shadow of the future into the present. Unfortunately, the meaning of said poems will only become fully clear to the consensus public after the events have occurred, not earlier when the prescient poem was generated. This outstanding problem of interpreting vague metaphors about future events is one best left to poets, the time tested masters of singular, direct, and objective, semiotics and semantics.

''' python

#!/usr/bin/env python2
# -*- coding: utf-8 -*-
"""
author: Hunter Stabler
DESCRIPTION: python poem generator
LICENSE:GNU General Public License
created August 28th 2018
"""

import random


# "list of exclamations"
exclamations = ["Wow", "Yeet", "Goodbye", "Hallelujah", "Nam Myoho Renge Kyo",
                "He gave us some yogurt", "Kamehame ha", "Oh dear", "Yes",
                "Ow", "Sup bibble", "Yip", "Okay", "Hola", "And so it will be",
                "Hark"]

# "list of nouns"
nouns = ["savant", "sheeple", "weavel", "goober", "tuber", "owl", "bowels",
         "carpet", "snack", "arch", "toenail", "horse hair", "compost", "casm",
        "pocket", "dullard", "mallard", "listicle", "miracle", "awl",
        "Demiurge", "mangosteen", "Timor", "pow wow", "detour","ShamWow"]

# "list of place nouns"
place_nouns = ["hind quarters", "AA meeting", "parking lot", "noise festival",
               "Apalachians", "Zeta Reticuli", "ocean floor", "HoJo", "Dojo",
               "onsen"]

# "list of verbs"
verbs = ["hover", "whack", "dabble", "immolate", "taste", "summon",
         "channel", "throw", ]

# "list of adjectives"
adjectives = ["cold", "frumpy", "acrid", "sour", "toasty", "smarmy", "doty",
              "spidery", "wispy", "angular", "sharp", "tiniest", "basic",
              "omnipresent", "oracular", "miraculous", "super computer",
              "awe inspiring", "analogue", "analogous", "teleological"]
# "list of adverbs"
adverbs = ["slinkily", "eagerly", "brutally", "unabashedly", "daily", "soon",
           "outside", "underground","prophetically", "extremely",
           "sardonically",   ]

noun = random.choice(nouns)
second_noun = random.choice(nouns)
third_noun = random.choice(nouns)
fourth_noun = random.choice(nouns)
fifth_noun = random.choice(nouns)

verb = random.choice(verbs)
second_verb = random.choice(verbs)
third_verb = random.choice(verbs)

adjective = random.choice(adjectives)
second_adjective = random.choice(adjectives)

adverb = random.choice(adverbs)
second_adverb = random.choice(adverbs)

exclamation = random.choice(exclamations)

place_noun = random.choice(place_nouns)

##concatenation
#print "The " + adjective + ", " + second_adjective + " " + noun + " " + verb

#word poem
#print "The " + adjective + " " + noun + ""
## for loop to iterate through verbs
#i = 1
#for verb in verbs:
#    whitespace = " " * i
#    print whitespace + verb
#    i = i + 1




#string formatting
print " {ex}, The {adj} {n} {adv} {v}s a {sn} whilst the {tn} {sv}s a {fthn}.\
 How can a {sa} {fn} {tv} in the {pn}?".format(adj=adjective,
        n=noun, v=verb, sn=second_noun, tn=third_noun, sv=second_verb,
        adv=adverb, ex=exclamation, pn=place_noun, sa=second_adjective,
        fn=fourth_noun, fthn=fifth_noun, tv=third_verb)





#i = 0
#for noun in nouns:
#    print nouns[i]
#    i = i + 1

#" How can a {sa} {fn} {tv} in the {pn}? "