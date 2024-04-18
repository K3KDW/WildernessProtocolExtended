# Wilderness Protocol Extended
The original Wilderness Protocol from QST Feb 1994 sets a standard for emergency communication when outside repeater range. "Extended" adds functionality for users outside of Amateur Radio (HAM Radio) and includes beyond line of sight options.

## QUICK REFERENCE

    TIME (LOCAL)           FREQ./CHAN. PRIORITY
    7:00   -  7:05 AM      #1  146.52 MHz Analog FM
    10:00  -  10:05 AM     #2  GMRS/FRS 19
    1:00   -  1:05 PM      #3  446.0 MHz Analog FM
    4:00   -  4:05 PM      #4  28.4 MHz USB
    7:00   -  7:05 PM      #5  7.030 MHz CW
    10:00  -  10:05 PM     (If possible,
    1:00   -  1:05 AM      monitor two in order
    4:00   -  4:05 AM      listed above.)
    

### Activity Times are the first 5 minutes of the hour, every 3 hours, starting at 7 AM local.
Where applicable, monitor adjacent time zones.

-  7:00   -  7:05 AM
-  10:00  -  10:05 AM
-  1:00   -  1:05 PM
-  4:00   -  4:05 PM
-  7:00   -  7:05 PM
-  10:00  -  10:05 PM
-  1:00   -  1:05 AM
-  4:00   -  4:05 AM

### Frequency/Channel selection. Use the first frequency or channel your radio is capable of beginning at the top of the list.
-  #1  146.52 MHz Analog FM  (2 meter ham radio calling frequency.)
-  #2  GMRS/FRS 19           (GMRS and FRS radios share frequencies. Channel 19 is the "main" talk channel. 462.65 MHz FM. Shout to NotARubicon!)
-  #3  446.0 MHz Analog FM   (70 cm ham radio calling frequency.)
-  #4  28.4 MHz USB          (10 meter ham radio calling frequency.)
-  #5  7.030 MHz CW          (40 meter ham radio QRP center of activity. See notes below.)

Users without battery concerns should monitor as often as possible. At minimum they should monitor for the first 5 minutes of every hour. If practical, users near local events, common commuting routes, and popular outdoor areas should consider monitoring continuously during these events.

If nothing is heard for the first 4 minutes or so, it is helpful to announce your presence to help establish the "network".
Users should expect to act as a relay for others. In mountainous or otherwise difficult terrain it may not be possible to communicate directly from deep terrain to outside assistance. It may be necessary for multiple users to relay messages back and forth. This takes additional time and careful coordination so patience and careful coordination are critical. Users may not be able to hear each "link" in the relay chain. A long pause in communication that otherwise appears to be going smoothly may not indicate a problem. If in doubt, reach out! Otherwise keep quiet so the established relays can work effectively.

### If your radio is capable of monitoring two of the above frequencies at once, please monitor the following hierarchy on the second slot. The same applies if you have multiple radios.
-  Secondary #1  GMRS/FRS 19           (GMRS and FRS radios share frequencies. Channel 19 is the "main" talk channel. 462.65 MHz FM. Shout to NotARubicon!)
-  Secondary #2  446.0 MHz Analog FM   (70 cm ham radio calling frequency.)
-  Secondary #3  28.4 MHz USB          (10 meter ham radio calling frequency.)
-  Secondary #4  7.030 MHz CW          (40 meter ham radio QRP center of activity. See notes below.)

If you are within repeater range: Transmit a Long Tone Zero (LiTZ) by holding the DTMF key "0" on your radio while transmitting. Some repeaters are equipped with LiTZ functionality which triggers additional help for emergency use. The type of help and availability varies so research and program appropriate repeaters ahead of your trip when possible.

## 7.030 MHz as a last option
Affordable, low power ham radio kits are common for 7.030 MHz CW and it's within the privileges of all ham radio licenses. It is easy to construct a simple dipole antenna which can be installed about as high as you can reach from the ground and used for NVIS propagation to a relatively local coverage area. Many of these radios can be run from either a common 9v battery or 13.8 VDC found in vehicles. Though these radios are often limited to a single frequency, that's also a good thing! It is possible to build the radio, cut and test the antenna, and pack it all up in a single day. The downside is that this frequency falls in the CW portion of the 40 meter band which usually requires learning morse code. The solution is to learn LowTap (See the repository in the K3KDW Github) which is a much simpler alternative to morse code. If you need help before you learned morse code there's not much hope. If you have the cheat sheet for LowTap handy and have never used it before you should still be able to communicate effectively. Practice is heavily encouraged of course.

If you choose to use 7.030 MHz, it is wise to coordinate with other radio amateurs with capable equipment and skills who can monitor for your call. Casual check ins are helpful for ensuring you are being received from base camp or along a travel route. This step is not strictly necessary but due to the obscurity of this approach compared to 146.52 or GMRS/FRS 19, the prudent will stack the deck in their favor.

### Additional Information
**The Wilderness Protocol Extended is not limited to the wilderness only.** Use the Wilderness Protocol Extended any time communication is especially important or may be limited for example when cell phones, internet, and other communication paths are reduced or absent.

**Leave room in a conversation for others to speak.** This is critical when emergency/priority communication is trying to break through a casual chat.

It is always legal to listen to these radio frequencies. For normal use a license is required to transmit on Amateur (ham) Radio and GMRS frequencies but EMERGENCY USE REQUIRES NO LICENSE. It is highly recommended to get the appropriate license for the frequency you plan to use because you will gain important proficiency with your equipment and you can legally use the radio for non-emergency use. Emergency use is always legal.

