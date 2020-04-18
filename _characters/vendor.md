---
title: vendor
layout: player_character
character_info:
  name: Supply Model 8 - Unit 256, 'Vendor'
  class: artificer
  class_specialty: artillerist
  race: warforged
  background: guild artisan
  level: 7
  age: unknown
  alignment: Neutral good
  proficiency_bonus: 3
  armor_class: 20
  max_health: 59
  size: medium
  speed: 30 feet
  spellcasting: true
  casting_ability: intelligence
  spell_attack_bonus: 1
  abilities:
    strength: 8
    dexterity: 14
    constitution: 16
    intelligence: 18
    wisdom: 12
    charisma: 8
  proficient_skills:
    - arcana
    - insight
    - investigation
    - perception
    - persuasion
  proficient_saving_throws:
    - constitution
    - intelligence
  disadvantaged_skills:
    - stealth
  other_proficiencies:
    - Thieves' tools
    - Tinker's tools
    - Herbalism kit
    - Woodcarver's tools
    - Smith's tools
    - Carpenter's tools
    - Simple weapons
    - Firearms
    - Light armor
    - Medium armor
    - Shields
  skill_notes:
    - Tool expertise (x2 proficiency bonus when using tools)
    - Advantage vs. being poisoned
    - Resistance to poison damage
    - Immune to disease
    - Magic cannot put to sleep
    - Stealth disadvantage
  class_features:
    - magical tinkering
    - spellcasting
    - ritual casting
    - infuse item
    - the right tool for the job
    - eldritch cannon
    - arcane firearm
    - flash of genius
  racial_features:
    - constructed resilience
    - sentry's rest
    - integrated protection
  background_features:
    - guild business
    - guild membership
  prepared_spell_limit: 7 # intelligence modifier + floor(0.5 * level)
  spell_slots:
    - level: 1
      slots: 4
    - level: 2
      slots: 2
  spells:
    - spell: firebolt
    - spell: mending
    - spell: shield
      prepared: true
      footnote: Always prepared via class specialization.
    - spell: thunderwave
      prepared: true
      footnote: Always prepared via class specialization.
    - spell: scorching ray
      prepared: true
      footnote: Always prepared via class specialization.
    - spell: shatter
      prepared: true
      footnote: Always prepared via class specialization.
    - spell: cure wounds
    - spell: alarm
    - spell: feather fall
    - spell: aid
    - spell: alter self
    - spell: lesser restoration
    - spell: web
    - spell: this doesn't exist
      range/area: does this work?
  money: 15gp
  inventory:
    weapons:
      - item: daggers
        quantity: 2
      - item: light crossbow
        description: lighter than a heavy crossbow
      - item: bolts
        quantity: 20
    spellcasting:
      - item: wand
    armor:
      - item: scale mail
      - item: shield
    tools:
      - item: thieves' tools
      - item: tinker's tools
      - item: herbalism kit
      - item: woodcarver's kit
      - item: smith's tools
      - item: carpenter's tools
    other:
      - item: dungeoneer's pack
      - item: letter of introduction from guild
---

#### Convenient reminders

At-a-glance of reminders.

- Firebolt (cantrip): Ranged spell attack against the target. On a hit, 2d10 fire damage.
- Arcane firearm (dmg modifier): +1d8 damage for artificer attack spells cast w/arcane firearm (wand)
- Eldritch cannon activation (bonus action)
  - HP: 5x(level)
  - Mending: if mending spell is cast on it, it regains 2d6 hit points
  - As part of bonus action, can direct cannon to walk/climb up to 15 feet
  - Cannons:
    - Flamethrower: The cannon exhales fire in an adjacent 15-foot cone that you designate. Each creature in that area must make a dexterity saving throw against your spell save DC, taking 2d8 fire damage on a failed save or half as much on a successful one. The fire ignites any flammable objects in the area that aren't being worn or carried.
    - Force ballista: Make a ranged spell attack, originating from the cannon, at one creature or object within 120 feet of it. On a hit, the target takes 2d8 force damage, and if the target is a creature, it is pushed up to 5 feet away from the cannon.
    - Protector: The cannon emits a burst of positive energy that grants itself and each creature of your choice within 10 feet of it a number of temporary hit points equal to 1d8 + your intelligence modifier.
