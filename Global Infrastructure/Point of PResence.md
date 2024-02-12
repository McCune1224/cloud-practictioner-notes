An intermediate location between an AWS REgion and the end user, and this location could be a datacenter or collection of hardware.

Examples:
- Redge Locatoins
- Regional Caches

Edge Locations are datacenters that hold cached (copy) of most popular files (eg web pages, images, videos) to reduce the distance time for sending a resource.

Regional Edge Locations are datacenters that hold much larger caches of less-popular files to reduce round trip.

PoPs live at the edge/intersection of two networks


Tier 1 network is a network that can reach every other network on the Internet without pruchasing IP transit or paying for peering. [[Availability Zones]] are all redundantly connected to multiple tier-1 transit providers


a few AWS services that use PoP for content delivery or expediated upload:
- [[Amazon CloudFront]] 
- [[Amazon S3 Transfer Acceleration]]
- [[AWS Global Accelerator]]


Amazon is a CDN that allows your website 

#global-infrastructure 