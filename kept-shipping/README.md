# The Breaking Point

> 📍 Late Game · 6 decisions made

Friday, 4:47pm. You just merged a feature. CI is green. You're reaching for your bag when Slack explodes.

`#incidents` — **P1: PAYMENT SERVICE DOWN**

Your feature touched the payment service's dependency chain. You didn't know it was in the dependency chain because there are no architecture docs. Customers are being double-charged.

*This is the Knight Capital pattern.* On August 1, 2012, Knight Capital deployed new trading software. They deployed to 8 servers. One of the 8 was running old code that was reactivated by the new deployment. In 45 minutes, that one server executed 4 million trades. Loss: $440 million. The company was bankrupt in a week. The root cause: they didn't know which servers were running which code.

---

- [Revert immediately](https://github.com/shift/right/tree/main/emergency)
- [Try to fix forward](./fix-forward)
- [Wait for someone else to handle it](./hide)

*3 choices. There is no going back.*
