source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '10.0'
use_frameworks!
inhibit_all_warnings!

abstract_target 'AbstractStuff' do
  pod 'Result', :configurations => ['Debug']
  
  target 'One' do
  	pod 'Async', :configurations => ['Debug']
  end

  target 'Two' do
    pod 'Reusable', :configurations => ['Release']
  end
end
