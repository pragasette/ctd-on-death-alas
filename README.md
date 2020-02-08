# CTD On Death, Alas

A mod for [The Elder Scrolls V: Skyrim][Skyrim] to quit the game when health
reaches zero.

> _The literal definition of "It's not a bug, it's a feature!"_  
> – [/u/StoneOfLight][#1]

Made on [request][#2].


## Requirements

- [The Elder Scrolls V: Skyrim][Skyrim].

## Installation

- Use your mod manager of choice, [Mod Organizer 2] is recommended.

## Known Issues

- This technically doesn't _crash_ to desktop, it exits gently using an
  [existing function of the game scripting language][QuitGame].

## TODO

- Turn it into a [SKSE] plugin to make the process actually crash, by trying
  to access an invalid memory address, or employing more advanced techniques.


[Skyrim]: https://elderscrolls.bethesda.net/en/skyrim
[#1]: https://www.reddit.com/r/skyrimmods/comments/f0kda6/mod_request_ctd_on_death/fgutvwq/
[#2]: https://www.reddit.com/r/skyrimmods/comments/f0kda6/mod_request_ctd_on_death/
[Mod Organizer 2]: https://www.nexusmods.com/skyrimspecialedition/mods/6194
[QuitGame]: https://www.creationkit.com/index.php?title=QuitGame_-_Debug
[SKSE]: https://skse.silverlock.org/
