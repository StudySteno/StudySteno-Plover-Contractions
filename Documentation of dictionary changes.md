# THIS IS JUST A REFERENCE FILE, DO NOT INSTALL THIS INTO PLOVER AS A DICTIONARY!! IT WILL NOT WORK!  
  
This file documents all the changes and new entries that the contractions.json dictionary file makes (technically, takes priority over) to the existing entries/briefs in the default Plover dictionary.  Do not worry!  **No changes are made to your default Plover dictionary (main.json), your personal dictionary (user.json), or any other dictionary.**  The contractions.json dictionary just takes priority over other dictionaries you have installed, depending upon how you order the dictionary files in Plover's main window.  
  
You'll also find some brief notes explaining some of the changes and/or choices made, thoughts on current inconsistencies, and bit more here and there below.  
  
# Entries that are the same as the default dictionary entry:  
These entries are exactly the same as the default dictionary.  I duplicate them in this dictionary to "future proof" against changes to these briefs in the default dictionary.  Having these in both _main.json_ and _contractions.json_ causes no issues and doesn't impact performance, since Plover only parses dictionaries looking for a brief in the order of priority  you set.  
  
"-TS": "it is",  
"\*TS": "it's",  
"\*UD": "you'd",  
"AEUPBT": "ain't",  
"AO\*EUF": "I've",  
"AOEUF": "I've"  
"EULD": "I would",  
"HAO\*EL": "he'll",  
"HAO\*ERS": "here's",  
"HAO\*ES": "he's",  
"HEZ": "he has",  
"HO\*UD": "how'd",  
"HO\*UF": "how've",  
"HO\*US": "how's",  
"HOULD": "how would",  
"HR-PBT", "will not",  
"KH-D": "which had",  
"KH-R": "which are",  
"KH-S": "which is",  
"KH-Z": "which has",  
"KO\*UF": "could've",  
"KOUF": "could have",  
"KWR\*D": "why'd",  
"KWR\*L": "why will",  
"KWR-R": "why are",  
"KWR\*S": "why's",  
"KWRA\*UL": "y'all",  
"PHAOEUF": "might have",  
"SHAO\*ED": "she'd",  
"SHAO\*ED": "she'd",  
"SHAO\*EL": "she'll,"  
"SHAO\*ES": "she's",  
"SHELD": "she would," (already in dictionary, but not consistent with preferred SHAOE root :( )  
"SHES": "she is",  
"SHEZ": "she has",  
"SHO\*UPBT": "shouldn't",  
"SHO\*PBT": "shouldn't",  
"SHO\*UF": "should've",  
"SHOUF": "should have",  
"T-LD": "it would",  
"T-Z": "it has",  
"T\*S": "it's",  
"T\*D": "it'd",  
"TH-S": "this is",  
"TH\*L": "this'll",  
"THA\*D": "that'd",  
"THA\*D": "that'd",  
"THA\*F": "that've",  
"THA\*L": "that'll",  
"THALD": "that would",  
"THAOERS", "these are",  
"THAS": "that is",  
"THAZ": "that has",  
"THELD": "they would",  
"THR-LD": "there would",  
"THR-R", "there are",  
"THR-Z": "there has",  
"THR\*D", "there'd",  
"THR\*F": "there've",  
"THR\*L": "there'll",  
"THR\*S": "there's",  
"ULD": "you would",  
"W\*EF": "we've",  
"W\*UPBS": "one's",  
"WAO\*EL": "we'll",  
"WAO\*ER": "we're",  
"WER": "we are",  
"WHA\*F": "what've",  
"WHA\*D": "what'd",  
"WHA\*L": "what'll",  
"WHA\*S": "what's",  
"WHAD": "what had",  
"WHALD": "what would",  
"WHAR": "what are",  
"WHAS": "what is",  
"WHAZ": "what has",  
"WHO\*D": "who'd",  
"WHO\*F": "who've",  
"WHO\*L": "who'll",  
"WHO\*S": "who's",  
"WHOD": "who had",  
"WHOLD": "who would",  
"WHOS": "who is",  
"WO\*UF": "would've",  
"WOUF": "would have",  
"WR-R": "where are",  
"WR-F": "where have",  
"WR\*F": "where've",  
"WR-D": "where had",  
"WR\*D": "where'd",  
"WR-L": "where will",  
"WR\*L": "where'll",  
  
  
# Brief pair entries that were swapped with each other  
  
These entries generally had the `*` brief be the non-contracted phrase, and the non-`*` brief be the contracted phrase. So, the definitions for these were simply swapped with each other.  This also includes brief pairs where both entries were identical, so one of the briefs was changed to be either a contraction or the non-contracted phrase, as appropriate.  
  
"HRETS": "let us", /changed from let's  
"HR\*ETS": "let's", /changed from lets - I just use `HRET/-S` for "lets", since I use it rarely.  
  
"K-PBT": "cannot", /swapped  
"K\*PBT": "can't",  
  
"R-PBT": "are not", /swapped  
"R\*PBT": "aren't",  
  
"T-L": "it will", /changed from it'll  
"T\*L": "it'll",  
  
"TKOEPBT": "do not", /changed from don't  
"TKO\*EPBT": "don't", /changed from Don't  
  
"UR": "you are",  
"\*UR": "you're",  
  
  
# Brief pair entries where existing entry was changed, and a new corresponding brief to complete the pair was created.  
  
"HPBT": "had not", /changed from hadn't  
"H\*PBT": "hadn't", /added  
  
"HAPBT": "has not", /changed from hadn't  
"HA\*PBT": "hasn't", /added  
  
"SPBT": "is not", /changed from isn't  
"S\*PBT": "isn't", /added  
  
"SR-PBT": "have not", /changed from haven't  
"SR\*PBT": "haven't", /added  
  
"THED": "they had", /changed from they'd  
"TH\*ED": "they'd", /added  
  
"THEL": "they will", /changed from they'll  
"TH\*EL": "they'll", /added  
  
"THER": "they are", /changed from "they're"  
"TH\*ER": "they're", /added  
  
"THEF": "they have", /changed from "they've  
"TH\*EF": "they've", /added  
  
"TK-PBT": "did not", /changed from didn't  
"TK\*PBT": "didn't", /added  
  
"TKAEURPBT": "dare not", /changed from daren't  
"TKA\*EURPBT": "daren't", /added  
  
"TKUPBT": "does not", /changed from doesn't  
"TK\*UPBT: "doesn't", /added  
  
"PHUPBT": "must not", /changed from mustn't  
"PH\*UPBT": "mustn't", /added  
  
"UL": "you will", /changed from you'll  
"\*UL": "you'll", /added  
  
"WR-PBT": "were not", /changed from "weren't"  
"WR\*PBT": "weren't", /added  
  
"W-RS": "where is", /changed from where's  
"W\*RS": "where's", /added  
  
"W-RD": "where'd", /changed to where had  
"W\*RD": "where had", /added  
  
# Brief pair entries where one half of the pair existed and is unchanged, and new corresponding brief to complete the pair was created.  
  
All of these are new entries.  Some may have preexisting non-conforming entries, but that's not documented here.  Plover has a wonderful lookup tool you can use to find those entries ;)  
  
"HO\*UL": "how'll",  
"\*EULD": "I'd",  
"KH\*D": "which'd",  
"KH\*R": "which're",  
"KH\*S": "which's",  
"KWR\*R": "why're",  
"PHAO\*EUF": "might've",  
"SH\*ES": "she's", /added, even though I prefer `SHAOE` for "shoes", `SHES` is already "she is" by default, so might as well add this.  
"TH\*S": "this's",  
"THAO\*ERS", "these're",  
"W\*ER": "we're",  
"WH\*R": "when're",  
"WHA\*R": "what're",  
"WR\*R": "where're",  
  
# Brief pair entries where just one half of the pair was changed  
  
In general, these are pairs where both entries are identical, so only needed to change one entry to conform.  For example, `HOUD` and `HO*UD` were both "how'd", so `HOUD` was changed to "how had"  
  
"AOEUF": "I have", /changed from "I've"  
"HAOERS": "here is",  
"HAOES": "he is",  
"HOUD": "how had",  
"KWRAUL": "you all", /changed from ya'll  
"SHAOED": "she had",  
"SHAOEL": "she will", /changed from she'll  
"SHAOES": "she is", /changed from she's  
"SHAOEZ": "she has", / changed from she's, to fit my pattern  
"SHOUPBT": "should not", /changed from "shouldn't"  
"SHOPBT": "should not", /changed from shouldn't (note I prefer `SHOU`-based briefs)  
"T-S": "it is", /changed from it's  
"TH-L": "this will", /changed from this'll  
"THA\*S": "that's", /changed from "that as"  
"THAF": "that have", /changed changed from that've  
"THAL": "that will", /changed from that'll  
"THR-D": "there had", /changed from there'd  
"THR-L": "there will", /changed from there'll  
"THR\*R", "there're",  
"THR-S": "there is", /changed from there's  
"UD": "you had",  
"WAOER": "we are", /changed from we're  
"WAOEL": "we will", /changed from we'll  
"WHAL": "what will",  
"WHOF": "who have", /changed from who've  
"WHOL": "who will", /changed from who'll  
  
# Changes involving unrelated words  
  
"AOEUD": "I had", /changed from I'd  
"AO\*EUD": "I'd", /changed from ID, which I don't mind fingerspelling (could just change EUD to ID if desired)  
  
"HAO\*ED": "he'd", /changed from heed  
"HAOED": "he had", /changed from he'd  
"HAOED": "heed", /changed from he'd  
  
"HOUZ": "how has", /changed from 'house' to 'how has', leaving the HOUS entry for 'house'  
  
"KOPBT": "could not", _(Changed to couldn't, for consistency, even though I'm migrating away from `KO` for "could")_  
"KO\*PBT": "couldn't", _(Changed from "cotton" - I don't mind double-stroking it (really should alter this all to always use `KOU` as the root and avoid conflicts/issues like this one)  
  
"THR-F": "there have", /changed from thereof, I prefer the existing `THROF` brief for thereof  
  
"UF": "you have", /changed from "you've"  
"U\*F": "you've", /changed from "UV"  
"U\*F/U\*F": "UV", /added so there's still an entry for UV, or just fingerspell it...  
  
"WAO\*ED", "we'd", /changed from weed, since I want contractions to *always* use `*`  
"WAOED", "weed", /changed from we'd  
  
"WAOEF": "we have", /changed from we've  
"WAO\*EF": "we've", /changed from 'weave' - WAEF meets the "using spelling to differentiate homophones" rule (ya, I know, lots of us use `*` to differentiate homophones instead of spelling, but I use "we" and "we've" way more often then "weave" and this holds true to steno principles... and then there's that `WEF` oddity for weave, which could be changed to "we have" if prefer `WE` root ... oh no, it's a rabbit hole!)  
  
"KH-L": "which will", /exists  
"KH\*L": "which'll", /changed from "ChemLuminary"  
"KH\*PL": "ChemLuminary", /added  
`KH*L` maps to "ChemLuminary" which I personally think is perfectly fine to delete/overwrite, but instead I'll remap it. I've chosen to remap it to `KH*PL`, (lit., "chem\*")  
  
"WHOR": "who are", /changed from "whore", as there are steno-complilant entries in the dictionary  
"WHO\*R": "who're", /added  
  
# New entries for briefs and phrases that already exist, but don't conform to my patterns and/or default entry required two or more strokes.  
  
"HAOEZ": "he has",  
"PHAO\*EUPBT": "mightn't",  
"TPHAO\*EPBT": "needn't",  
"WOUPBT": "would not", _(Note: This pair was added since I prefer `WOU` for "would" and `-PBT` for "not".)_  
"WO\*UPBT":, "wouldn't",  
  
# New briefs and phrases  
  
These are briefs and phrases that are completely new, no existing entry at all for these contractions and phrases (although the starter word for each exists, obviously!).  
  
"KWR-F": "why have",  
"KWR\*F": "why've",  
"KWR\*L":, "why will",  
"HO\*UL", "how will",  
"THAOELS", "these will",  
"THAO\*ELS", "these'll",  
  
### Here `HAOER`  
  
There are a number of "here" briefs and phrases in the default dictionary, but not the ones below!  
  
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
"THO\*EL": "those'll",  
"THOELD": "those would", /changed from "hold it" which has another entry that works  
"THOED": "those had",  
"THOEF": "those have",  
"THO\*EF": "those've",  
"THOER": "those are", /changed from "author" which has like 7 other entries  
"THO\*ER": "those're",  
  
### Double contractions  
  
"KOUFPBT": "could not have",  
"KO\*UFPBT": "couldn't've",  
This phrase and contraction isn't used that often, and since I'm preferring `KOU` as the root for "could," I didn't bother creating a `KO` version of this brief pair. Also, `KOFPBT` is good brief for "covenant".)_  
  
"WAO\*EFD": "we'd've",  
No matching briefs for the base phrase(s), "we would have," "we should have", "we could have" (yet)  
  
# COMING SOON  
The following are NOT currently in Plover's default dictionary, and I have not created briefs for these yet, due to conflicts or other issues.  
  
he will - conflicts  hell heel El eel  
here are - brief to match pattern is technically impossible lol  
here're - conflicts  hir  
how are - conflicts hour  hor  
how have  - conflicts however  
how will - conflicts howl  
might not  - obvious brief `PHAOEUPBT` maps to midnight.  
need not  -  conflicts indeed  beneathed nineteenth  
one has  - obvious briefs `WUPBS` and `WUPBZ` both map to "ones"  
what have - conflicts  whatever  
was it - conflicts watt  
was not - conflicts want  
everything related to "why'd" - why did, why had, why should/would/could, etc.  
why will -  conflicts ideal  
we would, we would/should/could have - need to create and/or resolve conflicts  
Figure out "which have" brief (`KH-F`/`KH*F` conflicts with briefs for CHF/chronic heart failure)  
  
The following are in the default dictionary with nonconforming outlines (although true to principles of steno) ... eventually will sort out ways to create briefs that conform to the overall pattern (maybe)...  
  
he would - is in dictionary as `ELD`, brief to match pattern causes conflict, need to figure this out still ;D  
how're - is in dictionary as `HOU/*R`, brief to match pattern causes conflict, need to just rethink entire "how" family  
one is - is in dictionary as `SW*UPB`  
wasn't - is in dictionary as `WAEPT`, `WUPBT`, `WAEPBS`, `WAEPBT`, `WASZ/-PBTD` ... yea, the entire "was" family needs some sanity  
who has - is in dictionary as `WHO*Z`, `WHO/HRAS`, `WHRO/HRAS`, pattern conforming brief `WHOZ` is mapped to  "whose" (and I don't want to change that) ...  
  
**Everything below here is stuff I need to organize into the above portion of this document or deal with later.**  
  
I'm not happy with the 'I' family of briefs, still stewing on it  
I am/I'm  
So AOEUPL is "I'm" by default, but can't change it to AO*EUPL because that's mapped to {^ime} suffix and I loath changing default suffixes ... on the other hand, both EUPL and *EUPL map to {im^} prefix, so I am considering changing *EUPL to {^ime} (which is consistent with similar/related prefix and suffix strokes having a matching pair of entries in the dictionary, differentiated only by a *).  If I do this, then that frees up AO*EUPL to be "I'm" and I can change AOEUPL to "I am", while keeping EUPL as {im^} and making *EUPL {^ime}  
I will  
I'll aisle  
  
it had /am considering -TD for it had (it's 'the' right now), OR changing T-D from {^ed it} to 'it had' and changing -TD from 'the' to '{^ed it} (or use *TD for ed it)  
  
we've weave  
  
"HR\*PBT", "won't", /added, just to be consistent with root phrase  
"WOPBT", "wont", /changed from wouldn't  
"WO\*PBT", "won't", /changed from wont  
