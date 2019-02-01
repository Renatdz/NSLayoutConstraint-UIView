# NSLayoutConstraint-UIView
A simple class that makes it much easier to work with constraints in swift

## Usage

```swift
lazy var label: UILabel = {
    let label = UILabel(frame: .zero)
    label.translatesAutoresizingMaskIntoConstraints = false
    label.text = "hello world!"
    label.textColor = .black
    return label
}()

parentView.addSubview(label)

label.centerXConstraint(parentView: parentView)
label.centerYConstraint(parentView: parentView)
label.width(100)
label.height(18)
```

## License

NSLayoutConstraint+UIView is released under the MIT license. See LICENSE for details.
