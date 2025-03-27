# Conky-Theme
A nice and aesthetic conky theme ;)
> This theme is only for screens with a resolution of 1080x720 px.
#

<p align="center">
  <a href="#">
  </a>
  
  <p align="center">
  Another Conky Theme
    <br />
    <a href="#"><strong>Install</strong></a>
    <br />
  </p>
</p>

<img src="https://github.com/Yisusdev2005/Conky-Theme/blob/main/486250506_1149384040204431_1789737642810540295_n.jpg" width="100%"/>

> I was inspired by some of the themes I saw

# How can I add it to my desktop?
First things first, you must follow these simple steps:

- First download both themes, then create a folder called <code>.conky</code> in your <code>home</code> directory.

- Use the autostart directory and create a <code>.desktop</code> file at <code>~/.config/autostart/</code>:

<pre><span class="token function">mkdir</span> <span class="token parameter variable">-p</span> ~/.config/autostart  <span class="token comment"># If the directory does not exist</span>
<span class="token function">nano</span> ~/.config/autostart/conky.desktop</pre>

- Paste this content (adjust the paths if you used others):

<pre>[Desktop Entry]
Type=Application
Name=Conky
Exec=sh -c "conky -c ~/.conky/conky-theme1.conf & conky -c ~/.conky/conky-theme2.conf &amp;"
StartupNotify=false
Terminal=false</pre>

> This script is so that every time you log in to your distro, it also starts conky at startup.

- Finally, test by entering each theme separately in the terminal to make sure they work correctly:

<pre>conky <span class="token parameter variable">-c</span> ~/.conky/conky-theme1.conf  <span class="token comment"># Only system</span>
conky <span class="token parameter variable">-c</span> ~/.conky/conky-theme2.conf  <span class="token comment"># Only music</span></pre>

> I hope my customized theme caught your attention ;)
