# This is a small hack that I developed for a problem I faced.
 ## This pipeline does the following things
* **First** 
 * Task Downloads Build from Azure Artifact
* **Second Task**
 * Downloads Zip from Azure storage
 * Adds the build from azure artifacts to the zip file
 * Lists the contents of zip file
 * Unzips the zip file
 * Lists the contents of directory
 * Moves the Build from Azure artifacts to the unzipped directory
 * Zips the directory 
 * Lists the contents of the zip.

# **All the variables needs to be defined in the pipeline libraries for thsi to work.**
