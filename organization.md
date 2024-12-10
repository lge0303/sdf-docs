# Organization

## Coact :id=coact

[Coact](http://coact.slac.stanford.edu) is our portal for scientific resources and access management to S3DF. Facility czars control who gets access and how Facility Resources are distributed via Allocations. Every new S3DF user must first register with Coact and request S3DF access by specifying a Facility that they are affiliated with. The facility czar must then approve the request before the user can login.

### Facilities :id=facility

Facilities correspond to groups that have contributed funding or purchased S3DF hardware resources. A Facility in Coact may be an organization, a SLAC facility, a project, or a program. A list of Facilities and their points of contact can be found on our [Contact Us](contact-us.md) page.

### Facility Czars :id=czar

Facility czars are people nominated to represent the scientific computing requirements for a Facility. They represent and can speak for the needs of the experiment or project and can act as gatekeepers to S3DF resources on behalf of their consistuents. A Facility may have multiple czars.

### Repos :id=repo

Coact Repos are associated with a single Facility and constitute a grouping of Facility members as well as some subset of Facility resources allocated to that repo. A Coact Repo may represent a specific software project with an accompanying code repository, that the developers or maintainers deploy on S3DF infrastructure. It is ultimately up to Facility Czars how to manage repo organization, membership, and resource allocation.

#### Requests :id=requests

Requests form the basis for how Facility czars and Facility members self manage resources in S3DF. Users may submit Requests asking for membership to a facility, to a repo, or request a new repo. Requests under a facility are sent to facility Czars who may confirm or deny requests.


### Facility Resources

A Facility may purchase resources (compute, storage, kubernetes nodes etc). Such resources are allocated to the Facility and the Facilty czar may choose to share these resources amongst the Facility's Repos. Since the Facilty has purchased these resources, the members of the Facilities Repos will have prioritized and/or exclusive use of these resources.


### Batch Cluster

A cluster is a homogenous set of computing nodes with the same hardware specifications and storage access. See [Clusters & Repos](batch-compute.md). 

### Repo Compute Allocation :id=allocation

A Repo Compute Allocation is specified as a percentage of a Facilities Batch Compute Resource, and can be adjusted per Repo by czars under Repos -> Compute. Compute Allocations for a given Repo can be adjusted for each Batch Cluster a Facility has purchased resources in.

Generically, a Facility may request preemptable (non prioritized, no guarantee of job completion) to compute resources that they have not purchased.



