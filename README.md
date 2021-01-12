# Plant Water Plan
3 things:
 1) Plant image
 2) Water Level
 3) Water button
    - 0-3: dry
    - 4-8: perfect
    - 9+: overwatered

html setup:
- Button
    - Why? When clicked, will change water level
- Image
    - Why? To give feedback to user about how plant is doing
- Some div
    - To show user current water level

1) Grab DOM elements
    - That means they need ids in html
2) Initialize some state (need to do for anything that will change over time)
    - Water level = 0 - let
3) Add event listener to button. On click:
    - state: water level rises by 1
    - view: change textConent of water level div
    - view: image changes to match current water level
