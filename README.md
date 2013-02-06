# TweetMapR
**TweetMapR** is a poor man's realtime Twitter client (read-only for now) consuming Twitter Streaming API and broadcasts data to the clients via SignalR.

# Clone and Run
You can run TweetMapR on your box. Just clone the repository and move the following files and under *TweetMapR/src/TweetMapR*:

 -  scripts/TweetMapR_config/Web.config
 -  scripts/TweetMapR_config/Web.Debug.config
 -  scripts/TweetMapR_config/Web.Release.config

Then, set your Twitter API Keys inside the *Web.config* file you just copied:

	<add key="ConsumerKey" value="" />
	<add key="ConsumerSecret" value="" />
	<add key="Token" value="" />
	<add key="TokenSecret" value="" />

Finally, run the **TweetMapR** project. You are good to go!