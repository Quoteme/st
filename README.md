# Luca's Suckless Terminal (st build)

<sub>german: Lucas Lutschwenigerendgerät</sub>

A terminal that does all you want and nothing more.

---

Based on [st](https://st.suckless.org/) technology and these patches:

- [newterm](https://st.suckless.org/patches/newterm/)^[custom version]
	- open new terminals in current folder with CTRL+ENTER
- [scrollback](https://st.suckless.org/patches/scrollback/)
	- scroll in the terminal using your mousewheel
	- [st-scrollback-20200419-72e3f6c.diff](https://st.suckless.org/patches/scrollback/st-scrollback-20200419-72e3f6c.diff)
	- [st-scrollback-mouse-20191024-a2c479c.diff](st-scrollback-mouse-20191024-a2c479c.diff)
	- [st-scrollback-mouse-altscreen-20200416-5703aa0.diff](st-scrollback-mouse-altscreen-20200416-5703aa0.diff)

newterm is implemented in a custom way to allow for support with
scrollback.

---

Start with `st`.

For help, type `man st`

To change the font to [curie](https://github.com/NerdyPepper/curie),
start st with `st -f curie:pixelsize=14`
