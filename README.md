# UltimateDex
The ultimate Pokédex app containing sprites, descriptions, maps, walkthroughs, and location data for all generations of Pokémon.

## Why?
I'm building this app because I love Pokémon and I've been playing since the original games came out all those years ago. I want to bring back those memories and help new players create new memories with the old games as well as the newer ones.

## Tech Stack
Another purpose for building this app is to test myself in some core concepts and technologies for creating iOS apps.

The design pattern and frameworks I will use to build this app are:
- MVVM (Model-View-ViewModel)
- SwiftUI
- Core Data

## Progress
| Gen 1 | Gen 2 | Gen 3 | Gen 4 | Gen 5 | Gen 6 | Gen 7 | Gen 8 | Gen 9 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete | 0/4 Complete |

### Gen 1 Progress (Red, Blue, and Yellow)
| Design🎨 | Build🖥 | Test📱 | Release🥹 |
| --- | --- | --- | --- |
| 1(but actually 0)/7 Complete | 0/5 Complete | 0/4 Complete | 0/4 Complete |

### Gen 1 Design Progress
| Pokédex Screens | Walkthrough Screens | MoveDex Screens | MapDex Screens | App Themes | App Screens | Gather/Create |
| --- | --- | --- | --- | --- | --- | --- |
| ✅All 5 screens designed✅‼️I GUESS NOT... see below‼️ | 1 screen designed, idk how many to go | Not started | Not started | Not started | Not started | Not started |

## Latest Update - Thursday, March 31, 2022
The Pokédex screen designs are finished (nevermind, see notes below). I also updated the type effect area on the Pokémon detail screen. And last, I designed the first Walkthrough screen. You can see those updates and new screen designs below.

![Type Effect Area](/images/typeeffects.PNG)
The data in this section looked a little less unified than I wanted it to, so I added the box and borders. You can see the previous design from yesterday's update below.

![Sprite Screen](/images/spritescreen.PNG)
This screen appears when you tap on the sprite on the Pokémon detail screen. It just shows all versions of the sprite from the specific game you are viewing. Now that I think about it, I should probably have that game selector still hovering at the top. I'll update the design to include that later.

![Pokémon Location Screen](/images/pokemonlocationscreen.PNG)
This screen appears when you tap on View Map in the Pokémon detail screen. The Pokémon party icon from the game would be blinking on every location on the region map that that Pokémon appears, and if you tap on one of them, it will highlight that location in the list of locations below. And I just remembered I was going to have another screen come up when you tap on the locations listed below, so I guess I have one more screen to design in the Pokédex screens.

![Walkthrough Main Screen](/images/walkthroughmainscreen.PNG)
This screen is the main screen that appears when you go to the Walkthrough tab. It allows you to select which part of the game you are at to go to a detailed walkthrough.

## Next Steps
- Finish Pokédex screen designs
    - Pokémon Location Detail screen
    - Update sprite screen and location screen to include game selector
- Design Walkthrough screens

## Previous Updates
### (in reverse chronological order)

### Wednesday, March 30, 2022
Since this is also the first update, I'll talk about my progress up to this point.

I've already finalized the overall content that I want to include in my app, which as you can see from the progress reports above, includes a comprehensive Pokédex for all generations as well as a MoveDex, MapDex, and game walkthroughs. I also mention app themes and app screens.

App themes are going to be unrelated to the functionality or content of the app; they will just be like skins you can apply to make your app look how you want. They will be included to help support the future development of this project.

App screens are just any screen that doesn't really have anything to do with the Pokédex content, such as the Settings screen, the Credits screen, and any other screens that need to be there but aren't really Pokédex stuff.

I use the app Mockup on the iPad to do very rough designs of my screens, and I've designed 3 screens so far, which you can view below.

![Default Pokédex Screen](/images/defaultpokedexscreen.PNG)
This is a pretty simple screen that just shows all the Pokémon in a classic iOS list style. Each list item has the Pokémon's sprite as well as name and types. You can tap on any Pokémon to go to a detail screen.

![Evolution Pokédex Screen](/images/evolutionpokedexscreen.PNG)
This is another version of the above screen, but it shows the Pokémon in their evolutionary chains, as well as the level they normally evolve at. You can still tap on any Pokémon to go to its detail screen.

![Pokémon Detail Screen](/images/pokemondetailscreen.png)
This screen shows up when you tap on a Pokémon from the previous Pokédex screens. It shows all the information about the Pokémon, such as the sprite, game description, stats, evolutions, and moves. You can also switch between viewing the grayscale sprite or the color sprite, and you can play the Pokémon's cry. Tapping on the sprite will bring up a sprite screen where you can see both the front and back of the Pokémon. And tapping on the View Map button in the How To Get section brings up a map of the region with the Pokémon's locations labeled.
