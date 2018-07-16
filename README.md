PYMUMBLE python library
=======================

STOP! You're looking for [azlux's pymumble](https://github.com/azlux/pymumble)
------------------------------------------------------------------------------

The **pymumble** that is most maintained is azlux's fork. This fork is a custom
fork created for [nv-moba](https://github.com/CosineGaming/nv-moba).

What is this?
-------------

I needed Mumble support in Godot for my game. I achieved this by using pymumble
and python godot bindings. However, there is a problem: pymumble keeps checking
if the parent thread is alive, and godot-python lies and says it's dead. So I
stopped pymumble from checking that, and needed to use git submodules, so I have
pushed my code here.

[The original API explanation](API.md).

License
-------
Copyright Robert Hendrickx <rober@percu.be> - 2014

`pymumble` is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
