Collection of keymap files for various JetBrains IDEs

## ReSharper

resharper.5.0.eclipse.shortcuts.vs2010.vssettings appears to work for VS 2008 as 
well.

## RubyMine

Importing and exporting are all done via .jar files. The raw .xml files are included in here for diffs and versioning.

### Importing/Exporting

https://www.jetbrains.com/help/ruby/exporting-and-importing-settings.html

Export just the Keymaps to the .jar file. On macOS, the Archive Utility should be able to extract the contents for
uploading the raw .xml file to this repo.

Import using the same instructions above.

Here's the file structure of the .jar (as of 2.0 thru 8.3), fyi:

```
.jar
+- keymaps
   +- rubymine.2.0.eclipse.xml
```
