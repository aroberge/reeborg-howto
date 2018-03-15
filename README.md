# reeborg-howto
Tips and tricks for creating worlds (aka programming tasks) for Reeborg's World

There is very little material right now in this repository. This file will
be used as an index.

If something is not clear, or you cannot find what you are looking for,
either contact me by email or file an issue.

* testing emojis :key: :memo: :information_source: :no_entry_sign: :no_entry: :x: :heavy_check_mark: :heavy_exclamation_mark: :white_check_mark:
:large_blue_circle: :red_circle: :large_orange_diamond: :negative_squared_cross_mark: :recycle: :warning: :construction: :trophy: :star: :smiley:

## Essentials

You should be familiar with the topics here before reading other sections.

* About Reeborg's World

* Two ways to create worlds _aka_ programming tasks

* The various editors

* [The advanced API](https://aroberge.github.io/reeborg-api/RUR.html) and its [naming convention](src/naming_convention.md)

* Opinion: what makes a good world

    - Clear task
    - Automatic feedback
    - Good description
    - Visual appeal
    - Language agnostic
    - Potentially adding randomness

## Classroom tips

* [Keeping track of progress](src/user_progress.md)

## How to ...?

* [Control the grid visibility](src/visible_grid.md)

* ... require Reeborg to follow a fixed path

* ... add new objects, with different properties

* ... add new robot images

* ... use randomness

    - Built-in using the graphical world editor
    - Using Python's random module
    - Using `RUR.randint()`

* ... create language-agnostic worlds

    - Usable with either Javascript or Python
    - Usable with all human languages
        * Some limitations



## Appendices

* Reeborg's philosophy

    - Why not OOP?
    - Why repeat?
    - Task driven learning

* [Support for different languages](src/international.md)

* [Checklist for a programming environment](src/checklist.md)

* [Real-time collaboration using Mozilla's TogetherJS](src/togetherjs.md)