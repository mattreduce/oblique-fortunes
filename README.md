# Oblique Fortunes

Receive inspriration from Eno all day, whilst in the stark environs of the
command line!

## Say what?

This project contains [fortune][1] files comprised of Brian Eno's [Oblique
Strategies][2].

1. You must have the `fortune` program installed
2. Both files must live in a place `fortune` expects
3. You should make the call to `fortune` on "login" from a config file

It will display a random Oblique Strategy before the prompt in new Terminal
windows.

## Examples

- "Turn it upside down"
- "Don't be afraid of things because they're easy to do"
- "Accept advice"
- "Not building a wall but making a brick"

## Instructions

    brew install fortune
    git clone git://github.com/mattonrails/oblique-fortunes.git
    cd oblique-fortunes
    cp oblique* /usr/local/Cellar/fortune/**/share/games/fortunes/
    echo 'if command fortune >/dev/null; then fortune oblique; fi' >> ~/.bash_profile

## Thanks

To Brian Eno for the Oblique Strategies, and of course his music.

To @zeke for inspiration and providing [the strategies][3] in an easy to
process format.

[1]: http://en.wikipedia.org/wiki/Fortune_(Unix) 'Fortune (Unix)'
[2]: http://en.wikipedia.org/wiki/Oblique_Strategies 'Oblique_Strategies'
[3]: https://github.com/zeke/oblique-strategies 'zeke/oblique-strategies'
