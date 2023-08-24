# Build
custom_build(
  # Name of the container
  ref = 'config-server',
  # Command to build the container image
  command = './gradlew bootBuildImage --imageName $EXPECTED_REF',
  # Files to watch that trigger a new build
  deps = ['build.gradle', 'src']
  )

  # Deploy