# inclass_act07

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Team 2 pet personality

The undergraduate Visual polish & accessible motion bundle is implemented in
`lib/pet_personality/`. It includes mood tint and labels, derived speech,
animated meters, action bounce/reactions, and reduced-motion support.

Run the fixture preview with `flutter run -t lib/personality_preview.dart`.
Run checks with `flutter analyze` and `flutter test`.

See [the integration guide](docs/PET_PERSONALITY.md) for state inputs, action
notifications, customization, and learning outcomes. Asset provenance is in
[assets/ATTRIBUTION.txt](assets/ATTRIBUTION.txt). Team 1 still owns care rules,
timers, outcomes, and integration into the main screen. The combined
undergraduate app needs one additional advanced feature beyond this bundle.

[Component test results](docs/PET_PERSONALITY_TEST_RESULTS.md): analysis passed and all 13 tests passed.

`PetCareView` now supplies a reusable screen body with care-action callbacks and
pet-name confirmation. It is adapted to the Team 1 PR #1 state interface. The
care implementation and combined main.dart are deliberately outside this PR.
See the integration guide for the exact connection snippet.
