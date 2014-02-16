The way I use Plone
===================

An opinionated collection of notes on my Plone projects practices, that could be applied to most CMS-based projects really.

## Guiding principles and prerequisites

* More a philosophical principle that we should follow in all we do, but *I do not expect all my use cases 
  to have a Plone-based answer*. It's even okay that some use cases do not have an answer. It's okay to fallback to manual
  solutions.
   
* Ideally, I use a setup with Plone 4.3+ where the default content types are replaced with the Dexterity-based ones (plone.app.contenttypes).

* I use my own buildout configuration, because it is easy for me, and that way, I know exactly what gets installed. 

* Whenever possible, I use [browser views](http://developer.plone.org/views/browserviews.html) instead of TTW templates and scripts . 
