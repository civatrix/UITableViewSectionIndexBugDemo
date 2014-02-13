UITableViewSectionIndexBugDemo
==============================

A demo application to demonstrate a 1 px bug that shows while using index titles and search bar

Excersise the bug by removing or commenting out `sectionIndexTitlesForTableView` in LNViewController.h line 41. I've made the table view background red for contrast to easier see the single pixel gap.

When first booting the app look for a single pixel red line between the search bar and the table. Also, after tapping the search bar to enter search mode look for a red line either below the search bar or above the status bar, it alternates each time you cancel and enter search.

Without section indexs:

![Without section indexes initial](/TableViewTest/WithoutIndexInitial.png)

Without section indexes while searching:

![Without section indexes while searching](/TableViewTest/WithoutIndexSearching.png)

With section indexes:

![With section indexes initial](/TableViewTest/WithIndexInitial.png)

With section indexes while searching (line on top):

![With section indexes while searching line above status bar](/TableViewTest/WithIndexSearchingTop.png)

With section indexes while searching (line on bottom):

![With section indexes while searching line below search bar](/TableViewTest/WithIndexSearchingBottom.png)
