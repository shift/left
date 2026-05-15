# The Quiet Fix

> 📍 Sprint 2 · 2 decisions made

You track down the timeout issue. Buried in a config file, someone set `SESSION_TIMEOUT=30`. Seconds, not minutes. A one-line fix.

But while you're in there, you notice the entire auth module has **zero tests**. The login bug was a symptom. The module is a house of cards.

You could just ship the fix. Or you could make it right.

---

- [Ship the fix, file a ticket for tests](./ship-fix/README.md)
- [Add tests while you're here](./add-tests/README.md)
- [Rewrite the whole auth module](./rewrite/README.md)

**3 choices — there is no going back.**

