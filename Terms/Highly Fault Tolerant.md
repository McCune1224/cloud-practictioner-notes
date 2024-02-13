Ability for your service to ensure there is no single point of failure. *Preventing* the chance of failure

Fail-overs is when you have a plan to shift traffic to a redundant system in case the primary system fails

[[RDS Multi-AZ]] allows you to run a duplicate standby database in another [[Availability Zones]] in case your primary database fails.

# Example
A copy (secondary) database where all ongoing changes are synced. The secondary system is not in use until a fail over occurs and it becomes the primary database.