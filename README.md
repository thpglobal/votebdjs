# votebdjs
* Readonly
* 2020 Version of votebd.org server and client
* the philosophy - clean, vanilla js whever humanly possible
* no angular
* no express
* Bootstrap 3.4.1 to try and utilize some of the old views
* MongoDB v4 - note major deprecation of old connection modes
* server.js handles simple find queries and static pages

## Installation
* Clone the repository, creating a new folder
* Make sure node and npm are working
* To start locally, issue node server.js

## Structure
* Each page is made up of a copy of index.html, which includes header.html, a middle.html and footer.html where middle
* At the moment, everything is local so it can run offline without access to cdn.
