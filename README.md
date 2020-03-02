ONOS REST API/CLI

Supported ONOS CLI operations:

    CONFIGURE A ROADM:
    `onos> oe-config roadm [roadm_name] [port1_id] [port2_id] [channel_id]

    CONFIGURE A TERMINAL:
    `onos> oe-config terminal [terminal_name] [ethPort_id] [wdmPort_id] [channel_id] [power]

    SHOW ALL LINKS:
    `onos> oe-config show-links

    SHOW ALL ROADM-ROADM LINKS:
    `onos> oe-config show-roadm-links

    SHOW ALL TERMINAL-ROADM LINKS:
    `onos> oe-config show-terminal-links

    SHOW ALL ROUTER LINKS:
    `onos> oe-config show-router-links

    SHOW NETWORK MONITER:
    `onos> oe-config monitor

    SHOW LINK OSNR:
    `onos> oe-config osnr

    CONFIGURE A DEFAULT NETWORK TOPOLOGY:
    `onos> oe-config default-topo

          h1 - s1 - t1 = r1 --- r2 --- r3 = t3 - s3 - h3
                       ||
                       t2 - s2 - h2

