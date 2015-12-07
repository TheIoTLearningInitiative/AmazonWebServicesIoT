# Lesson 3: Create an IoT device

Things are applications, connected devices, or physical objects that are supported by your cloud application. AWS IoT includes the Registry and Device Shadows, so you can register any Thing you wish to represent in the cloud with a name, some attributes, and a persistent virtual 'shadow'.

The Registry: You can use thing attributes to describe the identity or capabilities of your device. For example, you can describe whether a sensor reports temperature, and if the data are Fahrenheit or Celsius. You can also use attributes to search/filter within a list of things.

The Registry lets you store attributes at no additional charge, and metadata in the Registry does not expire as long as you access or update your Registry entry at least once every 7 years.

Click here to learn more about the Registry.

Device Shadows: Device Shadows are a persistent virtual version of each thing that includes the thing's last reported state and desired future state, even when the underlying thing is not connected.

You can retrieve the last reported state of a thing or set the desired future state through the API or using the rules engine.

Device Shadows let you store the state of your things for up to a year at no additional charge. Shadows persist forever if you update them at least once per year, otherwise they expire.

Click here to learn more about Device Shadows.