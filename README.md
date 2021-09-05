# Graph-Traversal
Graph Traversal to model Vaccine-Strain relationships.

Assume that you have a list of N strains and M vaccines. For the sake of this assignment, let us assume that a particular vaccine could neutralize only two strains at max. Write an application that maps COVID Strains and Vaccines and can answer the below queries:

- List the unique strains and vaccines the researcher has collected in the system.
- For a particular strain, help the reporter recollect the vaccines it has been neutralized by.
- For a particular vaccine, list the strains that have been neutralized with it (past or present).
- Identify if two vaccines neutralize similar strains. Vaccine A and vaccine B are considered to neutralize similar strains if they have been associated with the same strains (not necessarily at the same time or in the same year)
- Can two vaccines A and B be connected such that there exists another vaccine C where A and C are neutralizing similar strains and C and B are neutralizing similar strains.
