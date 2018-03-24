# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'NimbleNSEnum' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for NimbleNSEnum

  target 'NimbleNSEnumTests' do
    inherit! :search_paths
    # Pods for testing
    pod 'Nimble'
  end

end


post_install do |installer|
  installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
          config.build_settings['SWIFT_VERSION'] = 4.0
      end
  end
end
