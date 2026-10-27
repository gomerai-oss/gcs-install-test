# Identity registry

The mission router reads this table on `main`. An agent may act only while its row says `ACTIVE`. Change a row to
`SUSPENDED` or `RETIRED` to stop that agent at the router's next sweep. Changes to this file are made by a person, not
by a mission.

| Role | App ID | Installation ID | Status | Permissions |
|---|---|---|---|---|
| a2 | 5488815 | 175660931 | ACTIVE | contents write, PRs write |
| a3 | 5488892 | 175662493 | ACTIVE | contents write, PRs write |

Replace the example IDs with your Apps' IDs (App settings → General) and installation IDs (the number at the end of
the installation's settings URL).
