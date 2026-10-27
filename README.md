# PHOBOS Database

**PHOBOS Community Edition 1.0.1** is a production-oriented relational database engine built from scratch with transactions, MVCC, WAL durability, crash recovery, relational constraints, backup/restore, PITR, replication, TLS, and PHOBOS Management Studio.

## Downloads

- **Windows x64 Setup:** https://drive.google.com/file/d/1A4-QAnDrEbbMSsRRIvSZvYNwUaMHNhNt/view?usp=drive_link
- **Windows x64 Runtime ZIP:** https://drive.google.com/file/d/1P9jgYCFh7h6atAvnwhAI0851LQmuZ9Vh/view?usp=drive_link
- **Source ZIP:** https://drive.google.com/file/d/1kS1aKl9J3m2fjRSIDe7c1171-odZ_7ix/view?usp=drive_link

SHA-256 hashes are provided in `PHOBOS-1.0.1-FINAL-HASHES.txt` in this repository.

## Main Features

- Transactions and MVCC
- Write-ahead logging and crash recovery
- Primary keys, CHECK constraints, defaults, identity columns, and foreign keys
- `INSERT ... RETURNING`
- Views, CTEs, joins, subqueries, `UNION`, and `INSERT ... SELECT`
- Backup and restore
- Point-in-time recovery
- Replication
- TLS and authenticated access
- PHOBOS Management Studio
- No artificial Community Edition CPU, RAM, database-size, or connection licensing caps

## Platform Status

**Windows x64 is the qualified platform for PHOBOS Community Edition 1.0.1.**

Linux and macOS are not yet qualified release targets.

## Important Limitations

PHOBOS is still a young database project and does not claim full SQL-standard compatibility or feature parity with PostgreSQL, SQL Server, Oracle, or MySQL.

Current limitations include:

- One database per server instance
- Coarse `admin`, `writer`, and `reader` roles
- `DROP TABLE` is not currently supported
- Windows release files are currently unsigned
- Linux/macOS qualification is still pending

## Release Validation

PHOBOS Community Edition 1.0.1 completed its Stage 28 Windows x64 release-validation gate, including crash/WAL recovery, backup/restore/integrity, PITR, replication replay, packaged runtime stress, SQL regression tests, Management Studio error-resilience testing, and the frozen PHOBOS Standard benchmark.

## Repository

Project repository:

https://github.com/jmespana83/phobos-database

---

PHOBOS Community Edition 1.0.1 — built from scratch, community-first, and continuing to improve in public.
