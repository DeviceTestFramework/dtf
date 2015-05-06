# Device Test Framework

The Device Test Framework is a set of Python tools to make it as easy as possible to write tests that verifies the functionality of a device.

To interact with the devices a subproject "dctrl" is used, that internally uses Pexpect to run commands on the device via several connections and verify that the expected output is returned.
