# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Tools' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
	pod 'DialCountries'
#  pod 'AWSMobileClient'
#  pod 'AWSPinpoint'
  pod 'GoogleSignIn'
  pod 'Toast-Swift'
  pod 'EasyTipView'
  pod 'DropDown'
  pod 'IQKeyboardManager'
  pod 'Kingfisher', '~> 7.0'
#  pod 'LanguageManager-iOS'
  pod 'PureLayout'
  pod "PostHog", "~> 1.1"
  # Pods for Tools
  pod 'FirebaseCrashlytics'
  pod 'Firebase/RemoteConfig'
  pod 'DGCharts'
  pod 'UXCam'

  target 'ToolsTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'ToolsUITests' do
    # Pods for testing
  end
  post_install do |installer|
    installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '11.0'
      end
    end
  end
  
  
end

