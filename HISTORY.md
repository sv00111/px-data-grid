v1.0.0-beta.4
==========================
* Passes `item` object to the renderer to allow the renderer to read its "row
  data" to use at render time or in passing data up to the app through events
Demo updates:
* Adds demo for px-data-grid-paginated

v1.0.0-beta.3
==========================
* Update date/time rendering and filtering functionality to correctly use
  source data timezones when displaying bits of UI to the user (#753, #759, #762)
* Expand date/time APIs available in `columns` to support complete configuration
  of date/time UI by the developer. See the docs for more info.
* Fixes bug that caused px-data-grid to throw error when column objects were
  re-mapped and a non-configurable property was set (#761)
* Fixes bug that caused the page size select dropdown in px-data-grid-paginated
  to show an ellipsis when there was enough room to show the page numbers (#758)

v1.0.0-beta.2
==========================
Demo updates:
* Fix link to Github in the demo header
* Add link to Glitch in the demo snippet

v1.0.0-beta.1
==========================
* Initial release of the px-data-grid for beta testers. This release gives teams
  the chance to try the new grid out in dev/QA environments. It's not intended
  for use in production.
* Releasing all existing features for testing and feedback. See the px-data-grid
  and px-data-grid-paginated API docs for a list of all properties and methods
  available.
