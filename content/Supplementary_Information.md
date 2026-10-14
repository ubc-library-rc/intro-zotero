---
 layout: default
 title: "Supplementary Information " 
 nav_order: 19
---
# Supplementary Information
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Quick Search[\#](https://www.zotero.org/support/searching#quick_search)

Quick searches provide a fast way to find items in a library or
collection.

## Running a Quick Search[\#](https://www.zotero.org/support/searching#running_a_quick_search)

To begin searching, click inside the search box at the top-right of the
center pane (or type Ctrl/Cmd-F) and start typing your search terms. As
you type, only those items in the center column that match the search
terms will remain.

<img src="images/dc5c0012134400f6ada3f1ce8b6b14254f10e29b.png"
style="width:6.5in;height:1.39583in" />

## Quick Search Options[\#](https://www.zotero.org/support/searching#quick_search_options)

Quick search can be used in three different modes:

- “Title, Year, Creator” - matches against these three fields, as well
  as publication titles

- “All Fields & Tags” - matches against all fields, as well as tags and
  text in notes

- “Everything” - matches against all fields, tags, text in notes, and
  indexed text in PDFs

<img src="images/5c79b2f126c854c353b3a46c6ed2c93c1274a5bb.png"
style="width:6.5in;height:1.76042in" />

## Speeding Up Quick Searches[\#](https://www.zotero.org/support/searching#speeding_up_quick_searches)

By default, the quick search searches automatically as you type. In very
large libraries, this can result in a slow search experience. To speed
things up, type a quotation mark (") mark at the beginning of the search
field. This causes the search to start only when you type Enter/Return.

<img src="images/c82d9a605888f76604c3a5723e636db44c7efd70.png"
style="width:6.5in;height:3.125in" />

# Advanced Search[\#](https://www.zotero.org/support/searching#advanced_search)

Advanced searches offer more and finer control than quick searches, and
allow you to make [saved searches](#saved-searches-1).

## Running an Advanced Search[\#](https://www.zotero.org/support/searching#running_an_advanced_search)

To open the Advanced Search window, click on the magnifying glass icon
(<img src="images/88dd5b774b9cce15d0a045113647281911a24f60.png"
style="width:0.29171in;height:0.26045in" />) at the top of the center
pane and select “Advanced Search”. In this window, you can filter items
by the content of specific fields or by other properties, like item type
or the collection an item belongs to. Multiple filters can be set up by
clicking the plus button.

Set the library to search in by using the “Search in library:” option at
the top of the window. It is not currently possible to search in
multiple libraries at one time.

By default, items only show up in the search results if they satisfy all
search criteria. To change the search so that all items matching at
least one criterion are returned, change the “Match” option to “any”.

You can filter items by the collections or saved searches they belong to
by searching by “Collection”. To include items in subcollections of
matching collections in the search results, check “Search
subcollections”.

To hide non-matching parent items with child items that do match the
search criteria, and to collapse matching parent items with matching
child items, check “Show only top-level items”.

To match search criteria against both parent items and their children,
check “Include parent and child items of matching items”. If this option
is selected and “Match” is set to “all”, parent/child items will still
show up if just part of the criteria is met by the parent item and the
other part by a child item.

<img src="images/5573ec8a495e07d8c34955d39136803080c23aba.png"
style="width:6.5in;height:2.58333in" />

## Wild Cards[\#](https://www.zotero.org/support/searching#wild_cards)

The % percent sign character acts as a wild card in advanced searches,
substituting for zero or more characters. For example, the search term
“W% Shakespeare” will match “W Shakespeare”, “W. Shakespeare” as well as
“William Shakespeare”.

To search for items where a field contains any content at all, search
for the % percent sign character alone.

## Saved Searches[\#](https://www.zotero.org/support/searching#saved_searches)

When you save an Advanced Search, it appears as a collection in your
library but with a Saved Search icon
(<img src="images/058b1136f01e35f19c0c48bed04ffcb80ad683b2.png"
style="width:0.23962in;height:0.20836in" />) instead of the regular
collection icon
(<img src="images/0d0bf49bf38ec83b3a0ddcec799b9c2168e96649.png"
style="width:0.21878in;height:0.17711in" />). Saved Searches are
continuously updated. For example, if you set up a Saved Search for
“Date Added” “is in the last” “7” “days”, the saved search will always
show the items that have been added in the last 7 days. Saved searches
only store the search criteria, not the search results. To save a
search, click the “Save Search” button in the Advanced Search window and
provide a name for the search.

<img src="images/d236223e56621c755df0ab87f9c32cbde94ce31e.png"
style="width:6.5in;height:3.35417in" />

Saved searches can be edited or deleted by right-clicking the Saved
Search and selecting “Edit Saved Search…” or “Delete Saved Search…”,
respectively.

<img src="images/2efa7386fb474c445d2006ad8642733de4dfbe9e.png"
style="width:5.49035in;height:4.13599in" />

You can also create a saved search in a library by right-clicking on the
library name and choosing “New Saved Search…”.

<img src="images/1b4b054ada8e5fd52022a06711e87e4e6b74d4c8.png"
style="width:4.3131in;height:3.42756in" />

## Complex Search Criteria[\#](https://www.zotero.org/support/searching#complex_search_criteria)

It is possible to run complex Boolean searches by using multiple Saved
Searches. For example, to run the search (a OR b) AND (c OR d), first
make a Saved Search called “Condition1” for (a OR b), then make a Saved
Search called “Condition2” for (c OR d). Finally, run a third Advanced
Search and search for "Collection" "is" "Condition1" AND "Collection"
"is" "Condition2".

# Full-Text Indexing[\#](https://www.zotero.org/support/searching#full-text_indexing)

Full-text indexing allows embedded text within PDFs, EPUBs, HTML, and
text files to be searched with Quick Search (via the “Everything”
option) and Advanced Search (via “Attachment Content”). Indexing happens
automatically in the background when Zotero is idle.

<img src="images/7a4f97f64a2173dc6d9f33bedf3eab8a1c372b55.png"
style="width:6.5in;height:3.6875in" />

You can control how much text in a PDF/EPUB/HTML/text file is indexed in
the [<u>Search
pane</u>](https://www.zotero.org/support/preferences/search) of
[<u>Zotero preferences</u>](https://www.zotero.org/support/preferences)
(default: 500000 characters, 100 pages). You can remove indexed text
with the “Clear Index…” button or re-create the index from scratch using
the “Rebuild Index…” button. You can check the index status of any
PDF/EPUB/HTML attachment by selecting the attachment item in the Zotero
library and looking at the “Indexed:” field in the right pane.

If an item isn’t being indexed (e.g., if it is not showing up in an
‘Everything’ Quick Search), verify that the item has searchable text and
that the text is properly stored in the PDF (e.g., try to copy text out
of the document and ensure that it is high quality). If the PDF has
valid text, rebuild the item’s index by right-clicking on it and
choosing “Reindex Item”. If you are still having issues, please ask a
question on the [<u>Zotero forums</u>](https://www.zotero.org/forum).

<img src="images/28366de762ba3ab319316d8db2e6b967e6a0c831.png"
style="width:6.5in;height:4.09375in" />Note: At this time, only
PDF/EPUB/HTML full text content (and plain text files) can be indexed by
Zotero. Other document types (e.g., .docx, .odt) cannot be indexed by
Zotero.

# Sorting

Items in the center pane can be sorted by various fields, such as their
title, creators, or the date they were added to your library.

To change the way items are sorted, click on any of the column headers
at the top of the center pane. For example, if you click on “Title”, all
your items will be sorted alphabetically by title. Clicking a header
multiple times toggles between ascending and descending sorts. (The
header will show an upward and downward arrow, respectively.)

By default, Zotero will show columns for the Title, Creators, and
Attachments properties in the center pane. You can change which fields
are shown by right-clicking on the column headers and selecting fields
from the drop-down menu.

For each column, you can also choose the Secondary Sort field (the field
that’s used to break ties when sorting).

By default, fields in the center pane are arranged from left to right in
the order in which they are shown in the drop-down menu. You can
rearrange them by dragging and dropping the headers. To reset the order,
select “Restore Column Order” in the drop-down menu.

# Quick Copy[\#](https://www.zotero.org/support/creating_bibliographies#quick_copy)

If you just want to quickly add references to a paper, email, or blog
post, Zotero’s Quick Copy is the easiest way to go. Simply select items
in the center column and drag them into any text field. Zotero will
automatically create a formatted bibliography for you. To copy citations
instead of references, hold down Shift at the start of the drag.

To configure your Quick Copy preferences, open the Zotero
[<u>settings</u>](https://www.zotero.org/support/kb/preferences) and
select
[<u>Export</u>](https://www.zotero.org/support/preferences/export). From
this tab you can do the following:

- Select the export format
- Set up site-specific export settings
- Choose whether you want Zotero to include HTML markup when copying

<img src="images/e7c75fd756f43bc61baf8947f3959dc8690db876.png"
style="width:6.5in;height:5.125in" />

You can also use Edit → Copy Bibliography or press Ctrl/Cmd-Shift-C to
copy bibliography entries to your system clipboard and then paste them
into documents. To copy citations instead of bibliography entries, use
Edit → Copy Citation or Ctrl/Cmd-Shift-A.

In addition to bibliographic output, Quick Copy also supports export
formats such as BibTeX and RIS.

<img src="images/e08353bd95fa0d4e77026e0fd41e4fd105002ab8.png"
style="width:6.5in;height:3.08333in" />

# Right-Click to Create Citation/Bibliography[\#](https://www.zotero.org/support/creating_bibliographies#right-click_to_create_citationbibliography)

To create a bibliography or a citations list in Zotero, highlight one or
more items, right-click them, and select “Create Bibliography from
Item(s)…”. Then select a citation style for your citation/bibliography
format and choose either to create a list of *Citations/Notes* or a
*Bibliography*. Then choose one of the following four ways to create
your citation/bibliography:

- *Save as RTF* will save the bibliography as a rich-text file.

- *Save as HTML* will save the bibliography as an HTML file for viewing
  in a web browser. This format will also embed metadata allowing other
  Zotero users viewing the document to capture bibliographic
  information.

- *Copy to Clipboard* will copy the bibliography to your clipboard for
  pasting into any text field.

- *Print* will send your bibliography straight to a printer.

<img src="images/949f8a07afd6999f06084c6e002b961cd8899ac1.png"
style="width:6.5in;height:4.59375in" />

# Citation Styles

Zotero ships with several popular citation styles for [<u>creating
citations and
bibliographies</u>](https://www.zotero.org/support/creating_bibliographies),
and over 10,000 additional styles can be found in the [<u>Zotero Style
Repository</u>](https://www.zotero.org/styles). All these styles are
written in the [<u>Citation Style
Language</u>](https://citationstyles.org/) (CSL), a format also
supported by many other programs.

## Zotero Style Repository[\#](https://www.zotero.org/support/styles#zotero_style_repository)

You can install styles from the Zotero Style Repository by going to the
Cite pane of the Zotero settings and clicking on the “Get additional
styles…” option in the [<u>Zotero Style
Manager</u>](https://www.zotero.org/support/preferences/cite). Search
for the style you want and click the style title to install it into
Zotero. You can also visit the [<u>Zotero Style
Repository</u>](https://www.zotero.org/styles) webpage in your browser
with the Zotero Connector installed to install styles directly into
Zotero.

The repository allows you to search by style name and filter by style
type and academic field of study. By checking the box “Show only unique
styles”, duplicate styles that share the exact same format are hidden
(e.g., for the journal-specific styles “Nature”, “Nature Biotechnology”,
“Nature Chemistry”, etc., only the *independent* “Nature” style is
shown).

## Alternative Installation Methods[\#](https://www.zotero.org/support/styles#alternative_installation_methods)

You can also install CSL styles (with a “.csl” extension) from local
files on your computer (e.g., styles that you edit yourself or that you
download from another website). In the [<u>Zotero Style
Manager</u>](https://www.zotero.org/support/preferences/cite), click the
‘+’ button, then find the style file on your computer.

## Managing and Editing Styles[\#](https://www.zotero.org/support/styles#managing_and_editing_styles)

You can remove installed styles by clicking the ‘-’ button in the
[<u>Zotero Style
Manager</u>](https://www.zotero.org/support/preferences/cite). From this
tab, you can also preview style output for the selected items in Zotero
and [<u>edit installed
styles</u>](https://www.zotero.org/support/dev/citation_styles).

## Reporting Style Errors[\#](https://www.zotero.org/support/styles#reporting_style_errors)

If a CSL style doesn’t give the expected output, first make sure that
you are running the latest version of Zotero and have the most recent
version of the style installed from the [<u>Zotero Style
Repository</u>](https://www.zotero.org/styles). Once you have made sure
that the style deviates from the style guide, instructions for authors,
or published examples, report the error in the [<u>Zotero
Forums</u>](https://www.zotero.org/forum). For your post, use the title
“Style Error: \[Name of style\]”, and give a link to, or excerpt from,
the style guide that shows that the CSL style is wrong. You can also try
to [<u>edit the
style</u>](https://www.zotero.org/support/dev/citation_styles/style_editing_step-by-step)
yourself.

## Requesting New Styles[\#](https://www.zotero.org/support/styles#requesting_new_styles)

If you can’t find the style you’re looking for in the [<u>Zotero Style
Repository</u>](https://www.zotero.org/styles), feel free to [<u>request
a
style</u>](https://github.com/citation-style-language/styles/wiki/Requesting-Styles).
When requesting styles, please provide formatted references for the
Campbell/Pedersen article and the Mares chapter listed on the linked
page. Please also provide a link to a free-to-access article using the
style (if available). You can also try to [<u>create the
style</u>](https://www.zotero.org/support/dev/citation_styles) yourself.

# Importing Your Library from Other Reference Managers

It’s easy to migrate your data from other reference management tools to
Zotero. Instructions for popular tools are linked below.

- [<u>Mendeley</u>](https://www.zotero.org/support/kb/mendeley_import)

- [<u>EndNote</u>](https://www.zotero.org/support/kb/endnote_import)

- [<u>Citavi</u>](https://www.zotero.org/support/kb/import_from_citavi)

- [<u>Microsoft Word Bibliography
  XML</u>](https://www.zotero.org/support/kb/importing_formatted_bibliographies)

- [<u>Plain text reference
  lists</u>](https://www.zotero.org/support/kb/importing_formatted_bibliographies)

- [<u>Bib(La)TeX</u>](https://www.zotero.org/support/kb/importing_standardized_formats)

- [<u>JabRef</u>](https://www.zotero.org/support/kb/importing_standardized_formats)

You can also import from other tools, such as Reference Manager,
RefWorks, Papers, Google Scholar Library, ReadCube, etc., by exporting
to a [<u>standardized reference
format</u>](https://www.zotero.org/support/kb/importing_standardized_formats),
such as RIS, BibTeX, or CSL JSON, and then importing into Zotero by
clicking File → “Import…” and choose “A file”.

If you already have data in a Zotero library on another computer,
[<u>follow these
instructions</u>](https://www.zotero.org/support/kb/transferring_a_library)
to transfer your library to your new computer.
