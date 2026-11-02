# Way9

WAY9 is a desktop workflow designer and job scheduler built with Java and JavaFX. You create
reusable objects (shell tasks, internal scripts, SQL statements, file transfers, waits for files or
database conditions, decision gates), place them as nodes on a canvas and connect them with arrows.
A node starts as soon as all of its predecessors have finished successfully, so independent
branches run in parallel. Jobs run locally, on SSH hosts or against JDBC databases. They can be
scheduled and handed to a local headless agent (WAY9Agent) that keeps running after the GUI is
closed. WAY9 can also deploy and manage that agent on Linux and Windows machines over SSH; sending
jobs to such a remote agent is not available yet. The library, run history, schedules and settings
live in one store: a local SQLite file, or a central PostgreSQL database shared by the GUI and all
agents.

Further informations about the status of the project can be found at https://way9.at/de/solutions/way9
