# Boycott Trump

This is a script for boycotting businesses that work with or support the Trump family. All it does is prevent your computer from visiting the websites associated with these businesses. 

## Installation (only for OSX now)

1. Find your _Terminal_ and open it (it is in _Applications_ - _Utilities_)
2. Copy & paste the following three lines.

```
wget wget https://github.com/seandockray/browser-boycott/raw/master/boycott-trump
chmod 755 boycott-trump
sudo ./boycott-trump
```
4. You should be prompted for your administrator password. Did I mention that you need to be administrator of your machine?
5. If you absolutely need to undo this, you will need to edit your /etc/hosts file.


## Development Notes

* The initial list of domains is taken from [this spreadhseet](https://docs.google.com/spreadsheets/d/1vu0Y0HvadMgG_LN7dF8W7M66oPCcx_nmSARQWirV7iY/htmlview). Others should fork, file issues, submit pull requests, etc. to add to the list. For example, [I added moca.org](https://www.artforum.com/news/id=59943).
* At the moment, it is written for OSX but could easily be adapted for other operating systems.
* Some kind of installer would be helpful.
* An updater would be even more helpful.
* And if the sites redirected to an information page... 

