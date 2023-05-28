# First Steps
Now this may sound silly, but using a kids program to start learning programming is actually pretty smart.

Yup, you might have already guessed it but we are going to start by using [Scratch](https://scratch.mit.edu).

The scope of Scratch is too broad for me to all explain here, so i got some
useful links for you here:

- [Basics](https://pinnguaq.com/learn/scratch-basics-episode-1/)
    - [Chapter 2](https://pinnguaq.com/learn/scratch-basics-episode-2/)
    - [Chapter 3](https://pinnguaq.com/learn/scratch-basics-episode-3/)
    - [Chapter 4](https://pinnguaq.com/learn/scratch-basics-episode-4/)

I then recommend this:
- [Scratch Wiki - If block](https://en.scratch-wiki.info/wiki/If_()_Then_(block))

Now that you got all that, you are ready to make your own game! Don't know what a block does or how to do something?
Look it up! Programming is not something you learn completely by book, but by trying, making mistakes, and looking
stuff up!

## Example game
```haskell
when green flag clicked
forever [
    glide (5 seconds) to (random position)
    if <<touching (mouse pointer)> and <mouse down>> then [
        say (You found me!)
        stop [all]
    ]
]
```