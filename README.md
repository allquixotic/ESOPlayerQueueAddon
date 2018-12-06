# ESOPlayerQueueAddon
Elder Scrolls Online Player Queue Addon

Available on Minion / ESOUI at: https://www.esoui.com/downloads/info2207-PlayerQueue.html

## Overview

This addon keeps track of a queue of guild members locally (for any purpose you can imagine).

There are two ways to add people to the queue:

**Note:** All names you provide to the addon are case insensitive (meaning you can use caps or not).

### Managing the queue as the Addon Operator

If **you** have the addon installed locally, the following chat commands are available:

 - /nq - Enqueue someone (put them at the end of the queue). Required parameter: Full @handle (with or without @) OR partial character name.
 - /dq - Dequeue someone (remove the first instance of their name from the queue). Required parameter: Full @handle (with or without @) OR partial character name. Character names with spaces must be "quoted".
 - /qf - **Q**ueue **F**ront -- put someone at the front of the queue. Required parameter: Full @handle (with or without @) OR partial character name.
 - /cq - **C**lear **Q**ueue. Removes everyone from the queue. Character names with spaces must be "quoted".
 - /getq - Print the queue to your chat window **and** copy the queue to the chat buffer.
 - /printq - Just print the queue to your chat window. Does not copy to the chat buffer.
 - /copyq - Just copies the queue to your chat buffer. Does not print the queue to your chat window.
 - /stfuq - Shortcut to disable queue tracking. Also available in the settings GUI.
 - /startq - Shortcut to enable queue tracking. Also available in the settings GUI.

Check the Addon Settings (Esc -> Settings -> Addons -> PlayerQueue) to enable/disable allowing players to request enqueuing/dequeuing in various channels or to enable/disable queue tracking.

### Managing the queue (of someone else) as a player

If someone else is using the addon and you want to get into their queue, ask them which channel you should put a command in, then use one of the following:

 - !q - Add yourself to the end of the queue. You can also put someone else's @handle or character name to add someone else to the queue. Character names with spaces must be "quoted".
 - !dq - Remove yourself from the queue. You can also put someone else's @handle character name to remove someone else from the queue. Character names with spaces must be "quoted".

