[日本語](patchlog_ja.md) | **English** | [한국어](patchlog_ko.md) | [中文](patchlog_zh.md)

# Patch Notes

## v1.2.0

Added a new costume, Tom Nook, along with adjustments to existing costumes.

### New Character

#### 1. Tom Nook (New)

**Stats**: Leaf Drop +50000%

**Starting Item**: Tent

The shrewd tanuki businessman, Tom Nook, joins the battle!

He's a master at gathering Leaf — his Leaf Drop is increased by a whopping +50000%!
You'd think that makes him filthy rich... but it's not that simple.

He starts the game with his exclusive artifact, "Tent".
While holding this artifact, **all Leaf spending is multiplied by 500**! (This applies to shop buy prices and similar costs — sell prices are unchanged.)
On top of that, **your bag is fixed at 2×2, and your sub-bag and potion slots are fixed at 1 each**. Tent life is cramped.

But don't worry!
Once the Leaf you own reaches the expansion cost, the loan is paid automatically and your home gets **expanded**.
Each expansion gives you more bag, sub-bag, and potion slots, boosts the Leaf you pick up, and even comes with a reward!

| Artifact | Bag | Sub-bag | Potions | Leaf Picked Up | Next Expansion Cost | Expansion Reward |
|---|---|---|---|---|---|---|
| Tent | 2×2 | 1 | 1 | ×1 | 98,000 | Restorative Potion ×1 |
| My Home (Stage 1) | 3×3 | 2 | 2 | ×1.22 | 198,000 | Large Restorative Potion ×1 |
| My Home (Stage 2) | 4×4 | 3 | 3 | ×1.54 | 348,000 | Dice ×2 |
| My Home (Stage 3) | 5×5 | 4 | 4 | ×1.90 | 548,000 | Random Common Stone Tablet ×1 |
| My Home (Stage 4) | 6×6 | 5 | 5 | ×2.15 | 758,000 | Random Advanced Stone Tablet ×1 |
| My Home (Stage 5) | 7×7 | 6 | 6 | ×3.00 | 1,248,000 | Random Rare Stone Tablet ×1 |
| My Home (Stage 6) | 8×8 | 7 | 7 | ×5.20 | 2,498,000 | A special effect |
| My Home (Stage 7) | 9×9 | 8 | 8 | ×6 | — | — |

Expand all the way and pay off the loan to unlock the special effect of "My Home (Stage 7)".
**Right-click** My Home in your bag to pay Leaf and receive **the same reward choice you get on level up**!
The first use costs 1,000,000 Leaf, and the cost rises by 1,000,000 with each use.

Note that this artifact **cannot be disabled**. Even at a negative level or on a disabling slot, its effects keep going. There's no escaping the loan.

He also comes with his own attack motion right from the start!

### Balance Adjustments

#### 1. My Melody (Adjustment)

**Stat Change**: Curse of Healing +70% → +60%

**Artifact "Cute Notes"**:
- Melody Buff duration 2s → 1.5s

We've eased her Curse of Healing a little, making it easier to recover HP.
In exchange, Melody Buff now runs out sooner, so keeping your stacks up takes a bit more attacking than before.

#### 2. Sans (Buff)

**Artifact "Just Ketchup"**:
- All elemental damage -14 → -12
- Added: on a successful evasion, become invincible for 0.5s and restore 10% MP
- Added: immunity to fall damage

We've softened the elemental damage penalty to give his damage a small boost.

On top of that, a successful evasion now makes him briefly invincible and restores some MP!
The more you dodge, the better things get — just the way he likes to fight.

Also, with only 1 HP, simply falling into the abyss meant an instant game over for him.
To prevent these accidental deaths, he no longer takes fall damage.

#### 3. Kirby (Nerf)

**Stat Change**: Negotiation -60 → -80

**Artifact "Copy Star"**:
- Added flavor text

Copy Star turned out to be extremely powerful, so we've lowered his Negotiation even further to balance things out.
Shopping is now harder than ever for him, but the Copy ability itself is unchanged.

### Other

- **Updated ModMaker Runtime to v2.5.35**: To match this version, ModMaker Runtime has been updated to v2.5.35. If your Runtime is older than v2.5.35, the mod may not work correctly. In that case, please download and install the version that includes Runtime (`-withRuntime.zip`).
- **About multiplayer**: Tom Nook has not been tested when used by a non-host player in multiplayer. If you run into any issues, a report would be greatly appreciated.

## v1.1.0

Added a new costume, Kirby, along with adjustments to existing costumes and a new feature.

### New Character

#### 1. Kirby (New)

