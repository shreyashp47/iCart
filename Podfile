# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'iCart' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  platform :ios, '13.0'
  
  # Pods for iCart
  pod 'FirebaseAnalytics'
  pod 'FirebaseAuth'
  pod 'FirebaseFirestore'
  pod "ESTabBarController-swift"
end



post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
    end
  end
end
