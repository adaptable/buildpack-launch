# Adaptable Launch Buildpack

Sets the launch command for a buildpack image.

## Configuration

### `BP_LAUNCH_COMMAND`

Set `BP_LAUNCH_COMMAND` to a JSON-encoded string to set the launch command for the image.
This buildpack does no work if `BP_LAUNCH_COMMAND` is not set or is empty.
