# Threat-modelling, STRIDE

Worlds shortes introduction: <https://www.youtube.com/watch?v=2pvprvsr1lo&list=PLCVhBqLDKoOOZqKt74QI4pbDUnXSQo0nf>

## Data flow Diagram

Data flow Diagram DFD3: <https://github.com/adamshostack/DFD3>
- external entities
- processes
- data flow
- data stores
- trust boundry

## STRIDE

STRIDE helps us be structured in how we think about threats

. Spoofing
. Tampering
· Repudiation
. Information Disclosure
. Denial of Service
· Elevation of Privileges

STRIDE in 20 min <https://www.youtube.com/watch?v=rEnJYNkUde0>

## Threat Modeling Process

Step | Info | Details
-- | -- | --
1 | Doomsday scenarios | What would be the worst thing that could happen to the service? Examples: Data leakage, manipulation of infrastructure/services, outage
2 | Context diagram | What are the major communication peers of the service?
3 | Data Flow Diagram (DFD) | What are the major data flows inside and beyond the borders of the service?
4 | Trust Boundaries | What portions/components of the service do trust each other?
5 | Identify Threats | Use the STRIDE methodology to identify threats on components adjacent to trust boundaries.
6 | Address Threats | Define countermeasures to avoid or mitigate threats.
7 | Residual Vulnerabilities | Prioritize unmitigated threats according to the risk they impose.

