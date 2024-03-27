# Node-RED-HA-Solcast-JSONata

Read, store, and evaluate Solcast PV forecasts using Node-RED and JSONata for Home Assistant

A work in progress

Read Solcast forecasts for Residential account (two planes) during the day. Maintain an array of forecasts covering today and tomorrow, with estimated actuals for yesterday and the day before.

Add actual production every half-hour.
Provide estimates for forecast for today, today remaining, tomorrow.
Estimates by block period (defined by user - eg sunrise-noon, noon to 16:00, 16:00 to 19:00, post 19:00)

Estimate upper and lower in range.

Historic analysis - forecast 2 days ahead to 1 day ahead to 1 day after to 2 days after to actual

Option to add in domestic load as well as actual solar generation (and import from grid / export to grid)

Learning projection - average last two days load to project for day
