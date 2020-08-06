Example configuration to show how to use the git commit hash as the artifact/image version.

Additionally, I prefix the commit hash with the commit timestamp for better human readability ("20190101-101010.7555485").

- `mvn package` to build the jar, wrap it in a docker image and install the image to the local registry.
- `mvn deploy` to push the image to the docker registry.
