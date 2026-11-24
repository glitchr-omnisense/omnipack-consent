# Changelog

## 2.2.1

- The floating panel no longer moves for Symfony's web debug toolbar: nothing of the page reacts to the profiler. The
  panel stays where `consent.position` puts it, the toolbar open or closed; making way is the toolbar's to do
  (glitchr/symfony-profiler-pack's floating toolbar steps aside for the page's panels).

## 2.2.0

- `Consent.grant(name)`: one declared feature on, the others keeping their answer - the visitor's yes given where it
  is asked rather than in the panel (omnipack/music's films: "Played by YouTube... Play"). Queued like `accept()` when
  called before the library is there; `false` for a feature nobody declared.
- The panel opened again after the answer (the circle, a page's own "cookie settings") comes in as the floating one
  does, fading up, instead of appearing at once.

## 2.0.1

- The automatic-choice countdown keeps its seconds with their number: a no-break space around `{count}` in the five
  languages, so "10 s" never splits across two lines.
- The floating panel clears Symfony's floating debug toolbar only while the toolbar is open and shown.

## 2.0.0

omnibase/consent: the cookie consent panel shared by the omnibase sites - features, choices remembered, Consent.use() - on omnisense/omnibase 7.0.
