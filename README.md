# Parking Lot for Monster-UI

This app allows you to view and pickup parked calls, by clicking them on the screen.

You can also see and call the person who parked the call.

## Installation
Clone the repository to your Monster UI apps directory (often /var/www/html/monster-ui/apps, but may be different on your system). Then you may register the app on KAZOO with a sup command (with your specific Crossbar API location):

```cd /var/www/html/monster-ui/apps```

```git clone https://github.com/ruhnet/monster-ui-parkinglot parkinglot```

```sup crossbar_maintenance init_app '/var/www/html/monster-ui/apps/parkinglot' \\ 'http://mycrossbarapi.tld:8000/v2'```

