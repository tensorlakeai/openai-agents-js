# Maintainer installation policy

Use pnpm 11.28.5 with Node.js 22+. Keep the existing seven-day delay, require
publication timestamps and recheck frozen/cached locks. Automatic lifecycle
hooks are disabled. Local Git hooks are explicit: `pnpm run setup:git-hooks`.
Existing native approvals are retained for reviewed explicit rebuilds; this
policy does not automatically run those hooks. npm interoperability tests and
consumer instructions remain supported.
