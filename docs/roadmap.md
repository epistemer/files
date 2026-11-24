# Roadmap

Second of the three new packages (neozp decision D5), after message delivery.

## What the brief will start from

- Confab's `internal/confab/files.go` (90 lines), and the cleanup every save does when it stores a file and the record then fails to commit.
- ui's uploads (`ui/forms/files`, ui ADR 0012), which carry stored files by key but store nothing.
- zp's file storage, read as a record of needs: local disk and S3, files from a path, bytes, an upload or a URL, and forced downloads for some content types.

## M0: the brief

| ✓ | Item | Done when |
|---|---|---|
| ☐ | M0.1 `docs/brief.md`: what the record of needs teaches, the idea, decisions (each marked epistemer or Claude), the API sketch, open questions with defaults | written |
| ☐ | M0.2 A review by the other model family | its findings fixed or answered |
| ☐ | M0.3 Spikes for the risky decisions | each recorded as an ADR |
| ☐ | M0.4 `docs/interface.md`, locked by epistemer | locked; build milestones planned here |

Ownership: [ownership.md](ownership.md), delegated by epistemer on
2026-11-24.
