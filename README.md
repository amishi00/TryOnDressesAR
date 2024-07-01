# ARTryOnDresses
This is an augemented reality (AR) iOS application, built with echo3D Swift SDK that allows users to try on dresses virtually. Users also have the option of using their own 3D models to try on.

## Setup
In order to setup the app using the preselected dresses, follow these steps:
1. Open XCode or download it [here](https://developer.apple.com/xcode/).
2. Clone this repository and open in XCode on computer.
3. Go to the "Signing & Capabilities" tab in Xcode and fill out your signing information.
4. Connect your iPhone/iPad to computer.
5. Select your device on the dropdown list of devices to run the demo app on.
  <img width="600" alt="image" src="https://github.com/amishi00/TryOnDressesAR/assets/98851347/172cf25f-5eda-498b-83d7-55de27d590e7">


7. Press the Play button to build and run (Note: your device must be unlocked and in Developer Mode to run).

## Run
- Move your phone around a horizontal surface to scan a plane.
- If the "Add" button is selected, choose an object to add and touch somewhere on your horizontal plane to add it.
- If any other edit buttons are selected such as drag, rotate, or delete, tap or drag on the object you would like to edit.
- Objects can be scaled at any time by doing the two finger pinch gesture on them.
  <img width="300" alt="image" src="https://github.com/amishi00/TryOnDressesAR/assets/98851347/e8630e88-bac1-4673-9bd5-828a071c0258">


## Using your own 3D models
1. Register for FREE at [echo3D](www.echo3D.com).
2. Open ARTryOnDresses.xcodeproj using Xcode (Note: If you have Xcode downloaded you simply double click the file to open).
3. Go to the "Signing & Capabilities" tab in Xcode and fill out your signing information. See more details [here](https://docs.echo3d.co/swift/adding-ar-capabilities).
4. Go to the Echo3D.swift file and insert your API key as a string where it says "insert API key here".
5. [Add models to the echo3D console](https://docs.echo3d.co/quickstart/add-a-3d-model) or choose from our library
6. Go to the ViewController.swift file, add the entry ID's for 3D content you have added to your echo3D console where it says "insert entry ID here".
 ![image](https://github.com/amishi00/TryOnDressesAR/assets/98851347/dd9fd584-faf1-4708-a9c9-f87c572d52fa)

7. Connect your iPhone/iPad to computer.
8. Select your device on the dropdown list of devices to run the demo app on.
9. Press the Play button to build and run (Note: your device must be unlocked and in Developer Mode to run).

## Learn More
Refer to our [documentation](https://docs.echo3d.com/swift/installation) to learn more about how to use echo3D and the Swift SDK.
## Support
Feel free to reach out at [support@echo3D.co](support@echo3D.co) or join our [support channel on Slack](https://go.echo3d.co/join).

