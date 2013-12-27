# supersimplepeerjsdemo
## A really simple PeerJS demo.
### STEPS:
* Start your own PeerJS server or [start one in the cloud](http://peerjs.com/peerserver).
* Substitute your API key for the key in superSimplePeerJS.html
* Open a Chrome tab (ctab) and an incognito tab (itab) for superSimplePeerJS.html.
* In their respective console windows, execute the following commands:
	* ctab > definePeer('abc');
	* itab > definePeer('abc1');
	* ctab > var otherPeer = connect('abc1');
	* itab > var otherPeer = connect('abc');
	* ctab > otherPeer.send('My message from abc.');
	* itab > otherPeer.send('My message from abc1.');