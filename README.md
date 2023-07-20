# therealbitcoin
"The Real Bitcoin"

During my travels through Mordor I came across a band of renegade orcs.  Like many of us who fell afoul of Sauron's heirarchy, since the brutal orcish invasion of the Americas, they spoke spitefully of the empire.  They made good company and conversation despite their stubbornness and despite the tendency of their leader to demonstrate remarkable poverty and ignorance on almost any topic, they gained my respect for their technological understanding and more.  Imagine my surprise when I saw that they had cobbled their own working bitcoin node together.   

The codebase is mostly just Satoshi's bitcoin version 0.5.3 with a few edits to further simplify the code (removing e.g. DNS references, Windows references, checkpoints, and QT references), and to enable static linking.  It connects and syncs the block chain and as such is a fully working node, though it doesn't implement all the usual RFC commands we enjoy in the cruftier nodes.

The polishing of the turd is currently described at http://thebitcoin.foundation.  I share this project with you here now in this insecure forum for posterity - and to save you the trouble of learning our dialect. 
