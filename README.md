# StegoPhone
StegoPhone organizational repository, mainly with wiki and issues attached.

See the Wiki -> https://github.com/StegoPhone/StegoPhone/wiki!

I've been enjoying my vacation some, but I've also been iterating the code a little further along. I'm trying not to develop much code around the RN-52's I have on hand, but am expecting some beautiful new BM83 boards from my hardware guy Chris Burgess!

As of today I have a hardware board designer with some software ability, a vector/logo/media artist, and interest from another accomplished developer with a strong embedded systems background and both hardware and software skills.

I am going to be working on a writeup in the Wiki with a statement of purpose and goals for StegoPhone and apparently what we have help with and don't, etc!

This is going to be an amazing project.

In case you didn't know- StegoPhone's goal is to use sub-audible communications techniques to exchange some data during regular phone calls, which could be used for things like exchanging encryption keys or even just text chat which would still work even in a multi-user conference since it will be a packet-radio like retransmission system. The bulk of StegoPhone is producing essentially a mobile, tiny, SDR platform wedged between two bluetooth adapters. Once keys have been exchanged with all the users on the call, the display will indicate and then you'll be able to switch to fully encrypted calls.

# Repositories
* https://github.com/StegoPhone/StegoPhone - Top-level repo mainly for coordination and placeholder for Wikis/Projects
* https://github.com/StegoPhone/StegOS - Primary Real-Time Operating System Teensy/Arduino code that comprises the actual device
* https://github.com/StegoPhone/StegoPhone-Hardware - schematics, documentation related to the hardware.
* https://github.com/StegoPhone/StegoPhone-Artwork - logos, vector art, etc.
* https://github.com/StegoPhone/StegoPhone-Xamarin - Android app to facilitate pairing, ease of use- optional- Device should work without this.
* https://github.com/StegoPhone/StegoPhone-Blazor - Web front-end to manage profile, preferences, StegoPhone website. 
