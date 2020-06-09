# Quizzler ❓

A new Flutter application.

## What I have tried

![Finished App](https://github.com/londonappbrewery/Images/blob/master/quizzler-demo.gif)

## Getting Started
* Install dependencies
```sh
    $ flutter pub get
```

* Start building  
Use emulator or a physical device connected by USB
```sh
    $ flutter run
```

* Create APK
```sh
    $ flutter build apk --split-per-abi
```

### Install for Android
- [64 bit apk](https://www.github.com/raj-vora/quizzler-flutter/blob/master/apks/quizzler-arm64.apk?raw=true)
- [32 bit apk](https://www.github.com/raj-vora/quizzler-flutter/blob/master/apks/quizzler-armeabi.apk?raw=true)


## How to customise the quiz for your need (as a developer)
Replace

```
List<Question> _questionBank = [
    Question('Some cats are actually allergic to humans', true),
    Question('You can lead a cow down stairs but not up stairs.', false),
    Question('Approximately one quarter of human bones are in the feet.', true),
    Question('A slug\'s blood is green.', true),
    Question('Buzz Aldrin\'s mother\'s maiden name was \"Moon\".', true),
    Question('It is illegal to pee in the Ocean in Portugal.', true),
    Question(
        'No piece of square dry paper can be folded in half more than 7 times.',
        false),
    Question(
        'In London, UK, if you happen to die in the House of Parliament, you are technically entitled to a state funeral, because the building is considered too sacred a place.',
        true),
    Question(
        'The loudest sound produced by any animal is 188 decibels. That animal is the African Elephant.',
        false),
    Question(
        'The total surface area of two human lungs is approximately 70 square metres.',
        true),
    Question('Google was originally called \"Backrub\".', true),
    Question(
        'Chocolate affects a dog\'s heart and nervous system; a few ounces are enough to kill a small dog.',
        true),
    Question(
        'In West Virginia, USA, if you accidentally hit an animal with your car, you are free to take it home to eat.',
        true),
]

```  
with a list of your own questions with boolean answers  
  
Or else update [question.dart](https://github.com/raj-vora/quizzler-flutter/blob/master/lib/question.dart) to your own class of questions and make necessary changes in (main.dart)[https://github.com/raj-vora/quizzler-flutter/blob/master/lib/main.dart] and (quiz_brain.dart)[https://github.com/raj-vora/quizzler-flutter/blob/master/lib/quiz_brain.dart].  

>This is a companion project to The App Brewery's Complete Flutter Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)
