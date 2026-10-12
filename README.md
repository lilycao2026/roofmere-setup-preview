# roofmere-setup-preview

Roofmere guided setup wizard. Open `index.html` in a browser.

## Versions

- `index.html` — current 3-step wizard: Database → Website → Launch.
- `archived/setup-6-steps.html` — previous 6-step wizard, kept unchanged so it can be restored at any time. It uses the same images in `setup-assets/`.
  Commit `992c7a2` is the last commit where the 6-step wizard was `index.html`.

To roll back, copy `archived/setup-6-steps.html` over `index.html` and change `../setup-assets/` back to `setup-assets/`, or check out `index.html` from that commit:

```
git checkout 992c7a2 -- index.html
```

The two versions save progress under different browser keys, so switching between them does not mix up checklists.
