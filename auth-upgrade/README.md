# The Rabbit Hole

You start the auth upgrade. v2→v4 is a major version jump. The migration guide is 47 pages. Three breaking changes affect your codebase directly.

You estimate 2 weeks of careful, methodical work. Your manager said: "Don't spend more than a day on it."

*This is how Equifax happened.* In 2017, Apache Struts had a known CVE. Equifax knew about it for two months. Nobody patched it. 147 million social security numbers leaked. The CTO and CISO resigned. The company paid $700M in settlements.

Your auth library has known CVEs too. Nobody's touched it in 3 years.

---

- [Tell your manager it needs 2 weeks, properly scoped](../sprint-review-good)
- [Do what you can in a day, leave it half-done](../sprint-review-shaky)
- [Just do it, nights and weekends](./burnout)
