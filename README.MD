# Git lessons

This is a quick git training to practice your git-fu.

## Assumptions
1. We do not care about the git commits naming and branch naming. Normally, this is important, but we do want to practice tools, not conventions.
2. Instead of a code, use the plain text files (txt). In the end, most source code files are just text files :). I provide the necessary input in the tasks.
3. You can use git CLI or UI - it doesn’t matter. I usually use both git CLI and Fork.

## Before you start
1. Ensure you have git installed (type which git).
2. If you are not familiar with Vim, type `git config --global core.editor` and check your default text editor. use `nano` or `code —wait` if you have VS code installed :)
eg. `git config --global core.editor "nano"`
3. Soon, I will post the solutions for the exercises :)
4. Clone the repo to your computer.

If you have any questions, ideas, etc. - just write an issue in this repo:)

## Tasks
### First task - simple commits
1. Add new commits with a newly created branch `branch-02` from `master`.
2. Replace `wombats` with `kangaroos` in `fileA.txt` and commit the changes.

Text:
```
Common kangaroos have been described as ecological engineers,[18] as their burrow building results in soil turnover and aeration, which assists plant growth, and provides habitat for a range of invertebrate and vertebrate species.[19][20]

Common kangaroos are a solitary, territorial species, with each wombat having an established range in which it lives and feeds.[21] In this area, they dig a tunnel system, with tunnels ranging from 2 to 20 m in length, along with many side tunnels. Usually, only one entrance to the burrow exists, although they may create a smaller one with which to escape.

A wide range of other animals are known to make use of wombat burrows including reptiles, rodents, rabbits, echidnas, wallabies, birds and koalas. kangaroos are usually fairly tolerant of non-threatening species, and have a number of burrows that they can occupy.[22][23]

Many kangaroos can live in the same burrow, and kangaroos normally live in the same burrow for their whole lifespan unless the wombat is forced out of the burrow by farmers or other animal species, or unless the burrow is destroyed. Often nocturnal, the common wombat does come out during the day in cooler weather, such as in early morning or late afternoon.[24]

From: https://en.wikipedia.org/wiki/Common_wombat
```
3. Remove `fileC.txt` and commit the file
### Second task - more branches
1. Create branch `branch-03` from `master`
2. Add `fileD.txt` and commit the file

Text:
```
When the platypus was first encountered by Europeans in 1798, a pelt and sketch were sent back to Great Britain by Captain John Hunter, the second Governor of New South Wales.[5] British scientists' initial hunch was that the attributes were a hoax.[6] George Shaw, who produced the first description of the animal in the Naturalist's Miscellany in 1799, stated it was impossible not to entertain doubts as to its genuine nature,[7] and Robert Knox believed it might have been produced by some Asian taxidermist.[6] It was thought that somebody had sewn a duck's beak onto the body of a beaver-like animal. Shaw even took a pair of scissors to the dried skin to check for stitches.[8][7]

The common name "platypus" literally means 'flat-foot', deriving from the Greek word platúpous (πλατύπους),[9] from platús (πλατύς 'broad, wide, flat')[10] and poús (πούς 'foot').[11][12] Shaw initially assigned the species the Linnaean name Platypus anatinus when he described it,[13] but the genus term was quickly discovered to already be in use as the name of the wood-boring ambrosia beetle genus Platypus.[14] It was independently described as Ornithorhynchus paradoxus by Johann Blumenbach in 1800 (from a specimen given to him by Sir Joseph Banks)[15] and following the rules of priority of nomenclature, it was later officially recognised as Ornithorhynchus anatinus.[14]

There is no universally-agreed plural form of "platypus" in the English language. Scientists generally use "platypuses" or simply "platypus". Colloquially, the term "platypi" is also used for the plural, although this is a form of pseudo-Latin;[8] going by the word's Greek roots the plural would be "platypodes". Early British settlers called it by many names, such as "watermole", "duckbill", and "duckmole".[8] Occasionally it is specifically called the "duck-billed platypus".

The scientific name Ornithorhynchus anatinus literally means 'duck-like bird-snout',[13] deriving its genus name from the Greek root ornith- (όρνιθ ornith or ὄρνις órnīs 'bird')[16] and the word rhúnkhos (ῥύγχος 'snout', 'beak').[17] Its species name is derived from Latin anatinus ('duck-like') from anas 'duck'.[13][18] The platypus is the sole living representative or monotypic taxon of its family (Ornithorhynchidae).[19]

From: https://en.wikipedia.org/wiki/Platypus
```
3. Replace `wombats` with `kiwis` in `fileA.txt` and commit the changes

