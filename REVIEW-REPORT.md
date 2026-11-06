# Appetizers — first-pass conversion review

- Original OneNote pages: 23
- Generated appetizer recipe pages: 32
- Embedded photographs extracted: 5
- Pages with Recipe JSON-LD (preliminary): 22
- Original source text is available in a collapsible section on every generated page.
- **Not yet individually validated against Google Rich Results Test.**
- The original OneNote dates are source-page dates, not necessarily publication dates.
- The converter has not altered the original DOCX.

## Items requiring review

### Jalapeno Poppers
- A second ingredient-only variation appears after the tags; verify before cooking.

### Black Bean Salsa
- No clear preparation instructions found; structured data omitted.
- Incomplete or minimal instructions in the original; check before publishing as a fully specified recipe.

### Baked Brie
- No clear preparation instructions found; structured data omitted.
- Incomplete or minimal instructions in the original; check before publishing as a fully specified recipe.

### Air Fryer Cheese Curds
- Source explicitly warns this recipe was a disaster; warning preserved.

### Air Fryer Cheese Curds Dipping Sauce
- No clear preparation instructions found; structured data omitted.

### Guacamole
- No clear preparation instructions found; structured data omitted.
- Incomplete or minimal instructions in the original; check before publishing as a fully specified recipe.

### Queso dip
- No clear preparation instructions found; structured data omitted.

### Spinach Artichoke Dip
- One of three versions on the same OneNote page.

### Spinach Artichoke Dip — Version 2
- Alternative version; confirm title and intended ingredients.

### Spinach Artichoke Dip — Version 3
- Alternative version; confirm title and intended ingredients.

### Fried Pickles
- No clear preparation instructions found; structured data omitted.
- References a separate tempura batter recipe rather than listing a complete method.

### Cheese Crisps
- No clear preparation instructions found; structured data omitted.
- Incomplete or minimal instructions in the original; check before publishing as a fully specified recipe.

### Nachos
- No clear preparation instructions found; structured data omitted.
- Incomplete or minimal instructions in the original; check before publishing as a fully specified recipe.

### Bread Dip
- No clear preparation instructions found; structured data omitted.

### Mango Salsa
- Likely duplicate of the earlier Mango Salsa entry; retained as a separate draft pending review.
- Potential duplicate; compare dates and decide whether to merge.

### Pimiento Cheese
- No clear preparation instructions found; structured data omitted.

### Sweet & Sour Dipping Sauce
- The dipping-sauce finishing instruction appears later in the shared source page; see original source and linked Crab Rangoons.
- Method is split across the source page; review for completeness.

### Crab Rangoons
- The source page interleaves the dipping-sauce and rangoon methods; check the original if following the complete meal.
- Preparation is interleaved with sauce instructions in the source; review before publishing.

### Shrimp Cocktail
- Original page contains Cocktail Sauce, not instructions for preparing shrimp.

### Tostones (Patacones)
- Dipping-sauce instructions were extracted into a separate linked recipe.

### Mayoketchup Dipping Sauce
- Instructions are located in the original Tostones page; extracted separately.
- The dipping sauce was extracted from the Tostones page.

## Important limitations
- The initial ingredient/instruction separation uses conservative heuristics. Some recipes have mixed notes, variants, or incomplete instructions. Review against the source text before using them for cooking or treating schema as final.
- Images are associated with the OneNote source page where they occur; verify their assignment visually.
- The Crab Rangoons and Tostones sauce splits need particular attention because instructions are interleaved.
- The original two recipe pages are preserved from the previous ZIP.

## Uploading to GitHub
Extract the ZIP. Open the inner `holt-wolfer-cookbook-appetizers` folder. Upload its contents to the root of your existing `recipe-schema-test` GitHub repository, preserving the `recipes/` and `assets/` folders. GitHub should show the new appetizer HTML files under `recipes/` and images under `assets/`. Commit and wait for GitHub Pages to deploy.
## Tags and Served with update
Original OneNote tags and serving suggestions have been added to their main recipe pages when present. Linked serving suggestions use exact title matches or explicit aliases (e.g., bean dip → Costa Rican Black Bean Dip). Review these links; no missing recipe was fabricated. Child recipes split from a main OneNote page do not automatically inherit the parent tags. Search synonyms are illustrative and can be expanded.
