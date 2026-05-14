# The Left-Pad Situation

> 📍 Late Game · 5 decisions made

Your app breaks. Not because of your code — because of a dependency you didn't know you had.

Someone unpublished a package from npm. It was 11 lines of code. Your app transitively depended on it through 6 layers of indirection. Now your build is broken. So is half the internet.

Your `package-lock.json` hasn't been updated in 4 months. Your dependencies have 47 known vulnerabilities, according to `npm audit`.

---

- [Pin dependencies, add a lockfile, set up Dependabot](../framed-well)
- [Fix the immediate break, move on](../feature-factory)
- [We control our dependencies — vendor everything](./vendor)
