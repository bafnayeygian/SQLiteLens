# Security Policy

SQLiteLens opens SQLite database files in read-only mode and runs metadata queries.

## Untrusted databases

SQLite database files are parsed by the local SQLite library. Do not inspect untrusted database files in privileged environments unless you trust your sandboxing and SQLite version.

## Data exposure

Reports may include table names, column names, schema details, trigger SQL, view SQL, and row counts.

Do not publish reports for private databases unless the schema information is safe to share.

## Reporting vulnerabilities

For ordinary bugs, use the public issue tracker.

For security-sensitive issues, avoid publishing exploit details before a fix is available.
