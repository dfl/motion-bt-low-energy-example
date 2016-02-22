# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # app.sdk_version = "10.11"
  app.deployment_target = "8.4"

  # Use `rake config' to see complete project settings.
  app.name = 'bluetooth'
  # app.frameworks << 'CoreFoundation'
  app.frameworks << 'CoreBluetooth'

  app.identifier = 'com.pranawave.bt-test'
  # app.codesign_certificate = 'iOS Developer: David Lowenfels (David Lowenfels)'
  app.provisioning_profile = '/Users/dfl/work/rubymotion/Pranawave_local_development.mobileprovision'
end
