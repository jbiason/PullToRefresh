Fork of the original `code by Sonny Parlin <https://github.com/sonnyparlin/PullToRefresh>`_.

Additions:

Colors
    All colors are now configurable. The default ``initWithScrollView:`` still works as
    before, but there is a new ``initWithScrollView:backgroundColor:`` allowing to start
    with a different background color for the pull area and 
    ``initWithScrollView:backgroundColor:textColor:shadowColor:`` to configure background 
    color, text color and text shadow color.

Strings
	All strings are now localizable. So if you add PullToRefresh to a project in a different
	language, you don't need to change the text directly. Adding new translations requires
	adding Localized.strings in the project languages, as 
	`described in this article <http://forums.macrumors.com/showthread.php?t=373834>`_.