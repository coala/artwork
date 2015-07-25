Requirements for a coala GUI
============================

A project is defined though a coafile. (Usually .coafile)

Initial state:
 * A user shall be able to create a project
   * Opens an empty project after asking for a directory/filename
 * A user shall be able to open a project

Opened state:
 * Executing:
   * A user shall be able to execute the project (meaning: run all enabled sections)
   * A user shall be able to execute specific targets
 * Editing/Viewing:
   * A user shall be able to view settings for each section
   * A user shall be able to add files, bears and other default settings explicitly for each section
   * A user shall be able to add/change arbitrary settings

Execution state:
 * A user shall be able to view results
   * File and line should be shown according to the result
 * A user shall be able to apply actions on results
