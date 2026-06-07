# Core concepts

### Launches

A **launch** is a scheduled change with a time attached. Each launch moves through states you can see in the dashboard: _Scheduled_ (waiting), _Live_ (applied), _Rolled back_ (reverted), or _Failed_ (something prevented it — see [Troubleshooting](../reference/troubleshooting.md)).

### Snapshots

Before Launch Flow changes anything, it saves a **snapshot** of the original values — for prices, that's the existing amount on each product. The snapshot is what makes a clean rollback possible: Launch Flow always knows exactly what to restore.

### Scheduled events

Your plan determines how many launches can be scheduled at once. The Free plan allows **one** scheduled event at a time; paid plans allow more (see [Plans & limits](../reference/plans-and-limits.md)).
