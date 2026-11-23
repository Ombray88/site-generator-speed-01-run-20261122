# Site Generator Speed Solver

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Ombray88/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Ombray88/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

A high-performance standalone static site generation engine built for the make.fun competition. It processes site definitions, parses front matter and Markdown, evaluates custom templates, and outputs a complete static site tree without external dependencies.

Competition page: https://make.fun/bounty/site-generator-speed-01-run-20261122

## Usage

Run via TypeScript runner with V8 optimizations:

```bash
npx tsx main.ts
```

## Performance

Achieves substantial speedups over the reference baseline by eliminating module overhead, streamlining internal data structures, and optimizing text rendering pipelines.
