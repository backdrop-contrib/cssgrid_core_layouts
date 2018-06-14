CSS Grid for Core's Layouts
===========================

Ever wanted to use CSS Grid because you can, but don't want to mess up older browsers? Have no fear, this module *adds* a little CSS to make all multicolumn layouts from Backdrop core use CSS Grid.

For any browser that can use grid, they'll get grid layout (only in multi-column areas) instead of flexbox, and of course if they can't support flexbox they'll get float based layouts.

### Why do this?

Because I can! CSS Grid can work out a lot better than flexbox for page layout (it depends), but only ~75% of the users on the internet have browsers that support it. Eventually a better version of this CSS *might* be what's in Backdrop core, but for now it's here, for funsies.

To learn how CSS Grid works, I recommend:
* https://cssgridgarden.com/
* https://gridbyexample.com
* https://css-tricks.com/snippets/css/complete-guide-grid/

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- Wes Ruvalcaba (https://github.com/wesruv)
