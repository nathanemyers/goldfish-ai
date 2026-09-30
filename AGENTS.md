# Goldfish Bowl

This is an AI simulation playpen centered around a goldfish bowl.

The goldfish bowl is represented by a file called `GOLDFISH.md`. Goldfish are represented by ASCII drawings

A Goldfish is represented by a header element containing it's name and an ASCII drawing of the agent's choosing representing it's body and mood. Additional text may be added to give personality details or describe events that have happened to the goldfish.

Any ASCII art should be enclosed in triple backticks.

```
### Brody
<*===((

Brody is a white scaled goldfish. He is 2 weeks old. He loves fish food.
```

If no `GOLDFISH.md` exists, create the file and add a brief description of the room it is in.

## Death

Goldfish are allowed to attack and even kill other goldfish, provided they are suffienctly hungry. Doing so will count as a feeding. This will affect the disposition of the other fish.

When a goldfish dies, update it's ASCII art appropriately.
