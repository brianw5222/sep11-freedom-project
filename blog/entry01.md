# Entry 1
##### 10/23/23

The tool I pick is Kaboom.js and I am going to make a platform game that you try to go to the end. Something I learn is:

    kaboom() = This start the game
    setGravity(#) = This gives you gravity
    loadBean() = Makes a character
    const player = add([ = New chacter
        sprite("name"),  = name
        pos(x, y),       = position
        area(),          = how big
        body(),          = responds to object
        ])
    onKeyPress("space", () => { = key to do something
        // .jump() is provided by the body() component
        player.jump() = tells the player what to do
        })

This is the basic things that you have to to start playing and adding the game.

[Next](entry02.md)

[Home](../README.md)