# Todo List

* SRD Content
  * [] Race
  * [] Class
  * [] Abilities
  * [] Backgrounds
  * [] Equipment
  * [] Spells
  * [] Feats
  * [] Bio
  * [] Review

* [x] Template format
* [x] Pipe inputs into backend
* [] Integration with existing compendiums
* [] Allow for custom races etc without compendium entries
* [x] Button to open Conjurer
  * [] Integrate into *Create Actor*
  * [x] Add temporary button
* [ ] Pipe inputs into character sheet
* [ ] Prettify HTML
* [ ] Compatibility with alternate sheets (probably just Sky5e)
* [ ] Licensing under 5e SRD rules
* [ ] Allow for localization

* Flow
  * User interacts with template, which determines input data
    * Use a socket to connect template to JS?
    * Button onClick initiates script to pass in relevant data, into the correct template
  * Each tab get its own template, with the same button templates

* Data Model
  * Race
    * [x] Subrace
    * [x] Size
    * [x] Speed
    * [x] Language
    * [] Racial Feats
    * [x] *Add* ability bonuses to total ability scores (including possible subrace bonuses)
  * Class
    * [] Weapon prof
    * [] Armor prof
    * [] Skill prof
    * [] Class feats
    * [] Starting equipment
    * [] Hit die
  * Abilities
    * [x] Input scores
    * [x] Add/remove points
    * [] *Add* ability bonuses to total ability scores
    * [] Give option for different point systems
  * Background
    * [] Skill prof
    * [] Language prof
    * [] Personality traits
    * [] Ideal
    * [] Bond
    * [] Flaw
    * [] Equipment
  * Equipment
    * [] Choose equipment or starting wealth
  * Spells
    * [] Cantrips
  * Feats
    * [] Feats
  * Bio
    * [x] Name
    * [x] Age
    * [x] Height
    * [x] Weight
    * [x] Eyes
    * [x] Hair
    * [x] Skin
  * Gather data and pipe into character sheet