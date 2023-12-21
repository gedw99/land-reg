# land-reg

https://www.gov.uk/search-house-prices

This is very much a WIP.  For now am building up notes / logic.

Backend / Frontend will be golang based using htmx patterns of:

https://github.com/delaneyj/datastar

You can try the htmx examples here: https://htmx.org/examples/


Deployment to fly.io to 22 data centers with real time Sqlite DB sync between all data centers. 

Fly.io runs a BGP based Anycast network, so that any users requiest is automatically sent to the nearest data center.

https://fly.io/docs/reference/regions/
