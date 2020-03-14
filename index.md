Receive inspiration from Eno all day, whilst in the stark environs of the
command line!

## Say what?

This project contains [fortune][1] files comprised of Brian Eno's [Oblique
Strategies][2], to display randomly before the prompt in new Terminal windows.

## Examples

- "Turn it upside down"
- "Accept advice"
- "Not building a wall but making a brick"

## Instructions

"Don't be afraid of things because they're easy to do"

```bash
bash < <(curl -s https://raw.github.com/mattonrails/oblique-fortunes/master/get)
```

**DIY**

```bash
brew install fortune
git clone git://github.com/mattonrails/oblique-fortunes.git
cd oblique-fortunes
cp oblique* /usr/local/Cellar/fortune/**/share/games/fortunes/
echo 'if command fortune >/dev/null; then fortune oblique; fi' >> ~/.bash_profile
```

[1]: http://en.wikipedia.org/wiki/Fortune_(Unix) 'Fortune (Unix)'
[2]: http://en.wikipedia.org/wiki/Oblique_Strategies 'Oblique Strategies'