# Sentry SDK Boot Overhead — Lighthouse Benchmark

Next.js 14 (App Router) · production build · 3 Lighthouse navigation runs averaged.

| Metric | Baseline | With Sentry | Delta | % Change |
| --- | ---: | ---: | ---: | ---: |
| Total Blocking Time (ms) | 0 | 32 | +32 | n/a |
| Time to Interactive (ms) | 1508 | 2040 | +532 | +35.3% |
| First Contentful Paint (ms) | 615 | 614 | -1 | -0.1% |
| Speed Index (ms) | 615 | 614 | -1 | -0.1% |
| Performance Score | 100.0 | 100.0 | 0.0 | 0.0% |
| JS Transferred (KB) | 87.0 | 158.4 | +71.4 | +82.0% |
| Total Transferred (KB) | 88.8 | 160.2 | +71.4 | +80.4% |
