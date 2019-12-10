# NSLayoutConstraint+UIView
A simple class that makes it much easier to work with constraints in swift

## Usage

```swift
private lazy var someLabel: UILabel = {
    let label = UILabel()
    label.text = "hello world!"
    label.textColor = .blue
    label.translatesAutoresizingMaskIntoConstraints = false
    return label
}()

parentView.addSubview(someLabel)

someLabel.centerXConstraint(parentView: parentView)
someLabel.centerYConstraint(parentView: parentView)
someLabel.widthConstraint(constant: 100)
someLabel.heightConstraint(constant: 18)
```

## License

NSLayoutConstraint+UIView is released under the MIT license. See LICENSE for details.
