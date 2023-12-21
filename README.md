# land-reg

https://www.gov.uk/search-house-prices

This is very muc h a WIP. 

Backend Frontend will be golang based using:

https://github.com/delaneyj/datastar

Deployment to fly.io to 22 data centers with real time Sqlite DB sync between all data centers.

Fly.io runs a BGP based Anycast network, so that any users requiest is automatically sent to the nearest data center.

https://fly.io/docs/reference/regions/
