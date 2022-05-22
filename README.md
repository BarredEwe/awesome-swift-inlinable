<p align="center">
    <img src=".github/cover.png" width=60%/>
</p>
<p align="center">
    <a>List contains information about inlinable optimizations in Swift</a>
</p>

## WWDC
- [Binary Frameworks in Swift (from 28 minutes)](https://developer.apple.com/videos/play/wwdc2019/416/)

## Articles
- [Understanding @inlinable in Swift](https://swiftrocks.com/understanding-inlinable-in-swift)
- [The Forbidden @inline Attribute in Swift](https://swiftrocks.com/the-forbidden-inline-attribute-in-swift)
- [What is the advantage of saying your function should never be inlined?](https://catwolf.org/qs?id=dc4e5152-34f1-4c12-9ae7-a0ae7b21b76d&x=y)
- [Cross-module inlining and specialization](https://github.com/apple/swift-evolution/blob/master/proposals/0193-cross-module-inlining-and-specialization.md)
- [Swift Binary Optimizations](https://medium.com/@aslanyanhaik/swift-binary-optimizations-c13683d189fa)
- [Wikipedia - Inline function](https://en.wikipedia.org/wiki/Inline_function)

## Discussions
- [Effect of @inline(…) on nested functions](https://forums.swift.org/t/effect-of-inline-on-nested-functions/50202)
- [When should both @inlinable and @inline(__always) be used?](https://forums.swift.org/t/when-should-both-inlinable-and-inline-always-be-used/37375)

## Example of using
- [Swift - map function](https://github.com/apple/swift/blob/main/stdlib/public/core/Map.swift) by Apple
- [RxSwift - Atomic implimentation](https://github.com/ReactiveX/RxSwift/blob/1a1fa37b0d08e0f99ffa41f98f340e8bc60c35c4/Platform/AtomicInt.swift)
- [BetterCodable - LosslessValue (nested functions)](https://github.com/marksands/BetterCodable/blob/master/Sources/BetterCodable/LosslessValue.swift)
- [SwiftBinding (TensorFlow)](https://github.com/tensorflow/swift-bindings/blob/main/EagerExecution.swift.gyb)
