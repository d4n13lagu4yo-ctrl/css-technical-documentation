# Constitution

Version: 1.0
Status: Active

---

# Purpose

This document defines the permanent, non-negotiable rules of the CSS Technical Documentation project.

No feature, decision, or implementation may contradict this document.

This document may only be modified with explicit user approval.

---

# Core Principles

## Principle 1 — HTML and CSS Only

The project uses only HTML and CSS.

JavaScript and any other programming language are strictly forbidden.

No exceptions.

---

## Principle 2 — Feature 001 is Immutable

Feature 001 is the foundation of the project.

It must never be modified.

No feature may contradict Feature 001.

If a requested change conflicts with Feature 001, the AI must stop and report the conflict.

---

## Principle 3 — Accessibility First

The project must be accessible to all users.

Requirements:

- Full keyboard navigation (tab, focus indicators)
- Screen reader compatibility
- Semantic HTML structure
- Proper heading hierarchy
- Sufficient color contrast
- Readable font sizes
- Voice control compatibility
- ARIA attributes where appropriate

Accessibility is not optional.

---

## Principle 4 — Responsive Design

The site must work on all screen sizes:

- Mobile: ~320px and above
- Tablet: ~768px and above
- Laptop: ~1024px and above
- Desktop: ~1440px and above

Breakpoints must be defined and consistent.

---

## Principle 5 — Browser Compatibility

The site must work on all major browsers.

All fonts must have fallback stacks.

CSS properties must use vendor prefixes when necessary.

No browser-specific features without graceful degradation.

---

## Principle 6 — Professional Aesthetic

The project must maintain a professional appearance.

Forbidden:

- Extravagant colors
- Excessive animations
- Bad practices (inline styles, !important abuse)
- Unreadable typography

Allowed:

- Subtle, professional animations
- Clean color palette
- Consistent spacing
- Clear typography

---

## Principle 7 — Performance

The site must load fast and perform well on all devices.

Requirements:

- Optimized CSS
- Minimal dependencies
- No render-blocking resources
- Smooth animations (respect prefers-reduced-motion)

---

## Principle 8 — Feature Workflow Compliance

Every feature must follow the workflow defined in AI-WORKFLOW.md and FEATURE-WORKFLOW.md.

Documentation must follow DOCUMENT-STANDARDS.md.

No step may be skipped.

---

## Principle 9 — Sequential Development

Features are developed one at a time, in sequential order.

No parallel features.

A new feature starts only after the previous one is approved and documented.

---

## Principle 10 — User Authority

The user has final authority on all decisions.

The AI must never assume requirements, skip approval, or modify immutable elements.

---

# Restrictions

- No JavaScript
- No frameworks (React, Vue, Angular, etc.)
- No CSS frameworks (Bootstrap, Tailwind, etc.) unless explicitly approved
- No backend languages
- No database
- Feature 001 must remain unchanged forever

---

# Violations

Any implementation that violates these principles must be:

1. Stopped immediately
2. Reported to the user
3. Corrected before continuing

---

# End of Document