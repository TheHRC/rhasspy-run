
# Introduction
Rhasspy is an open source, fully offline set of voice assistant services for many human languages that works well with:

<li>Hermes protocol compatible services (Snips.AI)</li>
<li>Home Assistant and Hass.io</li>
<li>Node-RED</li>
<li>Jeedom</li>
<li>OpenHAB</li>

[Follow this link for the official documentation](https://rhasspy.readthedocs.io/en/latest/)

# Run with docker-compose
```
docker-compose -f docker-compose-rhasspy.yml up
```
<b>Note</b>: <i>"-d"</i> with the above command to run in background


# Run with docker run using the sh script
```
sh rhasspy_run.sh
```