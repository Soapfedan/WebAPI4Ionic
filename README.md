# WebAPI4Ionic
Ionic 4 project where WebAPIs will be implemented

## List of WebAPIs
MDN ref. https://developer.mozilla.org/en-US/docs/WebAPI

## Communication APIs

- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Network_Information" title="WebAPI/Network_Information">Network Information API</a>
     - Provides basic information about the current network connection, such as connection speed.
 - [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/WebBluetooth" title="WebAPI/WebBluetooth">Bluetooth</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
    - The WebBluetooth API provides low-level access to the device's Bluetooth hardware.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Mobile_Connection" title="WebAPI/Mobile_Connection">Mobile Connection API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Exposes information about the device's cellular connectivity, such as signal strength, operator information, and so forth.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Network_Stats" title="WebAPI/Network_Stats">Network Stats API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
    - Monitors data usage and exposes this data to privileged applications.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/WebTelephony" title="WebAPI/WebTelephony">Telephony</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Lets apps place and answer phone calls and use the built-in telephony user interface.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/WebSMS" title="WebAPI/WebSMS">WebSMS </a><span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Lets apps send and receive SMS text messages, as well as to access and manage the messages stored on the device.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/WiFi_Information" title="WebAPI/WiFi_Information">WiFi Information API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - A privileged API which provides information about signal strength, the name of the current network, available WiFi networks, and so forth.
  
  
## Hardware Access APIs

- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Using_Light_Events">Ambient Light Sensor API</a>
  - Provides access to the ambient light sensor, which lets your app detect the ambient light level in the vicinity of the device.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Battery_Status" title="WebAPI/Battery_Status">Battery Status API</a>
  - Provides information about the battery's charge level and whether or not the device is currently plugged in and charging.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/Using_geolocation" title="Using_geolocation">Geolocation API</a>
  - Provides information about the device's physical location.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Pointer_Lock" title="API/Pointer_Lock_API">Pointer Lock API</a>
  - Lets apps lock access to the mouse and gain access to movement deltas rather than absolute coordinates; this is great for gaming.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Proximity" title="WebAPI/Proximity">Proximity API</a>
  - Lets you detect proximity of the device to a nearby object, such as the user's face.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Detecting_device_orientation" title="WebAPI/Detecting_device_orientation">Device Orientation API</a>
  - Provides notifications when the device's orientation changes.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Managing_screen_orientation" title="WebAPI/Detecting_device_orientation">Screen Orientation API</a>
  - Provides notifications when the screen's orientation changes. You can also use this API to let your app indicate what orientation it prefers.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Vibration" title="WebAPI/Vibration">Vibration API</a>
  - Lets apps control the device's vibration hardware for things such as haptic feedback in games. This is <strong>not</strong> intended for things such as notification vibrations. See the <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Alarm" title="WebAPI/Alarm">Alarm API</a> for that.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Camera" title="WebAPI/Camera">Camera API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Allows apps to take photographs and/or record video using the device's built-in camera.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Power_Management" title="WebAPI/Power_Management">Power Management API </a><span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Lets apps turn on and off the screen, CPU, device power, and so forth. Also provides support for listening for and inspecting resource lock events.



## Data Management APIs

- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/FileHandle_API" title="WebAPI/FileHandle_API">FileHandle API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Provides support for writable files with locking support.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/IndexedDB" title="IndexedDB">IndexedDB</a>
  - Client-side storage of structured data with support for high-performance searches.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Settings" title="WebAPI/Settings">Settings API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Lets apps examine and change system-wide configuration options that are permanently stored on the device.


## Other APIs

- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Alarm" title="WebAPI/Alarm">Alarm API</a>
  - Lets apps schedule notifications. Also provides support for automatically launching an app at a specific time.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Simple_Push" title="WebAPI/Push_Notifications">Simple Push API</a>
  - Lets the platform send notification messages to specific applications.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/Web/API/Push_API">Push API</a>
  - Gives web applications the ability to receive messages pushed to them from a server, whether or not the web app is in the foreground, or even currently loaded, on a user agent.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Using_Web_Notifications" title="https://developer.mozilla.org/en-US/docs/WebAPI/Using_Web_Notifications">Web Notifications</a>
  - Lets applications send notifications displayed at the system level.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/Web/API/Apps" title="Apps">Apps API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - The Open WebApps API provides support for installing and managing Web apps. In addition, support is provided to let apps determine payment information.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Web_Activities" title="WebAPI/Web_Activities">Web Activities</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Lets an app delegate an activity to another app; for example, an app might ask another app to select (or create) and return a photo. Typically the user is able to configure what apps are used for which activities.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/Web/API/Payment_Request_API">Payment Request API</a>
  - Lets Web content initiate payments and refunds for virtual goods.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/DOM/Using_the_Browser_API" title="DOM/Using_the_Browser_API">Browser API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Provides support for building a Web browser completely using Web technologies (in essence, a browser within a browser).
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Idle" title="WebAPI/Device_Storage_API">Idle API</a>
  - Lets apps receive notifications when the user is not actively using the device.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Permissions" title="WebAPI/Permissions">Permissions API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Manages app permissions in a centralized location. Used by the Settings app.
- [ ] <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Time_and_Clock" title="WebAPI/Time_and_Clock">Time/Clock API</a> <span class="inlineIndicator nonstandardBadge" title="This API has not been standardized."><span class="badgeText"><b>Non-standard</b></span></span>
  - Provides support for setting the current time. The time zone is set using the <a href="https://developer.mozilla.org/en-US/docs/WebAPI/Settings" title="WebAPI/Settings">Settings API</a>.



  
 


