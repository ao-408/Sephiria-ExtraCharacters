[日本語](patchlog_ja.md) | **English** | [한국어](patchlog_ko.md) | [中文](patchlog_zh.md)

# Patch Notes

**From v2.0.0 onward, the mod itself is available exclusively on [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3843151213).** Nexus Mods and GitHub provide information and update news.

## v2.0.0

Crewmate joins the tower!
This update also adds our first weapons: **Pocky and Buster Sword**, alongside new animations and balance changes.

**This is now a standalone mod requiring no ModMaker Runtime, with the mod itself distributed through Steam Workshop.** Read the [installation instructions](README_en.md#installation) before updating.

### New Character

#### 1. Crewmate

**Stats**: Attack Speed +20% / Damage dealt outside meetings −60%

**Starting Item**: Emergency Meeting Button / 緊急会議ボタン

Ditching his spaceship tasks, Crewmate has arrived at the tower!

Press the button for a **10-second Emergency Meeting**. Participants are invincible! ...But violence is frowned upon, so ordinary damage dealt during meetings is reduced by 99%.

Each hit on an enemy adds one vote, with no vote cap. When voting ends, **the single enemy with the most votes is ejected**. A tie means no ejection.

An **Impostor** hides among the enemies, secretly attacking them. Once only Impostors remain, they reveal themselves and go wild!

- **Eject an Impostor and you're a hero!** The remaining enemies also take damage based on its vote count. Outside boss and miniboss encounters, the button's cooldown is reduced by 80%.
- **Eject an innocent enemy and...** all participants are stunned for 3.5 seconds.
- **Bosses and minibosses** survive ejection with at least 1 HP. Instead, they take damage based on votes, and the cooldown is reduced by 50%.

Ejection damage scales with your highest elemental damage and artifact damage bonuses.
A **team-wide 9-second wait** follows the meeting, preventing players from taking turns to keep meetings going.
The button also cannot be used within two slots of the bag's edge. Ship buttons belong in the middle!

His ordinary damage is modest, but **voting and ejection damage are exempt from the outside-meeting −60% penalty**.
Why fight with fists when you can fight with meetings?

In multiplayer, players holding an Emergency Meeting Button join the same meeting.

### New Weapons

#### 1. Pocky

**How to obtain**: Enhance “Divine Iron Staff” at an anvil (tier-3 staff).

The snack has finally become a weapon!

- **Your special attack is Eat!** Finish the remaining Pocky to restore HP and gain Attack Speed and Basic Attack Damage. Longer Pocky gives bigger bonuses: a full stick restores 3.5% of Max HP and grants +25% Attack Speed and +20% Basic Attack Damage for 8 seconds.
- Every 12 successful basic or dash attacks, it gets shorter: full → 3/4 → 1/2 → 1/4 → empty. Range decreases with length. When empty without an active eating buff, Basic Attack Damage is reduced by 30%.
- Melee range at 100% / 75% / 50% / 25% / 0% length is **+35% / +18% / 0% / −18% / −35%**, respectively.
- When empty, a fresh stick is taken from your stock if available.

Restock with a **Pocky Box箱**, sold by merchants: **34 sticks for a fixed 220 Leaf**, unaffected by Negotiation. Only Pocky owners can buy one.

Enhancing into Pocky grants **one box** as a gift. Obtaining or enhancing it in training does too.
The box has its own opening animation. Even Pocky fans don't eat the packaging!

#### 2. Buster Sword

**How to obtain**: Enhance “Hypersensitivity” at an anvil (tier-3 greatsword).

A big sword deserves a big moment! Build the Limit Gauge through attacks and damage taken, then unleash four different techniques.

- Every 100 gauge is one level, up to four levels. Hits generate damage dealt ×0.1, capped at 25 per hit.
- **Hold the special attack to charge at 45 per second.** You cannot move while charging, but it works outside combat.
- With at least one level, **tap the special attack to use the technique for your current level**. It spends the entire gauge and grants invincibility while active.

| Level | Technique | Effect |
|---|---|---|
| 1 | Cross-Slash | Close in for three slashes, stunning on the final hit. |
| 2 | Blade Beam | Fire a forward shockwave that also damages enemies around its impact. |
| 3 | Finishing Touch | Lift nearby enemies in a tornado, then launch them away. |
| 4 | Omnislash | Teleport through 15 slashes, followed by an area finisher. All hits are critical! |

The gauge appears beside the Mana Gauge and also below your character when it changes.
See each technique's in-game tooltip for detailed effects and damage.

Melee attack range is increased by 15%.

### Animations and Controls

- Added dedicated attack animations for Sans and Dummy-chan and corrected some unnatural motion.
- **Every costume now has all of its animations!** Future costumes will also be completed before release.
- Added **Extra Characters →** to character selection to open the mod's character list. With a mod character selected, selection starts on the mod page.

### Balance Adjustments

#### ![1. Sans (Adjustment━)](images/balance/headings/en/01.png)

**Starting Item**: Removed Broken Sapphire.

**Previously omitted change**: Dash invincibility bonus +0.2s → +0.3s.

We forgot to document the added Sapphire and changed invincibility bonus last time. Sorry!
The powerful starting artifact is going away, but the +0.3s bonus stays.

#### ![2. Kirby (Nerf▼)](images/balance/headings/en/02.png)

**Stats**: Fruit Skewer cap bonus +8 → +6 / Added bag slots −3.

Still a big eater, but now packing takes a little more thought!

**Ability Star**

- While copying, Ability Star hides its own base description and displays the source artifact's effects.
- Copied effects use Ability Star's own level, capped at the copied ability's maximum. The source artifact's level does not determine their strength.
- **Placement conditions and weapon restrictions are copied too**, and checked at Ability Star's position and equipment.
- Positional abilities, such as Compass of Breakthrough and Giant Telescope, work from **both the original artifact's position and Ability Star's position**.
- Hovering over Ability Star highlights the artifact below it with a pink frame.

#### ![3. Dummy-chan (Buff▲)](images/balance/headings/en/03.png)

**Stats**: Added Defense +20.

Despite how difficult she is to play, her stat bonuses were not particularly strong compared with other characters.
To give her a distinct identity as someone who can take a hit, we have added a Defense bonus.

### Bug Fixes

- **Ability Star**: Fixed level labels left behind after moving, stale maximum levels after removing or replacing the source.
- **Ability Star**: Fixed missing minus signs and bullets in copied effect descriptions.
- **Ability Star**: Fixed refresh and cleanup of positional effects. Moving the copy preserves the original artifact's effects.
- **Ability Star**: Reduced processing overhead by removing per-frame effect-text generation and additional full-inventory recalculations.
- **Character selection and presets**: Fixed added characters disappearing or appearing as “?” in presets.
- **Translations**: Fixed other descriptions failing to appear when only a name was translated.

- **Just Ketchup**: Fixed successful evasion failing to grant 0.5s invincibility and restore 10% MP.
- **Tent / My Home**: Fixed guest expansion displays, some Leaf-cost facilities working with insufficient funds, and purchasing bag expansions.
- **Descriptions**: Corrected mismatches and missing details, including Melody Buff's duration.
- **Update notifications**: Fixed issues such as repeated notices.

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

#### ![1. My Melody (Adjustment━)](images/balance/headings/en/04.png)

**Stat Change**: Curse of Healing +70% → +60%

**Artifact "Cute Notes"**:
- Melody Buff duration 2s → 1.5s

We've eased her Curse of Healing a little, making it easier to recover HP.
In exchange, Melody Buff now runs out sooner, so keeping your stacks up takes a bit more attacking than before.

#### ![2. Sans (Buff▲)](images/balance/headings/en/05.png)

**Artifact "Just Ketchup"**:
- All elemental damage -14 → -12
- Added: on a successful evasion, become invincible for 0.5s and restore 10% MP
- Added: immunity to fall damage

We've softened the elemental damage penalty to give his damage a small boost.

On top of that, a successful evasion now makes him briefly invincible and restores some MP!
The more you dodge, the better things get — just the way he likes to fight.

Also, with only 1 HP, simply falling into the abyss meant an instant game over for him.
To prevent these accidental deaths, he no longer takes fall damage.

#### ![3. Kirby (Nerf▼)](images/balance/headings/en/06.png)

**Stat Change**: Negotiation -60 → -80

**Artifact "Ability Star"**:
- Added flavor text

Ability Star turned out to be extremely powerful, so we've lowered his Negotiation even further to balance things out.
Shopping is now harder than ever for him, but the Copy ability itself is unchanged.

### Other

- **Updated ModMaker Runtime to v2.5.35**: To match this version, ModMaker Runtime has been updated to v2.5.35. If your Runtime is older than v2.5.35, the mod may not work correctly. In that case, please download and install the version that includes Runtime (`-withRuntime.zip`).
- **About multiplayer**: Tom Nook has not been tested when used by a non-host player in multiplayer. If you run into any issues, a report would be greatly appreciated.

## v1.1.0

Added a new costume, Kirby, along with adjustments to existing costumes and a new feature.

### New Character

#### 1. Kirby (New)

**Stats**: Max Fruit Skewers +8 / Negotiation -60

**Starting Item**: Ability Star

The Pink Demon himself, Kirby, joins the battle!

Being quite the big eater, he wants to eat plenty of fruit too — so his max Fruit Skewers increases by a whopping 8!

However, he's not great at talking (or, well, can he even talk?), so his Negotiation stat takes a big hit... oh well.

He also starts the game with a powerful artifact, "Ability Star"!
This artifact recreates his signature ability — Copy!

Ability Star copies the ability of the artifact placed below it!
Some artifacts won't do anything useful when copied, but most will still trigger their effect.
For example, you can double up Captain Mole, or cast an extra grimoire with the Watering Can!

### Balance Adjustments

#### ![1. My Melody (Rework━)](images/balance/headings/en/07.png)

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

#### ![2. Dummy-chan (Buff▲)](images/balance/headings/en/08.png)

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
**Starting Items**: Judgment of Thunder / Just Ketchup

Sans, the skeleton who loves jokes and ketchup, joins the battle!

In the original game, his stats were HP1 / AT1 / DF1 — we recreated that here in Sephiria.
His HP is fixed at 1, and his original artifact "Just Ketchup" fixes his AT and DF (all elemental damage and defense) at 1.

But don't worry!
Any elemental damage above 1 is converted into fixed damage, meaning raising any elemental damage stat will boost his power (though we've lowered the base values of all elemental damage stats to keep things balanced).
Any defense beyond the fixed value is converted into Evasion.

He also gains bonus Evasion and extra invincibility time during dashes — this is meant to reflect his signature ability to dodge attacks flawlessly (22 times, if you know, you know).

Just like in the original, he starts the game already having his special move, Judgment of Thunder, ready to use!
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
