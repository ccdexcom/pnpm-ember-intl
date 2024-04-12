```
➜  pnpm-ember-intl git:(main) pnpm audit
┌─────────────────────┬────────────────────────────────────────────────────────┐
│ high                │ glob-parent vulnerable to Regular Expression Denial of │
│                     │ Service in enclosure regex                             │
├─────────────────────┼────────────────────────────────────────────────────────┤
│ Package             │ glob-parent                                            │
├─────────────────────┼────────────────────────────────────────────────────────┤
│ Vulnerable versions │ <5.1.2                                                 │
├─────────────────────┼────────────────────────────────────────────────────────┤
│ Patched versions    │ >=5.1.2                                                │
├─────────────────────┼────────────────────────────────────────────────────────┤
│ Paths               │                                                        │
├─────────────────────┼────────────────────────────────────────────────────────┤
│ More info           │ https://github.com/advisories/GHSA-ww39-953v-wcq6      │
└─────────────────────┴────────────────────────────────────────────────────────┘
1 vulnerabilities found
```

```
➜  pnpm-ember-intl git:(main) ✗ pnpm why glob-parent
Legend: production dependency, optional only, dev only

dependencies:
ember-intl 6.5.3
└─┬ broccoli-merge-files 0.8.0
  └─┬ fast-glob 2.2.7
    └── glob-parent 3.1.0
```
