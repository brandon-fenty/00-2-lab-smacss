##### How did you determine which rules should be placed in each new CSS file?

I put the most broad rules into the base file (there were only two, global font as well as body color), the bulk went into layout; the way I sorted those was by determining which parts of the page will be present on every single page of the website (i.e. nav, header, footer, aside), the rest of the content went into the modules file; these were all of the individual components for a specific page instead of the website as a whole.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not, I left all of the CSS rules the same and just sorted them into their coresponding files.
