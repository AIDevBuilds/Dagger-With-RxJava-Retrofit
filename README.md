# Dagger with RxJava and Retrofit (Android)

Android sample that adds RxJava 2 and Retrofit to the Dagger 2 setup. It calls `GET /posts` on
[JSONPlaceholder](https://jsonplaceholder.typicode.com) through an injected network module.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- Dagger 2 components and modules, including a `NetworkModule` that builds the Retrofit client
- Retrofit 2.3.0 with the RxJava 2 call adapter and the Moshi converter
- A `PostApi` interface returning RxJava types, subscribed to with RxAndroid

## Stack

Java, Dagger 2.14.1, RxJava 2.1.9, RxAndroid 2.0.2, Retrofit 2.3.0, `minSdkVersion 15`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
