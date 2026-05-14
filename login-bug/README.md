# The Quiet Fix

You track down the timeout issue. Buried in a config file, someone set `SESSION_TIMEOUT=30`. Seconds, not minutes. A one-line fix.

But while you're in there, you notice the entire auth module has **zero tests**. The login bug was a symptom. The module is a house of cards.

You could just ship the fix. Or you could make it right.

---

- [Ship the fix, file a ticket for tests](../sprint-review-good)
- [Add tests while you're here](../sprint-review-good)
- [Rewrite the whole auth module](./rewrite)
