# Search-Engine
Search engine project.

Infrastructure:

CMS: ?

Version control: Github

Automation / Deploying: Jenkins

Database: Elasticsearch

Languages used: HTML, SASS (SCSS), JS, PHP

JS toolkit: Gulp

Gulp function:

IDE: Visual studio

- When gulp is installed, run command gulp --watch ( This will allow you to watch for all changed in the sass file being edited, and gulp will automatically compile it for you.

--------- Build order ---------

1. Pull from Git to local machine.
2. Run localhost build.
3. When done, push to git and merge to dev branch. ( Jenkins will spin up a new build of the dev site when this is approved)
4. When dev is approved, push to master. ( Jenkins will spin up a new build of the live site when this is approved)