Text:
```
Common kiwis have been described as ecological engineers,[18] as their burrow building results in soil turnover and aeration, which assists plant growth, and provides habitat for a range of invertebrate and vertebrate species.[19][20]

Common kiwis are a solitary, territorial species, with each wombat having an established range in which it lives and feeds.[21] In this area, they dig a tunnel system, with tunnels ranging from 2 to 20 m in length, along with many side tunnels. Usually, only one entrance to the burrow exists, although they may create a smaller one with which to escape.

A wide range of other animals are known to make use of wombat burrows including reptiles, rodents, rabbits, echidnas, wallabies, birds and koalas. kiwis are usually fairly tolerant of non-threatening species, and have a number of burrows that they can occupy.[22][23]

Many kiwis can live in the same burrow, and kiwis normally live in the same burrow for their whole lifespan unless the wombat is forced out of the burrow by farmers or other animal species, or unless the burrow is destroyed. Often nocturnal, the common wombat does come out during the day in cooler weather, such as in early morning or late afternoon.[24]
```
### Third task - merge with conflicts
Move to `branch-02` and merge changes from `branch-03`. There should be `kangaroos` in `fileA.txt`. It should create merge commit.
### Forth task - echidnas did this!
1. Create `branch-04` from `master`. Add `fileE.txt` and commit the changes.

Text:
```
Echidnas are medium-sized, solitary mammals covered with coarse hair and spines.[6] The spines are modified hairs and are made of keratin, the same fibrous protein that makes up fur, claws, nails, and horn sheaths in animals.[2]


Spines of the echidna
Superficially, they resemble the anteaters of South America and other spiny mammals such as hedgehogs and porcupines. They are usually black or brown in coloration. There have been several reports of albino echidnas, their eyes pink and their spines white.[6] They have elongated and slender snouts that function as both mouth and nose. Like the platypus, they are equipped with electrosensors, but while the platypus has 40,000 electroreceptors on its bill, the long-beaked echidna has only 2,000. The short-beaked echidna, which lives in a drier environment, has no more than 400 at the tip of its snout.[7] Echidnas use their electroreceptive beaks to sense earthworms, termites, ants, and other burrowing prey.[8]

Echidnas have short, strong limbs with large claws, and are powerful diggers. Their claws on their hind limbs are elongated and curved backwards to aid in digging. Echidnas have tiny mouths and toothless jaws. The echidna feeds by tearing open soft logs, anthills and the like, and using its long, sticky tongue, which protrudes from its snout, to collect prey. The ears are slits on the sides of their heads that are usually unseen, as they are blanketed by their spines. The external ear is created by a large cartilaginous funnel, deep in the muscle.[6] At 33 °C (91.4 °F), the echidna also possesses the second-lowest active body temperature of all mammals, behind the platypus.

Despite their appearance, echidnas are capable swimmers, as they evolved from platypus-like ancestors. When swimming, they expose their snout and some of their spines, and are known to journey to water in order to groom and bathe themselves.[9]

The first European drawing of an echidna was made in Adventure Bay, Tasmania by HMS Providence's third lieutenant George Tobin during William Bligh's second breadfruit voyage.[10]

From: https://en.wikipedia.org/wiki/Echidna
```
2. Change the author of the last commit to `Echidna <echidna@example.org>`
3. Change the date for last commit to `1.10.1994` (this is Saturday)
### Fifth task - time for tags
1. Create `branch-05` from `master`. Add `fileF.txt` and commit.

