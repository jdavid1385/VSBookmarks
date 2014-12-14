#VSBookmarks

**VSBookmarks is a numeric bookmarks extension for Visual Studio.**

<img style="float: left; margin-right: 20px" src="https://raw.github.com/SergeyVinyar/VSBookmarks/master/README_img/screenshot.png">

Provides up to nine enumerated bookmarks for every text editor tab. All of them are accessible by shortcuts or via a context-menu (right-click and see for VSBookmark submenu).

* **Ctrl-Shift-[1..9]** - set, change or remove a bookmark (you will see an appropriate digit on the left margin of the editor area);
* **Ctrl-[1..9]** - go to a previously set bookmark.

If some of these shortcuts are already used by any other global commands VSBookmark won't be able to hook them. In this case the following wiil help:
1. go to Tools -> Customize -> <Keyboard...> button;
2. type in a filter “VSBookmarks” (without quotes);
3. choose a command that relates to unavailable shortcut;
4. assign a shortcut.

If you use Visual Studio with default settings no additional actions are required.