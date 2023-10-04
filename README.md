# Hello!

Let me present myself in a dart code...

This code is a snippet from this [gist](https://gist.github.com/ElanDeyan/eb66d269e1abd78ddb3ac5266cf82f64).

```dart
final class ElanDeyan extends Programmer with Entusiasm implements Person {
  ElanDeyan();

  @override
  String get name => 'Elan Deyan';

  // Interests
  final studiesTheBible = true;
  final lovesTheNature = true;
  final favoriteSports = <String>{'Soccer/Football'};
  final interestedInMath = true;

  // Curiosity
  final wantsToLearnNewThings = true;

  @override
  Set<String> get learning => <String>{'Dart'};

  @override
  int get age {
    final bornDate = DateTime.parse('2002-07-16');
    final todayDate = DateTime.now();

    return todayDate.difference(bornDate).inDays ~/ 365.25;
  }

  @override
  Hand get dominatingHand => Hand.left;

  @override
  String get nativeLanguage => 'Brazilian portuguese';

  @override
  Map<String, String> get englishUnderstanding => {
        'speech': 'basic',
        'reading': 'more than basic',
        'hearing': 'basic',
        'write': 'basic'
      };
}
```
