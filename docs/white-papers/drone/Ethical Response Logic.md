+--------------------------+
| Start (Power On)        |
+-----------+--------------+
            |
            v
+--------------------------+
| GPS Lock Acquired?       |
+-----------+--------------+
            |
           Yes
            |
            v
+--------------------------+
| Is Area Tagged as        |
| Built-up / Protected?    |
+-----------+--------------+
            |
     +------Yes-------+       
     |                |
     v                v
+----------------+   +------------------------------+
| Check for       |   | Area is Open (Rural)        |
| Authorization   |   | or Club Zoned               |
| Dongle Present? |   +------------------------------+
+-------+--------+               |
        |                        v
      Yes                        v
        |               +--------------------------+
        v               | Scan for Aircraft Beacons|
+--------------------+  +--------------------------+
| Full Access Mode   |              |
| (Flight Permitted) |              v
+--------------------+     +--------------------------+
                           | Beacon Detected?         |
                           +-----------+--------------+
                                       |
                                     Yes
                                       |
                                       v
                           +--------------------------+
                           | Is Conflict Possible?    |
                           +-----------+--------------+
                                       |
                               +-------Yes--------+
                               |                  |
                               v                  v
              +----------------------------+   +-----------------------+
              | Trigger Avoidance Logic:   |   | Continue Flight Path  |
              | - Adjust Altitude/Heading  |   | (Monitor Closely)     |
              | - Loiter or Descend        |   +-----------------------+
              | - RTH if Safe & Needed     |
              +----------------------------+

