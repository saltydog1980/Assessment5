### Personal Recipe App
-----
### Base Overview:
- Allows users to input personal recipes into their personal recipe box.
- Query outside APIs for recipe ideas - possibly up to three different APIs each bringing different functionality.
- Allow users to also save selected query recipes to their recipe box.
- query their own recipe box for recipes.


### Models:
- Initially starting with two base models, one for the users and a second for recipes that will have the FK of the user for linkage
- ** May end up breaking out a few more, possibly breaking out ingredients, etc.


### Stretch:
- Ability to take a user's personal recipe and generate nutritional data for it.
- Given a selected recipe and get recommended wine pairing.
- ingredient substitutions.
- Ability to build out a weekly recipe plan (will be a new model for sure) **Possibly be able to break out a shopping list from the recipe plan
- Smart ingredient amount conversions


### Super Stretch:
- Pretty formatting and pdf generation for printing and or sharing.