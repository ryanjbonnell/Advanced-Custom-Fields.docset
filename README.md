# Advanced Custom Fields Docset

A docset of the [Advanced Custom Fields][1] WordPress plugin by [Elliot Condon][2] for the popular Mac OS X app, [Dash][3].

## Installation

1. Download a Zip archive of this repository
2. Extract the file to your Desktop
3. Copy **Advanced Custom Fields.docset** to `~/Library/Application Support/Dash/Docsets/Advanced Custom Fields`
4. Launch Dash
5. Open Dash's Preferences (⌘,) then select the **Docsets** tab
6. Click the **Rescan** button
7. _Advanced Custom Fields_ will appear in the list of installed Docsets

## Alternate Installations

If you prefer using a Terminal to the Finder, use the following commands:

1. `mkdir -p ~/"Library/Application Support/Dash/DocSets/Advanced Custom Fields" && cd "$_"`
2. `curl -#OkL https://github.com/ryanjbonnell/Advanced-Custom-Fields.docset/archive/master.tar.gz`
3. `tar -xzf master.tar.gz --strip-components 1 && rm master.tar.gz`
4. `open "Advanced Custom Fields.docset"`

An even more succinct version is:

`mkdir -p ~/"Library/Application Support/Dash/DocSets/Advanced Custom Fields" && cd "$_" && curl -#kL https://github.com/ryanjbonnell/Advanced-Custom-Fields.docset/archive/master.tar.gz | tar -xz --strip-components 1 && open "Advanced Custom Fields.docset"`

## Changelog

**Version 4.3.7** (18 April 2014)

[1]: http://www.advancedcustomfields.com/
[2]: http://www.elliotcondon.com/
[3]: http://kapeli.com/dash