- Repulsion shield (reaction): The shield has 4 charges. While holding it the wielder can use a reaction immediately after being hit by a melee attack to expend 1 of the shield's charges and push the attacker up to 15 feet away.

#### Infusions

Active infusions

- Enhanced arcane focus (wand)
- Repulsion shield
- Wand sheath

Known infusions (limit of 6 known, limit of maintaining 3 at any one time)

- **Enhanced arcane focus** (item: a rod, staff, or wand; attunement)
  - While holding this item, a creature gets +1 bonus to spell attack rolls. In addition, the creature
    ignores half cover when making a spell attack. (bonus +2 at lvl 10)
- **Enhanced defense** (item: suit of armor or a shield)
  - A creature gains a +1 bonus to armor class while wearing (armor) or wielding (shield) the infused
    item. (bonus +2 at 10th level)
- **Repulsion shield** (item: shield)
  - A creature gains +1 bonus to armor class while wielding this shield
  - The shield has 4 charges. While holding it the wielder can use a reaction immediately after being
    hit by a melee attack to expend 1 of the shield's charges and push the attacker up to 15 feet away.
    The shield regains 1d4 expended charges daily at dawn.
- **Replicate magic item: alchemy jug**
  - Description: This ceramic jug appears to be able to hold a gallon of liquid and weighs 12 points
    whether full or empty. Sloshing sounds can be heard from within the jug, even it it is empty.
  - Usage: you can use an action and name one liquid from the table (below) to cause the jug to produce
    the chosen liquid. Afterward, you can uncord the jug as an action and pour that liquid out, up to
    2 gallons per minute. The maximum amount of liquid the jug can produce depends on the liquid you named.
    Once the jug starts producing a liquid, it can't produce a different one, or more of one that has
    reached its maximum, until the next dawn.
  - Liquids
    - Acid (8 ounces)
    - Basic poison (0.5 ounce)
    - Beer (4 gallons)
    - Honey (1 gallon)
    - Mayonaise (2 gallons)
    - Oil (1 quart)
    - vinegar (2 gallons)
    - Water, fresh (8 gallons)
    - Water, salt (12 gallons)
    - Wine (1 gallon)
- **Replicate magic item: bag of holding**
- **Replicate magic item: wand sheath**
  - Description: A wand sheath clamps onto your arm and imparts the following benefits:
    - The wand sheath can't be removed from you while you're attuned to it.
    - You can insert a wand into the sheath as an action.
    - You can retract or extend the wand from the sheath as a bonus action. While the wand is extended,
      you can use it as if you were holding it, but your hand remains free.


#### Languages

- Common
- Dwarvish (racial)
- Elvish (background)

#### Background: Warforged Supplier's Union (Guild Artisan)

**Business:** Member of the Warforged Supplier's Union (WFSU)

- Former organizer of local-1024. An angry group of human merchants, drove our local chapter out of
  town, spilling the oil of many good warforged and causing the chapter to suspend operations.
- The Warforged Supplier's Union organizes warforged merchants (primarily supplier models, but other
  models are welcome).
  - Prejudice against warforged necessitated unionizing. Rampant ignorance about warforged sentience
    has lead to widespread discrimination, and warforged are often seen as tools rather than as
    full-fledged citizens.
  - Shunned from traditional merchant guilds, warforged merchants started their guild.

#### Persona

- Personality traits
  - I always want to know how things work and what makes people think.
  - Fair pay. I demand fair payment for goods and services.
- Ideals
  - People: I am committed to my fellow warforged and the WFSU, no ideals.
- Bonds
  - The Warforged
- Robo-quirks
  - You don't understand clothing beyond its utility and assume it denotes a person's function.
  - You are obsessed with your appearance and constantly polish and buff yourself.
