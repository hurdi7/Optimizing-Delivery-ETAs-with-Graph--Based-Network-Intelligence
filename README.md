# Optimizing-Delivery-ETAs-with-Graph--Based-Network-Intelligence
Project by Consulting and Analytics Club, IIT Guwahati


## Background
Delhivery is India's largest fully-integrated logistics provider, operating a vast network of facilities, inter-city routes, and last-mile delivery across every major state. At the core of its operations is a hub-and-spoke model: shipments travel from a source facility through one or more intermediate hubs before reaching the destination, each hop is a segment of a multi-leg journey.
To estimate delivery times, Delhivery uses OSRM, a standard routing engine that assumes clean traffic and shortest paths. But real-world logistics is far messier: congestion, facility dwell time, seasonal volume spikes, and route-type constraints all cause actual delivery times to deviate significantly from predictions.

## The Challenge
The strategic question: Delhivery's OSRM system underestimates actual delivery time on a significant fraction of routes. Can a graph-based model, one that treats the logistics network as a connected graph of facilities and corridors, not a collection of independent point-to-point estimates, produce more accurate ETAs and identify which corridors and hubs are systematically causing delays? When ETA is wrong, SLAs are missed and customers are unhappy Downstream capacity planning breaks down across the network 
There is currently no systematic way to identify which hubs and corridors are the biggest contributors to delays Route-type decisions (FTL vs Carting) are made without accounting for graph position or structural risk of a facility.