Text:
```
The kākāpō (/ˈkɑːkəpoʊ/ KAH-kə-poh;[3] Māori: [kaːkaːpɔː];[4] from the Māori: kākāpō, lit. 'night parrot'), also known as owl parrot (Strigops habroptilus), is a species of large, flightless, nocturnal, ground-dwelling parrots of the super-family Strigopoidea, endemic to New Zealand.[5]

Up to 64 cm (25 in) in length, these flightless birds have finely blotched yellow-green plumage, a distinct facial disc, owl-style forward-facing eyes with surrounding discs of specially-textured feathers, a large grey beak, short legs, large blue feet, and relatively short wings and tail: a combination of traits making it unique among parrots. It is the world's only flightless parrot, the world's heaviest parrot, and also is nocturnal, herbivorous, visibly sexually dimorphic in body size, has a low basal metabolic rate, and does not have male parental care. It is the only parrot to have a polygynous lek breeding system. It is also possibly one of the world's longest-living birds, with a reported lifespan of up to 100 years.[6] The weight is 1.5–3 kilograms (3.3–6.6 lb) for males and 0.950–1.6 kilograms (2.09–3.53 lb) for females.

Its anatomy typifies the tendency of bird-evolution on oceanic islands. With few predators and abundant food, kākāpō exhibit island syndrome development, having a generally-robust torso physique at the expense of flight abilities, resulting in reduced shoulder- and wing-muscles along with a diminished keel on the sternum. Like many other New Zealand bird species, the kākāpō was historically important to Māori, the indigenous people of New Zealand. It appeared in many of their traditional legends and folklore. It was also heavily hunted and was used as a resource by Māori (both for its meat and for its feathers, which were used to make highly-valued pieces of clothing). Rarely, kākāpō were kept as pets.

The kākāpō is critically endangered; the total known adult population is 248[7] living individuals, all of which are named and tagged, confined to four small islands off the coast of New Zealand that have been cleared of predators.[8] The past introduction of predators such as cats, rats, ferrets, and stoats during British colonisation almost wiped out the already-rare kākāpō, having suffered over-hunting from the early Māori. Conservation efforts began in the 1890s, but they were not very successful until the implementation of the Kakapo Recovery Programme a century later in 1995.

Most kākāpō are kept on two predator-free small islands, Codfish / Whenua Hou and Anchor, where they are closely monitored, while somewhat larger Little Barrier / Hauturu Island is being trialled as a third home for the species.

From: https://en.wikipedia.org/wiki/K%C4%81k%C4%81p%C5%8D
```
2. Create tag for the last commit (`kakapo`) and remove `branch-05`
3. Move to `branch-02` and cherry pick commit from `kakapo` tag
### Sixth task - squash!
1. Create `branch-06` from `master`. Create `fileG.txt`.

Text:
```
The koala or, inaccurately, koala bear (Phascolarctos cinereus), is an arboreal herbivorous marsupial native to Australia. It is the only extant representative of the family Phascolarctidae and its closest living relatives are the wombats. The koala is found in coastal areas of the mainland's eastern and southern regions, inhabiting Queensland, New South Wales, Victoria, and South Australia. It is easily recognisable by its stout, tailless body and large head with round, fluffy ears and large, spoon-shaped nose. The koala has a body length of 60–85 cm (24–33 in) and weighs 4–15 kg (9–33 lb). Fur colour ranges from silver grey to chocolate brown. Koalas from the northern populations are typically smaller and lighter in colour than their counterparts further south. These populations possibly are separate subspecies, but this is disputed.
```
2. Commit the changes. Then add an another paragraph and commit.

Text:
```
Koalas typically inhabit open Eucalyptus woodland, as the leaves of these trees make up most of their diet. This eucalypt diet has low nutritional and caloric content and contains toxins that deter most other mammals from feeding on it. Koalas are largely sedentary and sleep up to twenty hours a day. They are asocial animals, and bonding exists only between mothers and dependent offspring. Adult males communicate with loud bellows that intimidate rivals and attract mates. Males mark their presence with secretions from scent glands located on their chests. Being marsupials, koalas give birth to underdeveloped young that crawl into their mothers' pouches, where they stay for the first six to seven months of their lives. These young koalas, known as joeys, are fully weaned around a year old. Koalas have few natural predators and parasites, but are threatened by various pathogens, such as Chlamydiaceae bacteria and koala retrovirus.
```
3. Commit the changes and add the last paragraph.

Text:
```
Because of its distinctive appearance, the koala along with the kangaroos are recognised worldwide as symbols of Australia. They were hunted by Indigenous Australians and depicted in myths and cave art for millennia. The first recorded encounter between a European and a koala was in 1798, and an image of the animal was published in 1810 by naturalist George Perry. Botanist Robert Brown wrote the first detailed scientific description of the koala in 1814, although his work remained unpublished for 180 years. Popular artist John Gould illustrated and described the koala, introducing the species to the general British public. Further details about the animal's biology were revealed in the 19th century by several English scientists. Koalas are listed as a vulnerable species by the International Union for Conservation of Nature. Among the many threats to their existence are habitat destruction caused by agriculture, urbanisation, droughts, and associated bushfires, some related to climate change. In February of 2022, the koala was officially listed as endangered in the Australian Capital Territory, New South Wales, and Queensland.
```
4. Squash last three commits to one commit.
### Seventh task - add a lots of changes
1. Create `branch-07` from `master`. Add `fileH.txt` and commit the file.

