# PodDemo
### Using [CocoaPods](http://cocoapods.org)
1. Create project `PodDemo` from XCode.
2. `cd PodDemo` RootDirectory from Terminal.
3. Add your Podfile for `vim Podfile` from Terminal, [Podfile](http://guides.cocoapods.org/using/the-podfile.html).

  ```ruby
  
platform :ios, "8.0"
target "PodDemo" do
pod 'AFNetworking'

end

  ```
  
4. Run `pod install` from Terminal, then open your app's `.xcworkspace` file to launch Xcode.

5. Import the `AFNetworking.h` umbrella header.
