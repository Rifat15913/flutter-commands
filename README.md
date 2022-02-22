# Flutter Commands

## **General**
```yaml
flutter doctor --verbose
```

This command shows if the `flutter` environment setup is okay or not.


## **Dependencies**
```yaml
flutter —no-color pub outdated
```

This command checks for outdated dependencies.

```yaml
flutter pub upgrade
```

This command updates dependencies with compatibility.

```yaml
flutter pub upgrade --major-versions
```

This command updates dependencies with potentially breaking changes.

```yaml
flutter --no-color pub get
```

This command gets all the dependencies listed in the ***pubspec.yaml*** file in the current working directory, as well as their transitive dependencies.
