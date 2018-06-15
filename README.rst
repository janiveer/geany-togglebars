Geany Toggle Bars plugin
========================

This is a plugin for `Geany`__
to show and hide the menu bar with a keystroke.

__ http://geany.org/

Forked from the `Geany Toogle Bars`__ plugin by Vasiliy Faronov.

__ https://github.com/vfaronov/geany-togglebars

Installation
------------

#. Install Geany 1.27+.

#. Make sure that "Show status bar"
   (Geany preferences → Interface → Miscellaneous)
   is **enabled**.

#. Install `GeanyPy`__.
   On Debian/Ubuntu, install ``geany-plugin-py``
   `as well as`__ ``python-gtk2``.

#. Put ``togglebars.py`` on your `Geany plugin path`__,
   e.g. in ``~/.config/geany/plugins/``.

#. Open Geany's plugin manager (Tools → Plugin Manager)
   and enable GeanyPy and Toggle Bars.

#. Select Toggle Bars, click Keybindings,
   and set your preferred key for "Toggle menu bar".

__ http://plugins.geany.org/geanypy.html
__ https://bugs.launchpad.net/ubuntu/+source/geany-plugins/+bug/1592928
__ http://www.geany.org/manual/current/index.html#plugins
