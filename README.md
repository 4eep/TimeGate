## TimeGate

![Screenshot_2](https://github.com/user-attachments/assets/4d006964-c79c-494a-a832-200de1bed5c9)

* [Exmple Project](https://github.com/4eep/TimeGate/releases/download/ue5.4/Example.Project.zip)
* [Description](#Description)
* [Important](#Important)
* [Requirement](#Requirement)
* [Installation](#Installation)
* [Usage](#Usage)
* [Screenshots](#Screenshots)
* [Fab](https://www.fab.com/ru/portal/listings/de1f10cb-ccae-407b-8011-70f02996aa1a)

## Description

TimeGate is a lightweight plugin for Unreal Engine that allows you to restrict the launch of your project by date. Ideal for freelancers and developers who need to protect their build from unauthorized use.

🔗 Online check of current date via API https://timeapi.io

🧠 Comparison with a given date

💬 Events (Async Blueprint) for processing results

✅ Works completely in Blueprints, without the need to write code

🧩 Compatible with Windows, Linux, Android and other platforms

# ⚠️ Important:

- Internet connection is required when running the build

- The plugin does not guarantee absolute protection against hacking, but it complicates unauthorized use

## Requirement

Target version : UE5.4 ～ 5.6
Target platform : All  
Test platform : Windows 

## Installation

Put the TimeGate folder in your project's Plugins folder. Or install the plugin via [Fab](https://www.fab.com/ru/portal/listings/de1f10cb-ccae-407b-8011-70f02996aa1a)
If the feature is not available after installing the plugin, it is possible that the plugin has not been enabled, so please check if the plugin is enabled from Edit > Plugins.

## Usage

Call the "CheckTimeGate" function anywhere in blueprints.
Pass the FDateTime to be checked and the desired time zone. If you are not sure about the correctness of the entered time zone, you can check. "Timeout" sets the time to wait for a response from the server.
You can see the list of supported time zones at [timeapi.io](https://timeapi.io/api/TimeZone/AvailableTimeZones).

## Screenshots
![TimeGate](https://github.com/user-attachments/assets/886fb40a-3512-4b5b-a87d-745293a3e0f2)