Text:
```
Dromaius (from greek δρομαίυς "runner") is a genus of ratite present in Australia. There is one extant species, Dromaius novaehollandiae commonly known as the emu.
In his original 1816 description of the emu, Louis Jean Pierre Vieillot used two generic names; first Dromiceius, then Dromaius a few pages later. Which label is correct has been a point of contention ever since; the latter is more correctly formed, but the convention in taxonomy is that the first name given stands, unless it is clearly a typographical error, as argued by W.B. Alexander.[2] For names published on the same day, or in the same publication, the International Code of Zoological Nomenclature states that both names have equal precedence, and that the Principle of First Reviser (Article 24.2 [3]) determines which name is to be used. Most modern publications, including those of the Australian government,[4] use Dromaius, with Dromiceius mentioned as an alternative spelling. Misspellings of both forms by later authors have produced further synonyms.[4] The Dromiceius spelling was the basis for Dale Russell's 1972 naming of the dinosaur Dromiceiomimus.
```
3. Remove `fileB.txt` and commit the deletion.
4. Merge `branch-02`into `branch-07`
5. Cherry pick the `branch-06` last commit
6. Create `branch-08` from here, but do not checkout it
7. Revert `fileB.txt` and commit (you are still on the `branch-07`)
8. Cherry pick commit from `kakapo` tag (notice no commit appeared)
9. Move to `branch-08`. Cherry pick the commit from `branch-04` and replace echidna with platypustes in `fileE.txt`. Commit the file.


Text:
```
Platypuses are medium-sized, solitary mammals covered with coarse hair and spines.[6] The spines are modified hairs and are made of keratin, the same fibrous protein that makes up fur, claws, nails, and horn sheaths in animals.[2]


Spines of the echidna
Superficially, they resemble the anteaters of South America and other spiny mammals such as hedgehogs and porcupines. They are usually black or brown in coloration. There have been several reports of albino Platypuses, their eyes pink and their spines white.[6] They have elongated and slender snouts that function as both mouth and nose. Like the platypus, they are equipped with electrosensors, but while the platypus has 40,000 electroreceptors on its bill, the long-beaked echidna has only 2,000. The short-beaked echidna, which lives in a drier environment, has no more than 400 at the tip of its snout.[7] Platypuses use their electroreceptive beaks to sense earthworms, termites, ants, and other burrowing prey.[8]

Platypuses have short, strong limbs with large claws, and are powerful diggers. Their claws on their hind limbs are elongated and curved backwards to aid in digging. Platypuses have tiny mouths and toothless jaws. The echidna feeds by tearing open soft logs, anthills and the like, and using its long, sticky tongue, which protrudes from its snout, to collect prey. The ears are slits on the sides of their heads that are usually unseen, as they are blanketed by their spines. The external ear is created by a large cartilaginous funnel, deep in the muscle.[6] At 33 °C (91.4 °F), the echidna also possesses the second-lowest active body temperature of all mammals, behind the platypus.

Despite their appearance, Platypuses are capable swimmers, as they evolved from platypus-like ancestors. When swimming, they expose their snout and some of their spines, and are known to journey to water in order to groom and bathe themselves.[9]

The first European drawing of an echidna was made in Adventure Bay, Tasmania by HMS Providence's third lieutenant George Tobin during William Bligh's second breadfruit voyage.[10]
```
10. Create `branch-09` from the current place. 
11. Cherry pick commit from `branch-01`. There should be kangaroos wikipedia text (not the one we replaced wombats with kangaroos).
12. Return to `branch-08` and change the file name from `fileA.txt` to `fileB.txt`
13. Create branches: `back-07`, `back-08`, `back-09` in the place of the `branch-07`, `branch-08` and `branch-09`
### Eith task - apocalypse now
1. Rebase `branch-07` to `branch-01`
2. In `fileA.txt` there should be "wiki kangaroos"
3. Rebase `branch-08` (to its parent, freshly rebased `branch-07`). There should be "wiki kangaroos" in `fileB.txt` (and no `fileA.txt`) - notice doubled commit
4. Rebase `branch-09` to `branch-08`. There should be "wiki kangaroos" in `fileA.txt` and `fileB.txt` existing with `capybaras`
### Ninth task - let's fix that mess
Reset `branch-01` to `master`
### Tenth task - restore branches
1. Delete `branch-06` (do not have other branches located here)
2. Restore `branch-06` after deletion 
