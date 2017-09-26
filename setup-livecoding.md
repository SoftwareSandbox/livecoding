# Setting up your PC for livecoding

## Download OBS
[Open Broadcaster Software](https://obsproject.com/)

Install, check browser plugin.

## Create Twitch.tv account
If you haven't done so already:
[Twitch.tv](https://twitch.tv), _Register_

## Configuring OBS
### Settings
Base Resolution: _Use Current (1920x1080)_

FPS: _30_

Stream Key: Click _Show Key_ on [this url](https://www.twitch.tv/cgk_livecoding/dashboard/settings/streamkey).

Advanced: _Enable Stream Delay_ of _20s_ so you can still shut down the stream on time when you realized you've done something stupid (like shown a password e.g.).
Configure this to how fast you think you realize your own mistakes. :D

## Setting up scenes in OBS
We'll need 4 scenes:

* StreamLaunch
* Coding
* BreakyBreak
* DoingSecretStuff

All scenes except for coding should really just be image captures that contain a message to the viewers:

* _Stream starting soon_
* _On a lil' breaky break_
* _Doing super secret stuffs_

All of these images are currently set to _Fit to Screen_.

### Coding scene
The coding scene we can break down into multiple sources:

* mic: Audio input source for your microphone
* cam: Video input source for your webcam
* banner: a 1920x40 overlay that neatly hides the the windows bar and is the backdrop for some text
* current coder label: simply the text _Current Coder:_
* current coder: for now also simple text containing the name of the person that's coding, currently.
* display right(or left): the screen you'll be sharing with your viewers.

#### More info on the display source
You want to maximize your editor that you're using.

Pick the display that doesn't show your alt-tab screen.

## Stuff to pay attention to while streaming
Don't share company info, or development desktop related info. e.g. using a terminal might show who's logged in.

