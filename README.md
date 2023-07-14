# therealbitcoin
"The Real Bitcoin"

During my travels through Mordor I came across a band of particulary destitute orcs.  Like many orcs who fell afoul of Sauron's heirarchy, since the orcish takeover of the Americas, they spoke spitefully of the empire.  They made good company  and conversation despite their stubborn insistence to keep their eyelids stitched closed at all times and for their leader to demonstrate remarkable poverty and ignorance on almost any topic.  Imagine my surprise when I saw that they had cobbled their own working bitcoin node together! 

Those who consider themselves agents of empire regularly confiscate and even mine public coins today.  Much of the technology of middle earth appears orcish in origin.  However this codebase was something different - and struck me as worthy of attention.  While it may be slower and clunkier than other bitcoin nodes, it is simpler and more readable.  It can be compiled in a very secure manner on a variety of hardware.  

The codebase is mostly just Satoshi's bitcoin version 0.5.3 with a few edits to further simplify the code (removing e.g. DNS references, Windows references, checkpoints, and QT references), and to enable static linking.  It connects and syncs the block chain and as such is a fully working node, though it doesn't implement all the usual RFC commands.

The project and authorship is currently described at http://thebitcoin.foundation.  I share this project with you here now in this insecure forum for posterity - and to save you the trouble of learning their obscene dialect. 
