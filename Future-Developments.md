## Potential new parts / mechanics:

### Stock wheel, gear, leg conversions
* Update / finish / clean up the stock-part conversion patches.  Re-introduce as an optional patch set

### Landing Legs
* Single, dual, and quad landing-leg sets
  * Multiple variants.
  * All scalable
  * Dual varieties are for VTOL landing of horizontal rocket stacks (legs protrude 'sideways' from the rocket when in vertical orientation)
  * Quad varieties are for standard vertical landing, intended to be stack mounted to the bottom of a fuel tank inbetween the tank and the engine.
    * Will include both the ability to alter the scale, and the 'diameter' placement of the models.

### ICE engine parts and ICE motor model
* Essentially these are APUs that put out EC based on their size.  Consume LF + (O or IntakeAir) (dual-mode).
* Add a secondary motor-simulation-model that uses output curves appropriate for a combustion engine, usable/enabled when one of the ICE-APUs are present on the craft.

### Hovercraft / Ground-Effect flyers
* Set of fan/turbine/rotors intended for use for hover-craft.
 * Will include 'ground effect' mechanics -- whenever the engine is within a certain distance of the ground (based on its size and base power), it will gain 'bonus' power output based on this distance, to simulate ground-effect feedback.
* Potential set of hovercraft skirt parts.
  * Possibly with some sort of inflate/deflate/compress mechanics or rigging.
  * Might use custom plugin to drive animation based on distance from ground and presence of motors and their state.

### Rotary aircraft parts
* Set(s) of primary rotor blades with both thrust and torque output.
  * Scalable.  Same rotor sets can be used for both primary and secondary rotors.
  * Allow for co-axial counter-rotating setups to neutralize rotor torque output.
  * Full collective pitch simulation? -- 
  * Method to link output on both main and secondary rotors for a synchronized rotor setup (e.g. shaft-driven tail rotor)

### Standard aircraft propellers
* Uhh, yeah, pretty much what the title says
* But also some will have additional built-in features, such as changing of orientation / rotating - for either thrust vectoring, or use in hybrids (e.g. osprey)
* Scalable

### Folding Wings
* Stowable, foldable, deployable, scalable.