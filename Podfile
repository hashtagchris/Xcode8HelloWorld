platform :ios, '8.0'
use_frameworks!
project 'Xcode8HelloWorld.xcodeproj'

target 'Xcode8HelloWorld' do
  pod 'AFNetworking', '~> 2.6'
  pod 'ORStackView', '~> 3.0'
  pod 'SwiftyJSON', '~> 2.3'
end

post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings.add('CODE_SIGNING_ALLOWED', 'NO')
        config.build_settings.add('CODE_SIGNING_REQUIRED', 'NO')
    end
end