Similarly, though some radios are not normally legal for use on certain frequencies, such as the Baofeng UV-5R on GMRS, emergency use is legal and all means of helping others is encouraged. UV-5R owners should monitor 146.52 and GMRS/FRS 19 and respond to emergencies. Transmitting on GMRS/FRS 19 on an unauthorized radio and without a license is legal for emergency use.

**CTCSS, DTC, PL, etc. tones are not to be used.** If you don't know what these are, you're probably good to go.

The frequencies chosen coincide with calling frequencies and commonly used channels because they are likely to be monitored by a larger user base.
Non-emergency/priority communication can move to another frequency or channel.

### Prepare a layered communications plan.
Cell phones are the primary choice for many so a redundant cell phone is helpful but this is not a layered plan and infrastructure issues may impact both. True layering means having multiple, independent technologies available and a plan to use them with others. Personal Locator Beacons (PLBs) and Satellite Messengers may be a better fit for your needs and should be researched carefully. There are pros and cons to any approach so consider each technology and procedure carefully but plan at least 2 methods of communication even while at home. Home internet works independently of your cell phone but when you are away from home your internet and phone are now essentially a single point of failure. Cell towers do go out on a mass scale after all...

### Differences from the original Wilderness Protocol
Time slots go around the clock instead of 07:00 - 19:00 local time
Higher frequencies are removed and lower frequencies added
Commonly used FRS/GMRS channels added

#TO DO
Should CB or other frequencies be included? Should GMRS 16 (used by offroaders/overlanders) be included or replace CHannel 19? More users are driving than hiking/offroading but folks in more remote areas might have other hikers/offroaders nearby so how do we coordinate all of this? Did I remove frequencies that should have stayed? It's important to cover as many users as possible with a few frequencies as possible so they will be more effectively monitored. If 10 meters and/or CB are used should it be SSB, FM, AM? Lots of variables for an already questionable frequency. 70cm is rarely available as a single band radio, could that space be better used by another service or frequency?

Should a local repeater be added to the list? I'm thinking not because it's an item to maintain and will confuse many users. It would be prudent to add a paragraph in the additional info section that urges repeater use if there's good coverage or even a linked system like Colorado has which includes a net specifically for wilderness and emergency use. We want folks to monitor simplex but take advantage of these services when calling out.

How does Marine 16 fit in?

Is it reasonable to offer LowTap or T9CW as a last option?

What to do if you or someone else needs help.
  Look them up on APRS?
  
Include the Wilderness Protocol Extended in your hiking/paddling/boating/etc. plans as well as a copy in your car. Include a QR to a dedicated responders page.

Is there room for WSPR/carrier-pigeon? WSPR is monitored all around the world on a single frequency, reporting is automatic, and some affordable transceivers have WSPR built in. Even low power and compromised antennas can work the world thanks to WSPR's magic. It would be relatively easy to write a watchdog program to monitor the various WSPR reporters and trigger actions. I'm hesitant to get very far at all into digital options due to complexity. Those who have and know how to use this technology likely don't need as much help getting a message out. The 7.030 option is already outside the "I fell 30' but can still make a call" level of simplicity. We shouldn't assume someone is hurt and incapable of establishing comms so maybe reasonable complexity is fine as a tradeoff for an effective last option.

To that end, what about pre-recorded APRS messages a user could play through their radio? This is likely a bad idea but is there a nugget of good we can grab? Is there a bot watchdog on APRS that looks for SOS?

If a second frequency is monitored by the same radio, ensure the radio and antenna are able to transmit on that channel. It is strongly recommended that your radio can also transmit on the monitored frequencies. That said, listening is always better than not listening.

Add NOAA freqs and a paragraph to the additional info section.

Send link to Austin at Offgrid Weather?

Thank you list

Recommended radio list

7.030 MHz CW kit and diy NVIS antenna paragraph.

Is there a benefit to having monitors announce a minute or two before the window? The 4 minute rule seems cleaner and easier to remember while accomplishing the same goal.

Are there SOTA or POTA freqs we should consider?

Scanning might be a wise addition. If you can't make contact on the dedicated frequencies, use the scan function (if equipped) to find any active conversation and break in to get help. We want to create as much monitoring as possible on the fewest frequencies required to be effective but situations inevitably arise where nobody is on the designated frequency. Other users, likely entirely unaware of the Wilderness Protocol, will be on a different frequency and can provide assistance. We want to reduce "ships passing in the night" scenarios.

Add language about using crowdsourced monitoring. Dedicated emergency monitoring is nice but can never provide the manpower of an organically popular frequency. THe 4 minute rule should be adjusted to account for already busy channels because it only exists to let others know someone is available. If the frequency is already in use then the goal has already been accomplished. Depending on why the frequency is popular and users who meet on the frequency, it might be worth a brief mention of the Wilderness Protocol Extended so they can help monitor more effectively.

How can we use bots/SDR/etc. to augment monitoring? Is there a WSPRwatch type service we can utilize?

Is it helpful or trolling to write a short flyer about Wilderness Protocol Extended to put in the windshield of baofeng equipped vehicles and give to preparedness groups?

FT8 is everywhere right now. It's impossible to know if this will be popular enough in the long term to rely on but it's certainly automated enough to potentially serve as a bot monitor. FT8 native radios aren't ready for this use yet.

How far are we from a phone app that can listen and decode messages but also pipe them out over audio WITH THE FUNCTIONALITY built into a cable to key the radio? This may be another LowTap protocol application that works much like binary or other digital communications. It's human decodable if necessary but could also be machine to machine.

On the same topic, what would it take to put a LowTap monitor online that listens and reports automatically? Ideally it's good enough to decode human messages but a starting point could be decoding LowTap from the app mentioned above.

