# Usage

Just workingfor swift.

```
#  Podfile

source 'https://github.com/loveforgeter/RACSpecs.git'
# Should explict include the cocoapods repo.
source 'https://github.com/CocoaPods/Specs.git' 

target 'App' do
  use_frameworks!

  pod 'ReactiveCocoa', '5.0.0-alpha.1'

  target 'AppTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'AppUITests' do
    inherit! :search_paths
    # Pods for testing
  end
end
```
