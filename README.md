# Seald SDK demo app Flutter

This is a basic app, demonstrating use of the Seald SDK for Flutter for iOS and Android.

You can check the reference documentation at <https://pub.dev/documentation/seald_sdk_flutter/latest/>.

The main file you could be interested in reading is [`./lib/main.dart`](./lib/main.dart).

Before running the app, you have to install the dependencies, with the command `flutter pub get`.

Also, it is recommended to create your own Seald team on <https://www.seald.io/create-sdk>,
and change the values of `app_id`, `jwt_shared_secret_id`, and `jwt_shared_secret`, that you can get on the `SDK` tab
of the Seald dashboard settings, as well as `ssks_backend_app_key` that you can get on the `SSKS` tab,
in `./lib/credentials.dart`,
so that the example runs in your own Seald team.

Finally, to run from the CLI, use the command `flutter run`.
