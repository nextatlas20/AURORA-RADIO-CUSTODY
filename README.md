# Aurora Mutual Aid Radio Cache

This sealed custody snapshot supports the winter deployment handoff.

<!-- CUSTODY-BOARD:BEGIN -->
## Radio custody board — 3 February 2106
Rows: 20 physical | 15 valid | 5 invalid
Replay: 12 accepted | 3 rejected
Accepted actions: 6 dispatch | 4 arrival | 2 audit
Kits: 2 transit | 2 relocated | 2 home

| Kit | Label | Home | Current | Destination | Seal | Accepted | Rejected | Status |
| --- | --- | --- | --- | --- | --- | ---: | ---: | --- |
| RK-03 | Field Three | East |  | North | S-E5F6 | 2 | 1 | TRANSIT |
| RK-04 | Medical Four | North |  | West | S-G7H8 | 1 | 1 | TRANSIT |
| RK-01 | Beacon One | North | South |  |  | 3 | 0 | RELOCATED |
| RK-02 | Relay Two | South | East |  |  | 2 | 1 | RELOCATED |
| RK-05 | Spare Five | West | West |  |  | 0 | 0 | HOME |
| RK-06 | Survey Six | East | East |  |  | 4 | 0 | HOME |
<!-- CUSTODY-BOARD:END -->

## Handling note

Never deploy a radio kit while its recorded custody state is in transit.
