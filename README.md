# music-auction
This is the repository for an application based on a music auction service for bars.

There is a server with an UI displaying the queue of the requested song by the bar clients. A song can be requested by purchasing something in the bar. Then if another client wants to bid for that song to sound, another purchase in the bar has to be made.

Architecture:
- Online: Cloud based architecture, where the server accesses to a database in the cloud. There is an application running in some samrtphones in the bar to manage the upload of songs to the queue and bids.
- Offline: the application in the smartphone connects via bluetooth to the server in the bar. The database can run in the server computer.

Future ideas:
- create also bidding by posting with a hastag in a social network.
- creating more services as games for the clients.
