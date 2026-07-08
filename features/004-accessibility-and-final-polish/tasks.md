# Tasks — 004 Accessibility Final Polish

Version: 1.0
Status: Pending Approval

---

- [ ] Task 1: Add skip-to-content link as first child of `<body>` — hidden until focused.
- [ ] Task 2: Add `aria-label="Main navigation"` to `<nav>`.
- [ ] Task 3: Add `aria-label="Main content"` to `<main>`.
- [ ] Task 4: Add `aria-labelledby` or proper heading association to sections if needed.
- [ ] Task 5: Verify heading hierarchy — no skipped levels (h1 → h2 → h3 only).
- [ ] Task 6: Add `tabindex="-1"` to all section targets so skip link and sidebar links focus correctly.
- [ ] Task 7: Ensure all sidebar `<a>` elements have `href` and are keyboard-focusable.
- [ ] Task 8: Add or improve `:focus` and `:focus-visible` styles for all interactive elements.
- [ ] Task 9: Simulate full Tab navigation — document every stop, ensure logical order.
- [ ] Task 10: Verify skip link: first Tab shows it, Enter jumps to main content.
- [ ] Task 11: Test 200% zoom — ensure no horizontal scroll, no overlapping elements.
- [ ] Task 12: Verify all font sizes use relative units (rem, em, %).
- [ ] Task 13: Audit color contrast for all text — normal text 4.5:1, large text 3:1 minimum.
- [ ] Task 14: Fix any contrast issues found.
- [ ] Task 15: Verify font stack includes system fallbacks for all OS.
- [ ] Task 16: Test responsive: 320px, 375px, 768px, 1024px, 1440px, 2560px — fix any breakage.
- [ ] Task 17: Verify `prefers-reduced-motion` wraps ALL animations, transitions, keyframes.
- [ ] Task 18: Verify all `id` attributes are unique across the page.
- [ ] Task 19: Add `alt=""` or `aria-hidden="true"` to any decorative images/icons.
- [ ] Task 20: Confirm Feature 001 structure is completely untouched.
- [ ] Task 21: Confirm zero JavaScript.
- [ ] Task 22: Validate HTML — zero W3C errors.
- [ ] Task 23: Run full self-evaluation against spec.md audit checklist — do not skip any item.
- [ ] Task 24: Only report completion if every single audit item passes with 100% confidence.