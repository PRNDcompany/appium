[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
# Stop Recording Screen

Stop recording screen
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
## Example Usage

```java
// Java
driver.stopRecordingScreen();
driver.stopRecordingScreen(new BaseStopScreenRecordingOptions(....));

```

```python
# Python
self.driver.stop_recording_screen()

```

```javascript
// Not supported
// wd example
await driver.stopRecordingScreen();

```

```ruby
# Ruby
# ruby_lib example
stop_recording_screen
stop_recording_screen remote_path: 'https://example.com', user: 'example', pass: 'pass', method: 'POST'

# ruby_lib_core example
@driver.stop_recording_screen
@driver.stop_recording_screen remote_path: 'https://example.com', user: 'example', pass: 'pass', method: 'POST'

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
// TODO C# sample

```


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
## Support

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### Appium Clients

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [static.javadoc.io](https://static.javadoc.io/io.appium/java-client/6.1.0/io/appium/java_client/screenrecording/CanRecordScreen.html#stopRecordingScreen--) |
|[Python](https://github.com/appium/python-client/releases/latest)| All |  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L3398) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#stop_recording_screen-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| None | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None | [github.com](https://github.com/appium/appium-dotnet-driver/) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
## HTTP API Specifications

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### Endpoint

`POST /session/:session_id/appium/stop_recording_screen`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### URL Parameters

|name|description|
|----|-----------|
|remotePath|The path to the remote location, where the resulting video should be uploaded. The following protocols are supported http/https, ftp. Null or empty string value (the default setting) means the content of resulting file should be encoded as Base64 and passed as the endpoint response value. An exception will be thrown if the generated media file is too big to fit into the available process memory.|
|username|The name of the user for the remote authentication.|
|password|The password for the remote authentication.|
|method|The http multipart upload method name. The 'PUT' one is used by default.|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### JSON Parameters

None

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
### Response

Base64 encoded string. If remote_path is set, the response is empty string. (`string`)

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/recording-screen/stop-recording-screen.yml)
## See Also

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L364)