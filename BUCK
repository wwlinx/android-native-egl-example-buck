project_config(src_target = ':testapp')

android_binary(
  name = 'testapp',
  manifest = 'AndroidManifest.xml',
  target = 'Google Inc.:Google APIs:14',
  keystore_properties = 'debug.keystore.properties',
  deps = [ ':testapp_lib' ],
)

android_library(
  name = 'testapp_lib',
  srcs = glob(['src/**/*.java']),
  deps = [ '//jni:jni' ])
