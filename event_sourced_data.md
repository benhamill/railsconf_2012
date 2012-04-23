# Use the Source, Luke
## Keith Gaddis

Event: when application state changes.

Serialize and store events; keeps a history.

History of events is basically git history; store only diffs, more or less.

Replay events after bug fix; DB is fixed.

Separate domain logic from non-domain logic.

"Creating a new problem", Keith?

Performance hit? Lots of events means really big logs.

Distributed systems, service-oriented architectures.

Check out replay gem.

Plays well with DCI.
