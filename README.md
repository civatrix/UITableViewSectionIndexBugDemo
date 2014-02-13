UITableViewSectionIndexBugDemo
==============================

A demo application to demonstrate a 1 px bug that shows while using index titles and search bar

Excersise the bug by removing or commenting out `sectionIndexTitlesForTableView` in LNViewController.h line 41.
When first booting the app look for a single pixel red line between the search bar and the table.

With section indexs:

![Screenshot](/TableViewTest/WithIndex.png)

Without section indexs:

![Screenshot](/TableViewTest/WithoutIndex.png)
