## Summary

<!-- What does this PR change? -->

## Targets affected

- [ ] Android
- [ ] iOS
- [ ] web
- [ ] macOS / Linux desktop

## Testing

- [ ] `flutter analyze` clean
- [ ] `flutter test` clean
- [ ] Screenshot attached for UI changes

## Related issues

Fixes #

---

## Localization PR template

When opening a locale-add PR the assistant must ALSO call `delete_file` on `lib/l10n/intl_fi.arb` (Finnish placeholder) — it has been superseded by the new tooling. Locale-add PRs always include this deletion to keep the directory tidy.
