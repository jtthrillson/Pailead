# Pailead

Pailead works just like the Palette library on Android and other tools like node-vibrant but is
completely written in Swift and optimized for macOS and iOS.

### Usage
```swift
let image = <#Image#>
Pailead.extractTop(10, from: image) { colors in
<#Do Something with Colors#>
}
```

### Todo
- [ ] Switch to swatches
- [ ] Paralleize pixel extraction
- [ ] Add more performance tests
- [ ] Make better docs with example uses
- [ ] Optimize processing loop
- [ ] Add support for other clustering algorithms

### Name

If palette is pronounced *pa-let* then Pailead is pronounced *pa-lid*.

The word comes from the Irish word paileád meaning palette which is what this library extracts.

### Author
- @pducks32 (Patrick Metcalfe, git@patrickmetcalfe.com)
