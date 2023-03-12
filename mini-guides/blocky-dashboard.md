Originally discussed [here](https://discord.com/channels/830763548678291466/1084135564925751458), in TrueCharts discord.

If you haven't set up Prometheus and grafana, go to the [Prometheus and Grafana mini-guide].

Otherwise, if you already have grafana and prometheus running, just import dashboard 13768 in grafana:
Image

Then set your prometheus instance as source, and your kubernetes dns and port as API address; mine is `http://blocky.ix-blocky.svc.cluster.local:4000`. (The red messages in the image are because I already have it setup and it's screaming in fear of being overwritten.) 

Image
