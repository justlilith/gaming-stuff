# Pathfinder Notes

## What's this for?

I noticed I've been relying on d20pfsrd for referencing different parts of my character's abilities, skills, etc., and the game itself. However, I'd end up with like 20 extra open tabs per session, so I thought it would be a good idea to collate just the relevant stuff for my character (and their place in the campaign).

Markdown is an easy way for me to structure pages, and then Git lets me reference my notes from any device with a browser.

## What's next?

I think it'd be really neat to build a processor for d20pfsrd that will build these pages automatically; e.g.:

```bash
pfgen --add feat 'Eschew Materials' 'Lightning Reflexes' 'Weapon Finesses (Combat)' 'Xenoglossy'
pfgen --add weapon 'dagger (masterwork)' 'Crossbow (light)'
```

And you'd have a nice, sourced block of markdown with all the details available from d20pfsrd. Something like that would be helpful.

Also, what about quickly searching for an entry?

```bash
pfgen --search 'adder strike'
> Results:
> [1] Adder Strike (Combat): Feat
> [2] Pinpoint Poisoner (Combat): Feat
> ...

pfgen --search 'adder strike' --display 1
> Adder Strike (Combat): Feat
> 'You can quickly apply poison to gloved hands, protected...'
> 'Prerequisites: Poison use class feature...'
```

I think this would be pretty useful.
