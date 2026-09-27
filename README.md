# Cairn character creator

Open `index.html` in a modern browser. The app is one self-contained file: no installation, build, server, fonts, or network connection required.

Follow the random tables one step at a time. Review previous chapters, swap two ability scores, choose weapons and bonus-table branches, and manage the ten-slot inventory. On the final screen, choose **Print / Save as PDF**, then your browser's **Save as PDF** destination. Use A4 portrait (or fit to Letter) and disable browser headers and footers.

Progress is saved in this browser's local storage when available. **Start over** replaces the saved character after confirmation. Printing requires finishing creation; the PDF includes the character, equipment, spell description if applicable, notes, and core play references.

## Source and rules decisions

Transcribed from the supplied `Cairn.pdf`, first edition, especially printed pages 4–9, 11–12, and 16–18. Includes all ten trait tables, all seven starting-gear tables, and all 100 spells. This implements the random starting-gear procedure; the optional class-like gear packages are outside this flow.

- Ability scores: 3d6 in STR, DEX, WIL order, with one optional pair swap.
- HP: 1d6; age: 2d20 + 10; gold: 3d6.
- Armor is capped at 3 and only counts carried items marked worn/held. One suit, helmet, and shield may contribute.
- Bulky gear occupies two slots. At ten personal slots, current HP is zero; excess gear must be left behind or put in a rolled cart.
- A cart takes two personal slots, provides four storage slots, and needs both hands to pull. Slot placement and small-item bundling remain subject to the Warden.
- Starting gold is treated as pocket-sized. Longbow uses the equipment list's bow profile (d6, bulky); Battleaxe uses the heavy-weapon profile (d10, bulky).
- Spell descriptions are matched by name because Command and Comprehend have transposed numbers between the PDF's table and description pages.

Cairn is by Yochai Gal: https://cairnrpg.com/. Its text is licensed under CC BY-SA 4.0. This unofficial adaptation is also made available under CC BY-SA 4.0: https://creativecommons.org/licenses/by-sa/4.0/.
