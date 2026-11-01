# tracker-store-testkit

Published Tracker store test builds for automancer-dashboard `apps/tracker` (t12429): each release `store-<commit>` carries the `@automancer/tracker-store` npm tarball — the vendored estate-watch rules, the store's own tools and migrations as an in-process store over `node:sqlite`, for another repository's CI (e.g. estate-watch's `npm test`) without a cross-repository credential or hosted call.

Install a build:

```
npm install "https://github.com/Automancer-Ltd/tracker-store-testkit/releases/download/store-<commit>/automancer-tracker-store-<version>.tgz"
```

API: `import { createTrackerStore } from "@automancer/tracker-store"` — see `apps/tracker/README.md` in `Automancer-Ltd/automancer-dashboard`.
