# Power Architecture

Status: LOCKED

## Power flow

Battery -> Fuse -> TVS -> Reverse Polarity MOSFET -> AP63203WU-7 -> 3.3V Rail

## Locked decisions

- Buck converter: AP63203WU-7
- Primary target: 12V systems
- TVS: Unidirectional, SMBJ package (exact part TBD during schematic)
- Reverse polarity protection: P-channel MOSFET
- Input fuse: ~2A, final implementation (SMD/blade/external) will be selected during PCB layout based on cost and practicality.

## Serviceability

- Euroblock battery connector
- Test points on PCB
- No buzzer
- Clear PCB silkscreen labels
- External modules connected via connectors
