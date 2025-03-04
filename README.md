# CocoaPods Setup

To set up your project with CocoaPods, add the following to your `Podfile`:

```ruby
source 'https://github.com/idoosmart/IDOSmartSpec.git'
platform :ios, '12.0'

target 'your_target_name' do
    pod 'IDOSifliSDK'
end
```

Then, run the following command to install the dependencies:

```sh
pod install
```

