Change Log
===============================================================================

Version 1.0.5 *(2013-03-XX)*
----------------------------

 * The 'SimpleCursorAdapter' sample now uses loaders 
 * Added new adapter type 'MultiChoiceArrayAdapter'

Version 1.0.4 *(2013-03-25)*
----------------------------

 * Added MultiChoiceSimpleCursorAdapter
 * Added new activity to the sample app to showcase new MultiChoiceSimpleCursorAdapter, and necessary DB infraestructure
 * Refactored MultiChoiceBaseAdapter to avoid code duplication when implementing MultiChoiceSimpleCursorAdapter


Version 1.0.3 *(2013-03-24)*
----------------------------

 * Fixed a bug which caused item selection to be completely broken in Android 2.X

Version 1.0.2 *(2013-03-24)*
----------------------------

 * Fixed a bug which prevented the selected item background from being shown the second time items were selected
 * Simplified the code that deals with item removal in the sample app
 * Added support for checkboxes
 * Added support for multiple activities to the sample app
 * Added code to persist selection state when a configuration change occurs

Version 1.0.1 *(2013-03-23)*
----------------------------

 * Added new actions (select all, reset list) to demo app; removed useless "settings" action
 * Fixed a bug which caused the app to crash if the initial selection was made programmatically
 * Fixed a bug in demo app which caused the app to crash when several items were deleted at once
 * Added this change log
 * Added one more digit to versioning scheme (1.0 => 1.0.1)
 * Improved support for background customization via styles and attributes
 * Switched to space-based indentation

Version 1.0 *(2013-03-22)*
----------------------------
Initial release.