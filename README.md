# NSLayoutConstraint+UIView
A simple class that makes it much easier to work with constraints in swift

## Usage

```swift
let label: UILabel = {
    let label = UILabel()
    label.text = "hello world!"
    label.textColor = .blue
    label.translatesAutoresizingMaskIntoConstraints = false
    return label
}()

parentView.addSubview(label)

label.centerXConstraint(parentView: parentView)
label.centerYConstraint(parentView: parentView)
label.widthConstraint(constant: 100)
label.heightConstraint(constant: 18)
```

## License

NSLayoutConstraint+UIView is released under the MIT license. See LICENSE for details.
