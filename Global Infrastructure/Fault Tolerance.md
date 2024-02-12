# Fault Domain
Fault Domain is a section of a network that is vunerable to damage if a critical device or system fails. The prupose of a fault domain is that if a failure occurs, it will not cascade outside that domain, limit potential damage.
You can have fault domains nested inside Fault Domains

The scope of a fault domain could be:
- Specific servers in a rack
- an entire rack in a detacenter
- the entire dtaa center building

Each Amazon region is designed to be completely isolated from other Amazon Regions. *Fault domain is the same thing as 'Failure Zone' as AWS coined the term failure zone*



#global-infrastructure 