# QA Protocol

## Visual
Inspect actual rendered output at wide desktop, laptop/tablet and narrow mobile. Check first viewport, full progression, footer, overlays and key states. Compare against approved frames.

## Functional
Test navigation, forms, links, buttons, menus, media, error states and integrations. No dead controls or placeholder destinations in final delivery.

## Responsive
Check overflow, clipping, sticky behavior, image crops, typography, touch targets and orientation.

## Accessibility
Keyboard pass, focus order/visibility, semantics, labels, contrast, zoom/reflow, reduced motion and screen-reader checks where available.

## Performance/content
Measure media, JS, fonts, layout shifts, long tasks and GPU load. Check factual accuracy, spelling, headings, metadata, social previews, links and localization.

## Defect log
| ID | Severity | Environment | Steps | Expected | Actual | Status |
|---|---|---|---|---|---|---|

Mark Pass / Fail / Not tested. A screenshot proves one visual state, not responsiveness or functionality. Never convert Not tested into Pass.
