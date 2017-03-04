![julia](/julia.png?raw=true)

# julia
This started out as a hack to mitigate SAP Business Objects lack of a friendly api. It's based on BOs option to run a cron that sends an e-mail with the latest data as `.csv` in an attachment. Now, since parsing e-mails is madness I let [mailgun](https://www.mailgun.com/inbound-routing) handle this. The only thing left to do is have a server recieve the payload (at a route specified to mailgun), validate the sender, parse the `.csv` and display the html.

Due to a lack of demand - julia was never used in production. This repo is more of a proof of concept.

Note: This is a work in progress. I'll start importing all the files in the coming weeks.

[demo](http://s.codepen.io/KarlPokus/debug/2ed99feba84c215d2e943419be8b9c4e) with dummy data.
