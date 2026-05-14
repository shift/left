# The Suspicious Package

> 📍 Day 1 · 0 decisions made

A new contributor submits a PR to fix a "performance issue" in your build tooling. The code looks fine. The tests pass. But something feels off.

The contributor's GitHub profile is 2 weeks old. The fix involves downloading and executing a binary from an S3 bucket. The binary is compiled — you can't read the source.

*In 2021, a researcher demonstrated that they could get a malicious PR merged into 17 major open-source projects by submitting "helpful" patches that included subtle backdoors. The technique is called "dependency confusion." The researcher got hired. A real attacker would not have been so gentle.*

---

- [Reject it — require source, not binaries](../framed-well)
- [Accept it — the tests pass](./compromised)
- [Run it in a sandbox first](../framed-well)

**3 choices — there is no going back.**

