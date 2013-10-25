Soup7
===

Soup7 is the seventh version of Note Soup.  It is a browser-based sticky notes organizer.

This version is written in AngularJS, using LocalStorage.

LocalStorage is browser magic that allows modest databases to be stored locally in your browser.  Your data never travels over the network, because there is no server.

### Live demo:

Live demo: http://soup7.herokuapp.com/

### Install a local copy

Because this is a server-free web application, it is very easy to have a secure local copy.  You need only download and unpack the .zip file, and open the file soup7.html in your browser.

Download: https://github.com/billroy/soup7/archive/master.zip

### Install on Heroku

Soup7 is ready to go on Heroku:

    $ git clone https://github.com/billroy/soup7.git
    $ heroku create --stack cedar
    $ git push heroku master

### About LocalStorage

Wherever soup7.html and the related support code is installed, your notes are stored on your computer, not the network.  Be careful to back up your computer frequently to ensure your notes are backed up.

Each browser has a separate LocalStorage, so you can't see your notes from browser A in browser B, even on the same computer.

Each browser also keeps separate LocalStorage for each domain.  This means notes entered on domain A are not visible from domain B.

You can use these features to create separate realms of notes.


### Privacy

The "Wipe All Workspaces" command in the workspace menu will remove all Soup7 data from your machine.

### License

Use under MIT License.
