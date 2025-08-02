The Reach and Teach Peace Tree was created in 2019 to ask and hopefully answer the question: "Can a holiday decoration change the world?" 
The hope of the design was that a set of LED lights creating light patterns based on the number of social media posts tagged with #peace 
might inspire more peace and peaceful actions. Our project team is now looking at expanding this to Blue Sky and other social media platforms.
The eventual desire is to also tie peace tree activity to specific peace producing actions. Currently, a special peace tree pattern occurs 
when a post is tagged with #peaceaction

Pretty much any WLED controller can be easily adapted to become a Reach and Teach Peace Tree by doing the following:

1. Connect to the WLED interface screen for your WLED controller
2. Create presets with IDs 21 through 26.
3. In Sync Interfaces (which you can get to from the configuration menu), enter the MQTT settings for the public peace tree feed which you can find in the instructable for the WLED Peace Tree https://www.instructables.com/Easy-Peace-Tree-Visualizing-Peace-With-WLED/ . Enable MQTT. Save the settings. This MQTT feed is hosted at takeoneworld.com and is specifically designed to work with WLED controllers. Save the settings.
4. Reboot the WLED controller (usually by simply unplugging it and replugging it in) and the peace tree should start operating within a couple of minutes.
5. Please let me know in your comments if you make this since I'm trying to keep track of how many peace trees are out in the world.

There is a background process located at takeoneworld.com that monitors #peace and #peaceaction tagged posts and activates the WLED presets as follows:
* 0 - 10 posts invoke Preset 21 (red pattern)
* 11-20 posts invoke Preset 22 (green pattern)
* 21-30 posts invoke Preset 23 (blue pattern)
* 31-39 posts invoke Preset 24 (aqua pattern)
* 40+ posts invoke Preset 25 (rainbow glitter pattern)
* A special post invokes Preset 26 (blue and white sparkle pattern)

There are other alternate preset files in this repository

There is an official website for this project at: https://peacetreelights.com
