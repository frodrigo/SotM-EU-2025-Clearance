Ttitle:

OSM Data replication under Quality Constraints with Clearance, OSM Logical History and UnderpassAPI

Abstract

"Clearance" tracks OSM changes and replicates extracts under quality constraints, and its subprojects: OSM Logical History which displays changes at semantic level and UnderpassAPI, which responds to Overpass queries from the partially replicated data.

Long description

"Clearance" is a tool that helps track changes in OSM on tematics, and keep replication extracts up to date, while still following quality rules. Instead of relying on timestamps or changesets, it focuses on partial and local data updates. If some data is rejected, it either needs to be fixed in OSM or approved manually, data edits are only done in OSM. Reviewing and fixing are done collaboratively.

OSM Logical History is a subproject that conflates two versions of OSM to present changes from a semantic point of view, like in the case of a split highway or a semantic move from a node to a polygon.

UnderpassAPI is a subproject that returns results for Overpass Query Language but from an SQL database such as Postgres or DuckDB.


Contributor for more than a decade, interested in data quality, maintainer of Osmose-QA, vector tiles and routing engine.
