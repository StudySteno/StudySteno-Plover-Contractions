# THIS IS JUST A REFERENCE FILE, DO NOT INSTALL THIS INTO PLOVER AS A DICTIONARY!! IT WILL NOT WORK!

This file documents all the changes and new entries that the contractions.json dictionary file makes (technically, takes priority over) to the existing entries/briefs in the default Plover dictionary.  Do not worry!  **No changes are made to your default Plover dictionary (main.json), your personal dictionary (user.json), or any other dictionary.**  The contractions.json dictionary just takes priority over other dictionaries you have installed, depending upon how you order the dictionary files in Plover's main window.

You'll also find some brief notes explaining some of the changes and/or choices made, thoughts on current inconsistencies, and bit more here and there below.

# THIS IS JUST A REFERENCE FILE, DO NOT INSTALL THIS INTO PLOVER AS A DICTIONARY!! IT WILL NOT WORK!

# Entries that are the same as the default dictionary entry:

"AEUPBT": "ain't", 
"AOEUF": "I've"
"KOUF": "could have",   
"KO\*UF": "could’ve",   
"KWRA\*UL": "y'all",   
"HEZ": "he has",   
"HAO\*ES": "he’s",   
"HAO\*EL": "he'll",   
"HAO\*ERS": "here’s",  
"HO\*US": "how's",   
"HO\*UF": "how've",   
"HOULD": "how would",   
"HO\*UD": "how'd",   
"HR-PBT", "will not",   
"AO\*EUF": "I’ve",   
"EULD": "I would",   
"PHAOEUF": "might have",  
"SHES": "she is",   
"SHEZ": "she has",   
"SHAO\*ES": "she's",   
"SHAO\*EL": "she’ll,"   
"SHELD": "she would," (already in dictionary, but not consistent with preferred SHAOE root :( )  
"SHAO\*ED": "she’d",   
"SHOUF": "should have",  
"SHO\*UF": "should’ve",  
"SHO\*PBT": "shouldn't",  
"SHO*UPBT": "shouldn't",
"T-LD": "it would",   
"T\*D": "it’d",   
"-TS": "it is",
"*TS": "it’s",   
"T*S": "it's", 
"T-Z": "it has",   
"TH\*L": "this’ll",   
"TH-S": "this is",   
"THA*D": "that'd",  
"THA\*F": "that've",   
"THA\*L": "that’ll",  
"THALD": "that would",  
"THAS": "that is",  
"THA\*D": "that’d",   
"THAZ": "that has",
"THAOERS", "these are",  
"THELD": "they would",   
"THR\*F": "there’ve",   
"THR-Z": "there has",
"THR\*S": "there’s",   
"THR\*L": "there’ll",   
"THR-LD": "there would",   
"THR\*D", "there’d",   
"THR-R", "there are",   
"ULD": "you would",   
"\*UD": "you’d",   
"W\*UPBS": "one’s",   
"WAO\*ER": "we're",   
"W\*EF": "we’ve",   
"WAO\*EL": "we’ll",   
"WHAS": "what is",   
"WHA\*L": "what’ll",   
"WHALD": "what would",   
"WHAD": "what had",   
"WHA\*D": "what’d",  
"WHA\*S": "what’s",   
"WHAZ": "what has",  
"WHO\*F": "who’ve",   
"WHOS": "who is",   
"WHO\*S": "who’s",   
"WHO\*L": "who’ll",   
"WHOLD": "who would",   
"WHOD": "who had",   
"WHO\*D": "who’d",  
"WOUF": "would have",  
"WO\*UF": "would’ve",  

# Brief pair entries that were swapped with each other

These entries generally had the `*` brief be the non-contracted phrase, and the non-`*` brief be the contracted phrase. So, the definitions for these were simply swapped with each other.  This also includes brief pairs where both entries were identical, so one of the briefs was changed to be either a contraction or the non-contracted phrase, as appropriate.

"R-PBT": "are not", /swapped  
"R\*PBT": "aren’t",

"K-PBT": "cannot", /swapped  
"K\*PBT": "can’t",

"T-L": "it will", /changed from it'll  
"T\*L": "it’ll", 

"TKOEPBT": "do not", /changed from don't  
"TKO\*EPBT": "don’t", /changed from Don't

"UR": "you are",  
"\*UR": "you’re",

# Brief pair entries where existing entry was changed, and a new corresponding brief to complete the pair was created.

"HPBT": "had not", /changed from hadn't  
"H\*PBT": "hadn’t", /added

"HAPBT": "has not", /changed from hadn't  
"HA\*PBT": "hasn’t", /added

"SPBT": "is not", /changed from isn't  
"S\*PBT": "isn’t", /added

"SR-PBT": "have not", /changed from haven't  
"SR\*PBT": "haven’t", /added

"THED": "they had", /changed from they'd
"TH*ED": "they'd", /added

"THEL": "they will", /changed from they'll
"TH*EL": "they’ll", /added

"THER": "they are", /changed from "they're"  
"TH\*ER": "they’re", /added

"THEF": "they have", /changed from "they've  
"TH\*EF": "they’ve", /added 

"THR-S": "there is", /changed from there's  


"TK-PBT": "did not", /changed from didn't  
"TK\*PBT": "didn’t", /added

"TKAEURPBT": "dare not", /changed from daren't  
"TKA\*EURPBT": "daren't", /added

"TKUPBT": "does not", /changed from doesn't  
"TK\*UPBT: "doesn’t", /added

"PHUPBT": "must not", /changed from mustn't  
"PH\*UPBT": "mustn’t", /added

"UL": "you will", /changed from you'll  
"\*UL": "you’ll", /added

"WR-PBT": "were not", /changed from "weren't"  
"WR\*PBT": "weren’t", /added

# Brief pair entries where one half of the pair existed and is unchanged, and new corresponding brief to complete the pair was created.

All of these are new entries.  Some may have preexisting non-conforming entries, but that's not documented here.  Plover has a wonderful lookup tool you can use to find those entries ;)

"PHAO\*EUF": "might’ve", /added
"SH*ES": "she’s", /added, even though I prefer `SHAOE` for "shoes", `SHES` is already "she is" by default, so might as well add this.
"THAO*ERS", "these're",


# Brief pair entries where just one half of the pair was changed

In general, these are pairs where both entries are identical, so only needed to change one entry to conform.  For example, `HOUD` and `HO*UD` were both "how'd", so `HOUD` was changed to "how had"

"AOEUF": "I have", /changed from "I've"
"HAOERS": "here is",  
"HAOES": "he is",  
"HOUD": "how had",  
"SHAOEL": "she will", /changed from she'll  
"SHAOES": "she is", /changed from she's  
"SHAOEZ": "she has", / changed from she's, to fit my pattern
"SHOUPBT": "should not", /changed from "shouldn't"
"T-S": "it is", /changed from it's   
"TH-L": "this will", /changed from this'll   
"THA*S": "that's", /changed from "that as"  
"THAF": "that have", /changed changed from that've
"THAL": "that will", /changed from that'll
"THR-D": "there had", /changed from there'd  
"THR-L": "there will", /changed from there'll  
"THR*R", "there're",  
"UD": "you had",
"WAOER": "we are", /changed from we're
"WAOEL": "we will", /changed from we'll      
"WHAL": "what will",

# Changes involving unrelated words
I *really* focused on avoiding changing the briefs for any unrelated words that just happened to sound the same as a contraction, so there's very few of these..

"HAO\*ED": "he’d", /changed from heed  
"HAOED": "he had", /changed from he'd  
"HAOED": "heed", /changed from he'd

"HOUZ": "how has", /changed from 'house' to 'how has', leaving the HOUS entry for 'house'

"KOPBT": "could not", _(Changed to couldn't, for consistency, even though I'm migrating away from `KO` for "could")_  
"KO\*PBT": "couldn’t", _(Changed from "cotton" - I don't mind double-stroking it (really should alter this all to always use `KOU` as the root and avoid conflicts/issues like this one)

"THR-F": "there have", /changed from thereof, I prefer the existing `THROF` brief for thereof  

"UF": "you have", /changed from "you've"  
"U\*F": "you’ve", /changed from "UV"  
"U\*F/U\*F": "UV", /added so there's still an entry for UV, or just fingerspell it...

"WAO\*ED", "we’d", /changed from weed, since I want contractions to *always* use `*`
"WAOED", "weed", /changed from we'd

"WAOEF": "we have", /changed from we've
"WAO*EF": "we've", /changed from 'weave' - WAEF meets the "using spelling to differentiate homophones" rule (ya, I know, lots of us use `*` to differentiate homophones instead of spelling, but I use "we" and "we've" way more often then "weave" and this holds true to steno principles... and then there's that `WEF` oddity for weave, which could be changed to "we have" if prefer `WE` root ... oh no, it's a rabbit hole!)


# New entries for briefs and phrases that already exist, but don't conform to my patterns

"HAOEZ": "he has",  
"WOUPBT": "would not", _(Note: This pair was added since I prefer `WOU` for "would" and `-PBT` for "not".)_  
"WO\*UPBT":, "wouldn’t",


# New briefs and phrases

These are briefs and phrases that are completely new, no existing entry at all for these contractions and phrases (although the starter word for each exists, obviously!).

"THAOELS", "these will",
"THAO*ELS", "these'll",

### Here `HAOER`

There are a number of "here" briefs and phrases, but the ones below do not currently exist.

"HAOERZ": "here has",  
"HAOERL": "here will",  
"HAO\*ERL": "here'll",   
"HAOERLD": "here would",  
"HAO\*ERD": "here'd",


### Somebody `SPH-B` 
There are numerous entries/options for the word "somebody." I prefer `SPH-B` as the brief for the left-hand phrase starter brief (or as I tend to call it, the "root" brief). All of these are new entries, some bump against orthography, but the orthographic strokes are generally nonsensicle words.  If you really want to write "somebodieds" you can still stroke it using orthographic norms (`SPH-B/-D/-S` or `SPH-BD/-S`) 

"SPH-BL": "somebody will",  
"SPH\*BL": "somebody'll",  
"SPH-BLD": "somebody would",  
"SPH-BD": "somebody had",  
"SPH\*BD": "somebody'd",   
"SPH-BS": "somebody is",  
"SPH-BZ": "somebody has",  
"SPH\*BS": "somebody's",   

### Someone `SPH-PB`
There are numerous entries/options for the word "someone." I prefer `SPH-PB` as the root. All of these are new entries, some bump against orthography but the orthographic strokes are nonsensicle - such as  'someoneds'.  If you really want to write "someoneds" you can still stroke using orthographic norms (`SPH-PB/-D/-S`)

"SPH-PBL": "someone will",  
"SPH\*PBL": "someone'll",   
"SPH-PBLD": "someone would",   
"SPH-PBD": "someone had",   
"SPH\*PBD": "someone'd",   
"SPH-PBS": "someone is",   
"SPH-PBZ": "someone has",  
"SPH\*PBS": "someone's", _(Note that there are double-stroke entries for "someone's", such as `SWUPB/AES`, but these do not conform with existing single-stroke contraction norms/entries, or my approach.)_

### Something `SPH-G`
As with "someone", there are numerous entries/options for the word "something." I prefer `SPH-G` as the root brief for "someone." These are all new entries, a bit of orthographic bumping but if you really need to write "somethingeds" you can still stroke it using orthographic norms (`SPH-G/G/-D/-S` or perhaps `SPH-G/GD/S`)

SPH-LG": "something will  
SPH\*LG": "something'll  
SPH-LGD": "something would  
SPH-GD": "something had  
SPH-GS": "something is  
SPH-GZ": "something has  
SPH\*GS": "something's

### Those `THOE`
For the "those" family of briefs and contractions, I drop the ending `S` or `Z` (from `THOES` or `THOEZ`, among others), and use `THOE` as the left-hand starter brief for briefing phrases.

"THOEL": "those will",  
"THO*EL": "those'll",  
"THOELD": "those would", /changed from "hold it" which has another entry that works  
"THOED": "those had",   
"THOEF": "those have",  
"THO*EF": "those've",  
"THOER": "those are", /changed from "author" which has like 7 other entries  
"THO*ER": "those're",  


### Double contractions

"KOUFPBT": "could not have",
"KO\*UFPBT": "couldn't've",
This phrase and contraction isn't used that often, and since I'm preferring `KOU` as the root for "could," I didn't bother creating a `KO` version of this brief pair. Also, `KOFPBT` is good brief for "covenant".)_   

"WAO*EFD": "we'd've",
No matching brief for the base phrase, "we would have," as anything that follows my pattern creates conflicts I've not sorted out options for yet.

# COMING SOON

he will - is NOT in dictionary, brief to match pattern causes conflict, need to figure this out still ;D  
he would - is in dictionary as ELD, brief to match pattern causes conflict, need to figure this out still ;D  
here are - is NOT in dictionary, brief to match pattern causes conflict, need to figure this out still ;D  
here're - is NOT in dictionary, brief to match pattern causes conflict, need to figure this out still - low priority, it's not used a lot ;D
how are  
how're  
how is  
how have  
how will - not in dictionary. Obvious brief - HOUL - is only entry for word "howl," so conflicts. Need to figure out.  
Might not  
Mightn’t  
Need not  
Needn’t  
one is  
one has  
what are  
what're  
what have  
what've  
was it  (Several options for 'was,' I prefer WA- as the root, but that creates numerous conflicts, hrm... come back to this)  
Was not  
Wasn’t  
when's  
when're  
when've  
when'd  
when'll  
where's  
where're  
where've  
where'd  
where'll  
which's  
which're  
which've  
which'd  
which'll  
why's  
why're  
why've  
why'd  
why'll  
who has 
we would have - need to resolve conflicts 

**Everything below here is stuff I need to organize into the above portion of this document.** 

(root of how is HOU)
"HO*UL": "how'll", /added  
/ I'm not happy with the 'I' family of briefs, still stewing on it
I am/I’m
So AOEUPL is "I'm" by default, but can't change it to AO*EUPL because that's mapped to {^ime} suffix and I loath changing default suffixes ... on the other hand, both EUPL and *EUPL map to {im^} prefix, so I am considering changing *EUPL to {^ime} (which is consistent with similar/related prefix and suffix strokes having a matching pair of entries in the dictionary, differentiated only by a *).  If I do this, then that frees up AO*EUPL to be "I'm" and I can change AOEUPL to "I am", while keeping EUPL as {im^} and making *EUPL {^ime}

I will
I’ll
"EU*LD": "I'd", /added
"AOEUD": "I had", /changed from I'd
"AO*EUD": "I’d", /changed from ID, which I don't mind fingerspelling (could just change EUD to ID if desired)


 


it had /am considering -TD for it had (it's 'the' right now), OR changing T-D from {^ed it} to 'it had' and changing -TD from 'the' to '{^ed it} (or use *TD for ed it)

"HRETS": "let us", /changed from let's
"HR*ETS": "let’s", /changed from lets (lets is a term primarily used in UK/non-USA English, equivalent to 'rent' in meaning. I just use HRET/S for lets, since I use it rarely.  Others may wish to leave this as is.)





she had

"SHOPBT": "should not", /swapped from shouldn't


 somehow somehow somehow should shouldn't shouldn't shouldn't SHO*PB shouldn't


 


this's
this'd

"WER": "we are",We're we're
"W*ER": "we’re", /added to be consistent with WER
we've weave
we'd 

we would
we had
 
"WHA*Z": "what as",

"WHOR": "who are", /changed-added - "whore" has WHOER version
"WHO*R": "who’re", /added
"WHOF": "who have", /changed-added
"WHOL": "who will", /changed from who'll

"HR*PBT", "won't", /added, just to be consistent with root phrase
"WOPBT", "wont", /changed from wouldn't
"WO*PBT", "won't", /changed from wont


"KWRAUL": "you all", /changed from ya'll



 