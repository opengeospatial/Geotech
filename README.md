# IDBE-Geotech

<img src="http://www.opengeospatial.org/pub/www/files/OGC_Logo_2D_Blue_x_0_0.png" width="200"/>
 <img src="https://buildingsmart-1xbd3ajdayi.netdna-ssl.com/wp-content/uploads/2018/11/694_NEW_-BuildingSMART_RGB_International_colour.png" width="300"/>

Welcome to the Integrated Digital Built Environment (IDBE) Geotechnical Engineering standardization effort. For more information on the IDBE, visit the [OGC public information page](http://www.opengeospatial.org/projects/groups/idbesc).

This GitHub repository is the workplace for collection of use cases and identification of existing work on the topic. The repository is public to allow the maximum number of stakeholders to participate in this collection effort.

If you are new to GitHub, instructions on its basic use are provided under [Using GitHub](https://github.com/opengeospatial/IDBE-Geotech) on this page.

## Repository Contents

### Use Cases
The [use_cases](https://github.com/opengeospatial/IDBE-Geotech/use_cases) folder contains descriptions of individual use cases, organized as documents. There is also a template document for users to create new use cases.

### Standards Catalog
The [standards_catalog](https://github.com/opengeospatial/IDBE-Geotech/standards_catalog) folder contains contains a catalog of individual standards and specifications, organized as documents. There is also a template document for users to create new standard summaries.

## Using GitHub

<hr/>
⚠️ Note for experienced GitHub users:
No need to read the rest of this document. We would prefer that you work in branches in the main repository and make pull requests for your changes, but direct push to the master branch is acceptable if you are a member of the project team. You are also free to fork the repository and make pull requests from your fork.
<hr/>

If you are not familiar with using GitHub, then read on. You probably should use the simplest tools available. Download [GitHub Desktop](https://desktop.github.com/) to allow you to manage your work and contributions to the IDBE-Geotech project through a simple interface.

The workflow is actually very easy. You will work on local files on your computer and can edit and manage those files just like any others. The only extra step is that you need to periodically synchronize your files with the online GitHub repository and have the repository managers assess and integrate your new work.

### Get access to the GitHub repository
This repository is open to the public and anyone can create new [Issues](https://github.com/opengeospatial/IDBE-Geotech/issues) to make suggestions for the work. If you are already a member of the IDBE group or would like to more actively contribute to this effort, we will be happy to add you to the project team. First, make sure that you have a [GitHub account](https://github.com/join). Then, send your contact information, your GitHub ID, and a brief description of how you want to contribute to [standards@opengeospatial.org](mailto:standards@opengeospatial.org).

### Download a local copy of the GitHub repository
To get a local version of the repository, click the "Clone or download" green button and select "Open in Desktop."

<img src="https://github.com/opengeospatial/IDBE-Geotech/blob/master/img/clone.png" width="500"/>

The local files of the repository will be placed in your filesystem. You can navigate to the files through the GitHub Desktop application. You are best-off editing the documents using your favorite text editor (lots of GitHub users like [Atom](https://atom.io/)).

### File management
If you want to make a new use case or register a new standard, first make a copy of the template document in your filesystem. Then name the copy something short and descriptive and edit. When you synchronize with the central repository, your new file will be uploaded.

### File editing
All of the files in the project are formatted as AsciiDoc. Don't worry about the odd equals signs or other markup in the document - these things just make the final work render nicely. Your job is to edit the main text.

Be sure to edit the appropriate information at the top of the document (title, organization, date, etc.). Fior instance, in the use_case document, the first few lines look like this:
```
= Use Case: title

*Version:* version number of use case, start at 1.0
*Author:* submitter
*Date:* YYYY-MM-DD

== Description
//brief description of use case
```
So after "=Use Case: " is the word "title." Replace "title" with your title for the use case. Similarly, after "*Author:*" replace "submitter" with the author of this use case (probably you).

Under "== Description" you see a line starting with two back-slashes. This line provides instructions for how to complete the text and there is no reason to delete the line. Just create a new line immediately following the instructions line and start editing text, like below:
```
= Use Case: Reconcile Standard Penetration Test results

*Version:* 1.0
*Author:* Jane Doe, OGC
*Date:* 2019-02-01

== Description
//brief description of use case
Standard Penetration Tests adhere to different national or regional....
```
We promise, the end results will look very nice when rendered in HTML.

### Synchronizing your edits
⚠️ Danger: make sure you are only adding content before you do the next steps. If you deleted any files from your local copy of the repository, DO NOT go any further and instead contact the project leads.

⚠️ If you are worried about messing up the repository, go no further and just email your changed or new documents to [standards@opengeospatial.org](mailto:standards@opengeospatial.org).

Once you are finished creating new files and making edits, be sure to save your work. Then go back to GitHub Desktop and you will see changes listed to the left in the application. Under the list of changes, type in a short summary to describe your changes and optionally some more details. Then commit those changes to the repository by clicking "Commit to master" at the bottom-left. See the example below.

<img src="https://github.com/opengeospatial/IDBE-Geotech/blob/master/img/commit.png"/>

Once the commit is complete, click on "Publish branch" in the upper part of the GitHub Desktop interface. This will update the central repository with your changes.

### Updating you local copy of the repository
Other people should be updating the repository as well. Usually, when you start GitHub Desktop it will tell you if changes occurred that you need to have locally. But just in case, you can click "Fetch origin" at the top of the application window to update your local copy.
