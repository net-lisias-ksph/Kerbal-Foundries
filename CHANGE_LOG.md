# Kerbal Foundries :: Change Log

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
