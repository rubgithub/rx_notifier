## [2.3.0] - 2023-06-26
* Added `setValueWithoutReaction`;

## [2.2.4] - 2023-06-08
* Fix callback error

## [2.2.2] - 2023-04-22
* Fix: Clear and addAll RxMap without rebuilding N times? #9.
* Fix: Fix disposers list cleaning before disposing all RxDisposers

## [2.2.1] - 2023-03-16
* @Deprecated [RxAction]. Use [RxNotifier] instead.
* [feat]: Added `RxNotifier.call` for re-call all the registered listeners.

## [2.2.0+2] - 2023-03-05
* Added [rxNext] function for wait the next change of a [RxNotifer].
* Added [RxNotifier.next];
* Refactor: [RxAction].

## [2.1.0] - 2023-03-01
* Added [RxCallback] Widget.
* Added `context.callback()`. 

## [2.0.0+6] - 2023-02-22

* (Breaking change) - `RxNotifier.value` now accept equal values. <br>
The ValueNotifier does not propagate if the changed value is the same.
* Flutter State management with `RxRoot` and `context.select` (Check documentation);
* (Deprecated) `RxMixin` (Use `RxRoot` or `RxBuilder` instead).
* Added `RxAction`.
* Added `RxReducer`.
* Update documentation.
* Up Dart version to >=2.17.


## [1.1.0] - 2021-03-29

* RxFuture: Added **.value** for add a new Future;
```dart
final rxFuture = RxFuture.of(myFuture);
...

rxFuture.value = newFuture;
```
## [1.0.0] - 2021-03-03

* Added Collections (RxList, RxSet, RxMap);
* Added async (RxFuture, RxStream);

