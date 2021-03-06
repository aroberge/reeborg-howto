# Controlling the grid visibility

Reeborg's world is defined on a square grid which is normally visible.

![grid world](/images/grid.png)

However, when a background image is used,

![reaching for the stars](/images/stars.png)

or when background tiles are added, they normally hide the grid.

![Rain 1](/images/rain1.png)

For beginners, it might be helpful to always show the grid. This is done
by setting the variable `RUR.state.visible_grid` to a value that evaluates as
`true`.

![Home 1](/images/home1.png)

Sometimes, we want only to show the grid for a limited number of squares.
This is done by setting `RUR.state.visible_grid = RUR.PATH_ONLY` **and** by
having a Javascript array named `RUR.public.path` whose items are arrays
containing the x and y coordinates, `[x, y]`, of the squares which we
want to highlight.

![Step 3 from SK worlds](/images/sk3.png)

When using Python, the name of this array should be `RUR.public['path']`,
since `RUR.public` is a Javascript object who is accessed by Python as though
it is a dict.

Note that, in spite of the name `path`, one could have an array that contains
non-connected grid squares.