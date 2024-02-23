# Uncomment the next line to define a global platform for your project
# platform :ios, '12.0'

target 'KeyboardFramework' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for KeyboardFramework

post_install do |installer|
  if installer.pods_project
    installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '12.0'
      end
    end
  end
end


pod 'IQKeyboardManagerSwift'


end
