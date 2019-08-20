# Kerbal Foundries :: Change Log

* 2017-1008: 2.1.2.11 (shadowmage) for KSP 1.3.1
	+ Update KSPWheel for KSP 1.3.1
* 2017-0904: 2.0.2.10 (shadowmage) for KSP 1.3
	+ Update KSPWheel to latest
* 2017-0826: 2.0.2.8 (shadowmage) for KSP 1.3
	+ Update included KSPWheel distribution.
	+ Fix CTT patch for APU, had incorrect part name specified.
* 2017-0715: 2.0.2.7 (shadowmage) for KSP 1.3
	+ Update KSPWheel to latest, includes a few bug-fixes and feature enhancements.
	+ Updated included ModuleManager to latest (2.8.1)
	+ NEW PART - Large Deployable Landing Leg - Has optional angled deployment using stock animation module, with adjustable deploy-angle limit.  Model+textures by TiktaalikDreaming, rigging/configs by Shadowmage.
* 2017-0604: 2.0.2.6 (shadowmage) for KSP 1.3
	+ Update for KSP 1.3
	+ Include updated ModuleManager (2.8.0)
	+ Include updated KSPWheel (0.9.5.16)
* 2017-0319: 2.0.1.5 (shadowmage) for KSP 1.2.2
	+ MAJOR CHANGE - Update to latest KSPWheels (0.9.4.15)
		- Fixes several bugs and adds a few new minor features.
		- Should not contain any breaking changes.
	+ NEW PART - Folding Hydraulic Leg - Model and textures by TiktaalikDreaming.  When clearance is a must, this leg will get the job done.  Config and balance are WIP.
	+ CHANGE - Update textures on Large Hydraulic Leg to include specular mask (TiktaalikDreaming).
	+ CHANGE - A few minor config cleanups for spelling/typos/consistency.
* 2017-0306: 2.0.1.4 (shadowmage) for KSP 1.2.2
	+ Update bundled KSPWheels to latest version (0.9.4.14)
	+ CHANGE - Re-enable APU config.
		- New/updated module to run it that does not use ModuleEngines*.  Now uses the stock resource converter mechanisms.
		- Still has sound-effects, smoke-effects based on current output.
		- Three modes - manual, linked to main throttle, or automatic.
		- Configurable target battery % in automatic mode
		- Toggle-able between open and closed cycle modes
		- Should be more compatible with welded/pre-rigged parts.
		- WIP - still some things to clean up and likely a few bugs to fix.
	+ CHANGE - Fix up the KF-Skid to actually function.  Reworked the rigging for improved visuals.  Fixed bug that was giving it improperly high rolling resistance.
	+ CHANGE - Clean up the KF-ScrewDrive a bit
		- Naming is the same as the old (left) part, but there might be loading issues with old craft.
		- Built in left-right symmetry handling.
		- Add brakes module
		- Adjust the torque output in motor module
		- Add water-propulsion module
	+ CHANGE - Remove the Screw-Drive(R) part.
	+ CHANGE - Remove deprecated rover body config and textures.
	+ NEW PARTS - Single and Dual wheel Truck tires.  Reworked/derivative of the KF-Large Wheel.  Both have the standard suite of options.
	+ [](http://i.imgur.com/j5NTKqA.png)
		- NEW PART - Large Industrial Leg - Models and textures by TiktaalikDreaming
	+ [](http://i.imgur.com/NBNQJCE.png)
* 2017-0225: 2.0.1.3 (shadowmage) for KSP 1.2.2
	+ NEW PART - Side-deploying ALG model.
	+ CHANGE - Updated ALG models and rigging.
		- WARNING -- These new models will not be compatible with the old, and the strut/wheel angles will be incorrect for vessels created with the old models.  You will need to bring the craft into the editor and adjust the angles and flip state in order to correct them.
	+ FIX - ALG now have manually specified drag cubes
	+ CHANGE - Update motor torque and power draw for all parts
	+ CHANGE - Add water propulsion module to all wheels and tracks (not on the screw drive yet, need to fix those parts first)
	+ Lots of bugfixes and updates in the latest KSPWheel version (bundled) -- https://github.com/shadowmage45/KSPWheel/releases/tag/0.9.3.13
* 2017-0205: 2.0.0.2 (shadowmage) for KSP 1.2.2
	+ UPDATE - Include latest version of KSPWheel (0.9.2.11)
	+ FIX - Incorrect brakes specifications in several tracks that were causing them to not work
	+ CHANGE - Add updated sound effects for tracks, wheels (motor, running, slip), repulsors (hover)
	+ FIX - Clean up ALG animation handling to eliminate clipping during animations.
	+ FIX - Mole track non-rotating road-wheel; they now all rotate as they should (mis-named transform in model)
	+ CHANGE - Recreate and re-rig TrackSimple for left/right models.  WARNING Craft using previous versions of TrackSimple may not load properly.
	+ CHANGE - Trim down the wheel-slip sound to allow for looping ability.
	+ ALSO - All the fixes listed for KSPWheel 0.9.2.11 ( https://github.com/shadowmage45/KSPWheel/releases/tag/0.9.2.11 )
		- NOTE -- Sound effects are WIP - will be adjusting volume/pitch according to wheel base size and current scale in future releases.
* 2017-0122: 2.0.0.1 (shadowmage) for KSP 1.2.2
	+ FIX - Fix Tiny Track config.  Still had the old KF modules in it.
	+ CHANGE - Add .version file for CKAN support
	+ CHANGE - Add Adjustable Landing Gear parts (models/configs).
	+ CHANGE - Add sound effects handling to all tracks and wheels.
	+ CHANGE - Add basic sound-effects handling to wheels and tracks.  Uses motor rpm percentage of max to determine 'power' for effects.
	+ CHANGE - Add - Dust Effects for all wheels and repulsors.  These can be disabled and configured a bit in the in-game settings/difficulty menu.  Further tweaking to come.
	+ CHANGE - Add - Repulsors float over water.  Includes special dust-effects on water (fx need a bit more work) WIP -- has issues when crossing to underwater while in inverted position.  Disabled when fully submerged.
	+ CHANGE - Add - Repulsors grid texture is animated.
	+ CHANGE - Add - Repulsors offset the force-application point to be @ the repulsor; greatly increases stability.
	+ CHANGE - Add - Repulsors can now have an 'auto-gimbal' mode enabled in the config (not available on surface-repulsor) (disabled by default).  May further increase stability beyond the force-offset changes, but may also cause spring compression unexpectedly resulting in improper suspension force calculation.
	+ CHANGE - Default repulsor damper ratio to 0.3, increase default spring rating to 1
	+ CHANGE - Repulsors now decrease length to 'turn-off'.  Should be much smoother when powering down repulsor-levitated craft (and when they lose power).
* 2017-0115: 2.0.0.0 (shadowmage) for KSP 1.2.2
	+ Initial Release
	+ IMPORTANT
		- Completely remove any previous versions of KSPWheel before installing this mod.
	+ Known Issues:
		- Currently no sound-fx
		- Currently repulsors do not levitate over water
		- Currently no dust-fx
		- Scaling support is WIP - drag cubes are not updated, attach node positions may be off, and scaling powers are not finalized (motor, mass, speed, load, etc)
		- Skid currently has no steering
		- Parts with L/R Counterparts are only partially supported and currently use two in-editor parts.
		- Any other issues that exist with KSPWheel (see the KSPWheel repository/issues list)
* 2016-0302: 1.9 (Richard_Kerman) for KSP 1.0.5
	+ No changelog provided
