## FireFire

This is the documentation repository for the FireFire project.

### Origin of the idea

Volunteer firefighter organizations often use different technologies to alarm their volunteers. For example, Telephone calls, SMS and pagers are common in Switzerland. These technologies have their advantages and disadvantages.

Pagers and dedicated networks usually provide redundancy and service even in catastrophic situations. However, they are expensive units of hardware accompanied by a expensive service contract.
Alarm by telephone calls requires a large number of phone lines - and how long an alarm takes to reach everyone depends on the number of phone lines and on how fast the called individuals pick up.

On the other hand, the alarm center operators (911/112/118/...), the fire stations and their commanding officers don't have any information about the firefighters location and - only with some systems - if they can respond to an alarm.

### Idea

The idea of this project is to harness the possibilities of the digital and smartphone age.

In the event of an alarm:
* Provide officers and operators with the (approximate) location of their fire fighters
* Provide estimates for how long it takes until the fire fighters reach their fire station
 * Possibly split by specialists (for example: certified truck drivers, [SCBA](https://en.wikipedia.org/wiki/Self-contained_breathing_apparatus) users, etc.)
* Provide a feedback channel for fire fighters
 * Example: "Cannot respond" / "Will try to respond"
 * "Cannot respond" responses will allow operators to widen the alarm, if necessary

### Visions

Make the fire fighting forces smart!
These ideas are more of a stretch, but still realizable.

* Alarming by smartphone app
 * Using a push message systems like [APNS](https://en.wikipedia.org/wiki/Apple_Push_Notification_Service) or [FCM](https://firebase.google.com/docs/cloud-messaging/)
 * Not intended as a replacement all alarming systems, since such an app-based system will not have a service guarantee. For catastrophic events, network overload or failure, the fail-safe systems will still be required.
* Information for fire firefighters
 * Estimated drive-time to fire station in the event of an alarm
 * Current alarm situation (Any alarms in progress? How many fire fighters involved?)
 * Alarm cancellation
* Machine / Deep learning
 * How long until the first fire engine leaves?
* During deployment: Using sensors / beacons / trackers
 * Track location of fire fighters (on which fire truck, fire stations, or where otherwise)
 * Track locations of fire engines

### Ideals

* Privacy: Protect the data of fire fighters. If there is no alarm, only provide restricted data.
* Security: Make sure the system is as tamper-proof as possible.
* Reliability: Make the system as resilient and reliable as possible within its framework.
* Performance: Make the system as fast as possible without sacrificing any of the other ideals.

### Contributing

Right now, this project is just an idea.
If you're already interested: Great, you can help shape its future!

Right now, it's an idea of a single person. So we'll figure out a communication channel as we go.
For now, [file a bug or comment on one](https://github.com/firefire-ch/docs/issues) if you're interested to contribute!
