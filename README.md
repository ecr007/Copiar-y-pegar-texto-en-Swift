# Copiar-y-pegar-texto-en-Swift

```swift
//Copy
let pasteboard = UIPasteboard.general
pasteboard.string = "Hello, world!"

// Paste
if let string = pasteboard.string {
    // text was found and placed in the "string" constant
}
```
