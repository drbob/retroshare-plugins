retroshare-plugins
==================

A collection of Plugins from various authors.

The aim of this git repo is simplify plugin compilation, 
and provide a decent collection so you dont have to search
out where to find them.

Please send me a pull requests to include any plugins
I have missed.


Compiling.
================

[Pre-requisite] Compiled Retroshare.
--------------------

	svn co retroshare retroshare-svn
	cd retroshare-svn
	qmake
	make

check-out in base of retroshare source tree.
------------------------------------

	git clone git:\\github.com\drbob\retroshare-plugins.git
	cd retroshare-plugins
	git update submodules --init
	qmake
	make



Plugins
======================

ZeroReserve by Anu: Friend 2 Friend Payment and Bitcoin exchange
------------------
https://github.com/zeroreserve/ZeroReserve

PaintChat by electron128
-------------------------
https://github.com/electron128/Retroshare-Paintchat-Plugin

RsWebUI by csoler
------------------------
https://gitorious.org/rswebui/rswebui

FriendMap by nyfor and chozabu
------------------------------
https://github.com/chozabu/FriendMap


Other Plugins which are not yet included:
=========================================

EmptyPluginRS by chozabu
-----------------------
https://github.com/chozabu/EmptyPluginRS

WebScriptRS by chozabu
------------------------
https://github.com/chozabu/WebScriptRS

Documentation by Morpheus Being
----------------------
https://github.com/morpheusbeing/retroshare_plugin_writing