**Stats**: Max Fruit Skewers +8 / Negotiation -60

**Starting Item**: Copy Star

The Pink Demon himself, Kirby, joins the battle!

Being quite the big eater, he wants to eat plenty of fruit too — so his max Fruit Skewers increases by a whopping 8!

However, he's not great at talking (or, well, can he even talk?), so his Negotiation stat takes a big hit... oh well.

He also starts the game with a powerful artifact, "Copy Star"!
This artifact recreates his signature ability — Copy!

Copy Star copies the ability of the artifact placed below it!
Some artifacts won't do anything useful when copied, but most will still trigger their effect.
For example, you can double up Captain Mole, or cast an extra grimoire with the Watering Can!

### Balance Adjustments

#### 1. My Melody (Rework)

**Stat Change**: Added Curse of Healing +70%

**Reworked artifact "Cute Notes"**:
- Removed the fixed HP heal on gaining a buff stack
- Added: each Melody Buff stack now grants +1 HP Regen
- Added a new attack motion

Her artifact wasn't behaving as intended, so we decided to rework it!

Since each Melody Buff stack now grants +1 HP Regen, she can reach up to 88 HP Regen at max stacks — an incredibly powerful healing tool!

However, we felt this would be far too strong on its own, so we've added a sizable Curse of Healing to keep things balanced.

Ever felt like something was missing while playing her?
That's right — an attack motion!

Previously added characters didn't have their own attack motions, but this time we've given My Melody one!

Stay tuned for attack motions for the other existing characters in future patches.

#### 2. Dummy-chan (Buff)

**Stat Change**: Dash Recovery Speed +150% → +220%

Playing as her was just too difficult, so we've made a small adjustment.
(Though... she's a training dummy — why can she dash so much in the first place?)

### Other

- **Added an update notification feature**: The game will now notify you on launch if a newer version of this mod is available! No more missing a new patch!
- **Updated ModMaker Runtime to v2.5.32**: To match this version, ModMaker Runtime has been updated to v2.5.32. If your Runtime is not v2.5.32, the mod may not work correctly. In that case, please download and install the version that includes Runtime (`-withRuntime.zip`).

## v1.0.0

New costumes added! The following 3 new costumes have been added.

### 1. My Melody

**Stats**: Luck +18 / Critical Chance -120%
**Starting Item**: Cute Notes

My Melody, wearing her adorable hood, joins the battle!

She starts with a whopping +18 Luck, along with her powerful original artifact, "Cute Notes"!

This artifact grants a chance to gain a "Melody Buff" on attack — each stack increases attack speed by 1%.
Since the buff can stack up to 88 times, this single artifact can grant up to +88% attack speed!
It also heals a fixed amount of HP whenever you gain a Melody Buff stack.

However, as the price for wielding such a powerful artifact, her Critical Chance is reduced by -120%, making it nearly impossible to land a critical hit.

### 2. Sans

**Stats**: HP fixed at 1 / Toughness -9999999 / Evasion +100 / Invincibility bonus during dash +0.2s
**Starting Items**: Thunder's Judgment / Just Ketchup

Sans, the skeleton who loves jokes and ketchup, joins the battle!

In the original game, his stats were HP1 / AT1 / DF1 — we recreated that here in Sephiria.
His HP is fixed at 1, and his original artifact "Just Ketchup" fixes his AT and DF (all elemental damage and defense) at 1.

But don't worry!
Any elemental damage above 1 is converted into fixed damage, meaning raising any elemental damage stat will boost his power (though we've lowered the base values of all elemental damage stats to keep things balanced).
Any defense beyond the fixed value is converted into Evasion.

He also gains bonus Evasion and extra invincibility time during dashes — this is meant to reflect his signature ability to dodge attacks flawlessly (22 times, if you know, you know).

Just like in the original, he starts the game already having his special move, Thunder's Judgment, ready to use!
"I've always thought — why doesn't anybody start with their special attack?"

As for why his Toughness is -9999999... if you know how his story ends, no further explanation needed.

### 3. Dummy-chan

**Stats**: Movement Speed -100% / Dash Recovery Speed +150%

Enough with just standing there getting hit! Sephiria's very own training dummy, Dummy-chan, joins the battle!

She starts with -100% Movement Speed, meaning she can't move on her own (it'd be weird if a dummy could walk, right?).

But without any way to move, you couldn't even start the game, let alone clear it!
So her only means of movement — dashing — recovers dramatically faster (even though a dummy dashing is a bit of an odd sight).

### Other

New costumes currently don't have unique attack animations yet. These are planned for a future patch — stay tuned!
