# StudySteno:  Greygal's Contractions Dictionary
My [Plover](http://www.openstenoproject.org/) steno dictionary of contractions and briefs for the related non-contracted phrase, based on [Waleed Khan](https://waleedkhan.name)'s approach to writing contractions with an asterisk (*). I think his approach is genius, so over time I integrated the use of `*` for contractions into my own dictionary. See https://waleedkhan.name/blog/my-steno-system/#use-asterisks-for-apostrophes-in-contractions for details.

Fair warning, I tend to over-explain the obvious.

## Some definitions

Brief = single-stroke abbreviation of one word

Brief pair = a pair (or set) of briefs that represent similar or related briefs or phrases but for a minor difference between the two (such as "that'll" and "that will" - they are essentially the same words, but with the minor difference being one is a contraction and one is not).

Contraction = a word or group of words resulting from shortening and/or combining two or more words into a single relative word.  Example: It is = it's  _Note:_ "Non-contracted" or "uncontracted" refers to the words used to create the contraction, before contracting it.  "It is" is non-contracted/uncontracted, "it's" is contracted/contraction.

Entries = Refers specifically to entries in Plover's dictionary, but can apply to any steno dictionary.

Plover = A fantastic, completely free, open source steno software program.  Plover has evolved into a full-featured, highly customizable yet simple to use program that lets anyone at all use steno to write, even if they don't have a steno machine. Plover has a great community of self-taught steno fanactics on Discord, too!  For more information about the Open Steno Project and Plover, visit http://www.openstenoproject.org/ and https://github.com/openstenoproject/plover

Phrase = single-stroke abbreviation that represents more than one word

Star = asterisk (*), specifically, the large center key on a steno keyboard that is represented by the `*` symbol in raw steno.

# WHY

Plover has entries for briefs covering all common English language contractions, and most of the less common/archaic ones.  Many of these entries already use `*`, but many do not.  This makes sense in some ways, since one tends to want the simplest briefs to write to be reserved for the most common words and phrases, and many steno users consider non-* briefs to be simpler to use.

However, you end up with some pattern inconsistencies, where the contracted phrase doesn't use a star sometimes and other times it does use a star.  

I think, especially for those learning steno, that *always* using `*` to designate the contracted version of a phrase, plus defining the non-`*` version of that brief to be the non-contracted version of that phrase, is far simpler to learn and remember.

Essentially, all common two word phrases use the most common right-hand (usually) brief for the first word combined with the most common left-hand brief for the second word (the contracted word), to create a brief for a contraction or for a phrase.  

> `TH` = "this"  
> `-L` = "'ll"

Therefore, it makes sense that `TH-L` would be "this'll"

But wait! What about a brief for the phrase, "this will"?  Don't we also commonly use `-L` for "will" when creating briefs for phrases?  Well, yes, indeed, we do!  So why don't we just use `TH*L` for "this will?" ... oh, wait, `TH*L` is already in the dictionary for "this'll" and there's no entry at all for "this will" ... wouldn't it make sense to just change either `TH-L` or `TH*L` to be "this will" and "this'll"? Hrm...

So as I dug deep into the dictionary, it did seem that more often than not, the non-`*` version of a pair of related briefs/phrases was the contracted version, and the `*` version was either ALSO the contracted version of the phrase, or it was the non-contracted version. So I made the decision that I'd go with the flow and started to dutifully edit the `*` version of entries that were identical to the non-`*` version to be the non-contracted phrase, or to create a `*` version if it didn't already exist.  

Except... the dictionary isn't consistent in its inconsistencies.  For example:

> `WH-L` "when will",  
> `WH*L` "when'll",

> `KH-L` "which will", but no entry whatsoever for "which'll" (granted, it's not a very common contraction).

> `EU` = "I"  
> `AOEUL` = "I'll  
> `HR*EU` "I will"

Then there's the entire would/could/should family of briefs and phrases... sometimes they use `WO`/`CO`/`SHO` as the starter, sometimes `WOU`/`COU`/`SHOU` ... and contracted phrases are usually using `*` while non-contracted phrases are not....

Sigh... while there are patterns within the patterns and virtually every entry whether for a contraction or non-contracted phrase actually does hold true to the principles of steno, **_having a singular, (mostly) all-encompassing approach to briefing contractions and their non-contracted phrase is preferable to trying to remember which brief pair uses which of the various approaches,_** to say the least.

Of course, as many before me can attest to, I quickly realized if one keeps the non-`*` version of a brief pair to be the contracted version, and the `*` version to be the non-contracted version,  you're running into some heavy-duty mental gymnastics trying to remember which common phrase briefs use `*` and which don't... and the simple fact that there's no entry whatsoever for a ton of common non-contracted contractions.

> `TH-L` and `TH*L` both for "this'll", no entry for "this will," but `TH-B` for "this be" ... 

There's gotta be a better way, and of course, there is.  **Waleed's way:  Use * for ALL contractions.**

I set out to integrate his approach into my own dictionary, and herein I present to you my contractions dictionary, complete with non-contracted phrases paired with each contraction.  This dictionary is compatible with Plover 4.0x version, and while it probably works with older versions, I don't support the older version and you should seriously, really, like right this very minute update to the latest weekly release of Plover.

# HOW IT WORKS

Non-contracted phrase:  Take the most common left-hand brief for the starter word (note I tend to prefer phoneticly-true briefs) and combine it with the most common right-hand "phrase ender" brief for the ending word.

Contracted phrase: Same thing, but add `*`

## Left-hand phrase starter words:
Most of these will already be familiar to you, as I utlized existing norms as much as possible.

Brief|Word
-----|------
AOEU, EU|I _(see note in the "tricky bits" section.)_
K-|can
KO-, KOU |could _(`KOU` is preferred.  Note I'm migrating away from using `WO`, as I prefer the `WOU` version, although sorting out conflicts is ongoing.)_
H|had 
HA|has
HAOE|he _(note that `HE`-based entries still exist for some phrases, I prefer phonetic versions)._
HAOER|here
HOU|how
HR-|will
HRET|let
PHAOEU|might _(note the dropping of the ending `-T` for purposes of briefing)_
PHU|must _(note the dropping of the ending `-FT` for purposes of briefing)_
R-|are
SHAOE|she _(note that `SHE`-based entries still exist for some phrases, I prefer phonetic versions.)_
SHO, SHOU|should _(note I'm migrating away from using `SHO`, as I prefer the `SHOU` version.)_
SPH|somebody
SPH-LG|something
SPH-PB|someone
SR-|have
T-|it
TH|this
THA|that
THE|they _(don't get me started on the conflicts caused by a phonetic entry for "they")_
THR|there
TK-|did
TKOE|do
TKU|does _(technically, "does" is `TKUZ` but for finger sanity reasons, I drop the `Z` when briefing phrases)_
THAOES|these
WO, WOU|would _(note I'm migrating away from using `WO`, as I prefer the `WOU` version, although sorting out conflicts is ongoing.)_
THOES, THOEZ|those _(note there are several options for 'those' in the default dictionary. I prefer `THOEZ`, but sometimes also use `THOES` because of simpler/easier fingering, so both are used as a root for most of these entries, except where creates conflicts.  Sometimes the ending `S` or `Z` is entirely dropped, and its likely that I'll make that my standard approach in the future.)_
WAOE|we _(note some `WE`-based entries still exist for some phrases due to conflicts, I do prefer phonetic version although still resolving conflicts.)_
WHA|what
WHO|who
WR-|were
U|you

## Right-hand phrase enders:
Again, most of these will already be familar to you.  Simply add/tuck them into the left hand starter brief to use.

Brief|Word
-----|------
-D|had, contraction for could, should and would, also sometimes did
-F|have
-L|will
-LD|would
-PBT|not
-R|are
-S|is, sometimes us such as in "let us", and contraction for "has"
-Z|has

## To make the phrase a contraction, simply add `*` to the brief.

> `THA` = that  
> `-S` = is    
> `THA-S` = that is    
> `THA*S` = that's

# TRICKY BITS TO WATCH OUT FOR

## Y'all and you all

"y'all" is written phonetically with `*`, not with starter `U`:  `KWRA*UL` = y'all

But since `U-L` is "you will," I use `KWRAUL` for "you all", which is consistent with the pattern for y'all but not phonetically true.

Note: "Y'all" is **_never, ever_** written as "ya'll" and if you insist on writing it as "ya'll", y'all can just go eat lemons.

## Won't and will not

Technically, "won't" is the contraction for "will not", so the dictionary contains entries for phonetic "won't" and (semi) logical "will not" contracted:

> `HR-PBT` will not  
> `HR*PBT` won't  
> `WO*PBT` won't

Note that the entry `WOPBT` was changed to the word "wont" which, while it's not a commonly-used word anymore, should remain in the dictionary.

## Anything that starts with I
Some default entries use `EU`, some  use `AOEU` ... sigh... resolving the conflicts in this family is a challenge that probably dates back to 1911... this is a work in progress.  For the most part, most entries use `AOEU` for I, but there are some noteable exceptions, such as:

> `EULD` I would (because `AOEULD` is "island" and although there are other entries for "island" I kinda like this one...)
> `EU*LD` I'd (because `*EUD` maps to "Idaho")  
> `AOEUD` I had (because EUD maps to id and just don't get me started whinging on all the variations of I.D. ID id ...)  
> `AO*EUD` I’d

## Double contractions

Fortunately, there are very few double contractions - that is, a root word with two contractions.  They work essentially the same as all other contractions, except you are "tucking" two right-hand endings, and the non-contracted phrase is three words.

`KOU` could
`-PBT` not
`-F` have
`KOUFPBT` could not have
`KO*UFPBT` couldn't've

# HOW TO INSTALL
Simply download _contractions.json_ file, then add it to your Plover dictionaries by clicking the big, round green + button at the bottom of the main screen.  By clicking and dragging, move _contractions.json_ so that it is **higher** priority then _main.json_ and _commands.json_ dictionaries, but either below or above your _user.json_ dictionary file in priority, depending on your preference. 

**DO NOT install the 'annotated dictionary' file.** This is a reference file noting the changes I've made, the entries I've added, the ones that don't have entries yet, and other little comments.  Feel free to refer to it, of course, but don't install it!

# NEED TO DO/FIX/FINISH

- [ ] I'm not happy with the 'I' family of briefs, still stewing on which approach I prefer.  Some existing entries use `EU` for I, some use `AOEU`, there's a number of other bits going on in the "I" family, due to how many potential conflicts can result.
- [ ] Need to add phrases ending with "should" and "would" where they don't already exist (although existing 'd contractions work for phrases ending with should and would, of course)
- [ ] Need to make the "those" family consistent, leaning towards just droping the tucked final `-S` or `Z` and using `THOE` as the root starter brief.
- [ ] Need to finish/fix the following phrase families:  Was, when, where, which, why, couple of other less common contractions.  There are several options for 'was,' I prefer `WA-` as the root, but that creates numerous conflicts, hrm... come back to this!

