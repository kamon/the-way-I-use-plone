The way I use Plone
===================

A collection of notes on my development and deployment practices with Plone.

## Guiding principles and prerequisites

* **I do not expect all my use cases to have a Plone-based answer**. It's even okay that some use cases do not have an answer. 
  It's okay to fallback to manual solutions.
   
* Ideally, I use a setup with Plone 4.3+ where the default content types are replaced with the Dexterity-based ones (plone.app.contenttypes).

* I use my own buildout configuration, because it is easy for me, and that way, I know exactly what gets installed. 

* Whenever possible, I use [browser views](http://developer.plone.org/views/browserviews.html) instead of TTW templates and scripts . 


## New technology, still under testing

* [plone.app.widgets](https://github.com/plone/plone.app.widgets).
