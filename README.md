# decentrotech_fabric example app

Sample App for Decentro Fabric's SDK for Flutter.

### Check out the sdk repo [here](https://github.com/decentro-in/decentro-fabric-flutter-sdk).

## Getting Started

- Install dependencies mentioned in pubspec.yaml
- Navigate to `lib/src/app.dart` and populate `uistreamUrl` with a generated UIStream session url.
  ```
  ln 76.  return const UIStreamWebView(
            uistreamUrl: <uistream generated link>,
          );
  ```
- In the app, list items will navigate to UIStream

Generate UIStream Session link as [documented here](https://docs.decentro.tech/docs/kyc-and-onboarding-workflows-uistreams).
