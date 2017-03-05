![julia](/julia.png?raw=true)

# julia
A dashboard for global health care data - number of current patients, in, out, visits and waiting list - organized by facility and time.

# usage
- Select organization
- Select time frame
- Optionally filter data

# Project
This is a company dashboard prototype made in 2015 for data-driven development. It contains a responsive UI, persistant filters and is easily extendable with more units and data points. The data source used is a cron in Business Objects that sends an e-mail with a `.csv` attachment - via [mailgun routing](https://www.mailgun.com/inbound-routing) for parsing - to a node.js server for calculations and presentation in html. Julia was never used in production. This is an archive.

# Demo
[Demo](http://s.codepen.io/KarlPokus/debug/2ed99feba84c215d2e943419be8b9c4e) with dummy data.
