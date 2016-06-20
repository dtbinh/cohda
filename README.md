# cohda
In decentralized systems, where the search space of a given optimization problem is distributed into disjoint subspaces, centralized optimization approaches often cannot be applied. For example, the global collection of data might violate privacy considerations or bandwidth restrictions. The gathering of such data might even be impossible, as it is the case if local search spaces are partially unknown or cannot be enumerated (i. e. due to infiniteness). Another limitation is that distributed search spaces are often not independent. Such interdependencies require to evaluate search spaces with relation to each other. For instance, this type of problem is present in the transition of today's electricity grid to a decentralized smart grid. Here, we have to cope with an increasing number of distributed energy resources (DER). The thesis focuses on day-ahead planning of the provision of active power for these DER, which can be expressed as a distributed combinatorial problem: Given a set of DER and a global target power profile, each unit has to select its own schedule for the planning horizon in such a way, that the schedules of all units jointly match the global target profile as close as possible.

For this purpose, the heuristic [COHDA (Combinatorial Optimization Heuristic for Distributed Agents)](http://www.uni-oldenburg.de/en/computingscience/ui/research/topics/cohda/) is developed. The approach is based on self-organization strategies and yields a distributed combinatorial optimization process in an asynchronous communication environment. Central components for data storage or coordination purposes are not necessary.

COHDA was developed as part of my [PhD thesis](http://oops.uni-oldenburg.de/1960/) (in German).