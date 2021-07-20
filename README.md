# What is mtg-term?
It is a minimalistic, open-source, mtg-like game, made in python, that can be played on most terminal emulator on linux.
The first goal to be realistic in scope, is to have a playable single player game, with simple generated card, that have simple [__Keyword ability__](https://mtg.fandom.com/wiki/Keyword_ability) effect. Then once completed, add complexity progressivelly, and maybe in the far long distant future a form of multiplayer.

![Magic](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwallup.net%2Fwp-content%2Fuploads%2F2016%2F04%2F10%2F315469-Magic_The_Gathering-fantasy_art-heroes-warrior.jpg&f=1&nofb=1)

## Project state:

Incomplete, In development

# Help Needed!
I really want to play an mtg-like alternative game on linux, so please do your best to contribute if you can!
This project only accept clear, organized and well commented code.
You can also submit suggestion and idea, as long as they are unambiguous and well developed.

![WE NEED YOU](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fau.edu%2Fsas%2Fimages%2FSAS%2520Volunteer%2520sign11.jpg&f=1&nofb=1)

# Main Game View
 
 ~~~
 Turn: [Player_name_one]
 Phase: [Beginning/Untap Step] 

 ▶️ [Player_name_one]: Health[20] Deck[60]
 
 Hand:  🔳🔳🔳🔳🔳🔳🔳[7] 
 Graveyard: 💀[0]
 
 Mana:  🟪 ⬛⬛
 Field: 🟫🟫 ⬛
        🗡️
        🛡️        
 Field: 🟫🟫🟫
 Mana:  🟪🟪 ⬛
 
 Graveyard: 💀[6]
 Hand:  🟧🟫🟪🟫🔍🟧[6]
 
 [Player_name_two]: Health[20] Deck[60]
 
 -[Info]----------------------
 Name: [Lorem Ipsum]
 Cost: 🔵🔵🔵[3] 🚫🚫[2]
 Type: Creature
 Effect: [ ... ]
 P&T: [1/1]
 ~~~
 
 # Graveyard View
  
 ~~~
 [Player_name_one] 
 Graveyard: 🟧🟫🟪🟫🔍🟧[6]
 Field: ⚔️
 
 -[Info]----------------------
 Name: [Lorem Ipsum]
 Cost: 🔵🔵🔵[3] 🚫🚫[2]
 Type: Creature
 Effect: [ ... ]
 P&T: [1/1]
 ~~~
  
 
 
 # Symbols emoji and therm used
 
 ~~~
 Symbols:
 Tapped ⬛
 Artefact Or Enchantment ⬜
 Creature 🟫
 Instant or Sorcery 🟧
 Cursor/Slection 🔍
 Colorless +
 Attacking 🗡️
 Blocking 🛡️
 Colorless 🚫
 Mana card 🟪
 Back 🔳
 
 Therm: P&T = Power and Taughness
 ~~~
 
 # Info on phase and stuff
 ~~~
 https://www.youtube.com/watch?v=V4rYwsBMKxs
 Phase: beginning, first_main, combat, second_main, ending
 Steps: Beginning(Untap, Draw) Main(Land, Spells) Combat(Attackers, Blockers, damage) Second(Land, Spells) Ending(Cleanup)
 ~~~
 


