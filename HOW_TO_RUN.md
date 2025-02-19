# HOW TO RUN AS HEADLESS

## Make sure 'magicdisplay' service is running

Check -> 'sudo systemctl status magicdisplay'
If not -> 'sudo systemctl restart magicdisplay'
May have to reload daemon -> 'sudo systemctl daemon-reload'


## After service is running connect to display via chrome script

located here -> /bernau/bin/start-chromium.sh
Add to pm2 if not already.

## Good to good. :)
