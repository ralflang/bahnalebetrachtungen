# bahnalebetrachtungen

notes repo

## MCAN / CC-Schnitte minimal setup

Connect CC-Schnitte Mini DIN 6-pin to any of the two Gleisbox Mini DIN 10-pin sockets using the black cable
Connect Gleisbox red wire and brown wire to track (see below)
Connect Gleisbox to switching power supply. It should be  18V DC 36VA (2.0A)

## Connecting wires to track

Most Märklin C-Gleis tracks have a pair of shoes on either side on which you can connect the red (+) and brown (-) power wires.

### Canonical Order of Track Wires.

Hold the piece of track one side up, one side down. Looking at the top side, the left hand contact finger should be closer to the top and the right hand contact finger should be further inside. There should be a letter stamped on the left side and a number on the right side, i.e. "B | 0" where | is the metal bar in the middle of the track.
Connect the red wire to the left/upper contact finger ("Letter side"). Connect the brown wire to the right/lower contact finger ("Number Side").

A pristine track box has flat connector sleeves ("spade connectors") at the tip of the cable. Some second hand track boxes are sold with these clipped off and bare cable ends instead. In any case, do not solder track box cables to the track. Either solder a separate cable to the track and connect that cable to the track box cable using wago clamps, screwed connectors of any kind or best crimp new flat connector sleeves to the cable. The Marklin original part id is 70930 for a crimp tool and 74995 for a set of flat connector sleeves but any electronics store has similar, cheaper alternatives.

If you connect the red wire to the wrong side, trains will still run correctly. However, all other connection points must be reversed, too. Some occupancy detectors and other peripherals will have problems if the sides are swapped.

### Marklin Color codes

| cable color | connector color * | code | purpose | other |
|-|-|-|-|-|
| red  | red | B | track central points (+) |  |
| brown | brown | 0 | track outer gauges (-) | cable can also be black |
| yellow | yellow | L | AC boosters, lights, turnouts/switches | If you use track power, connect this to RED + |
| blue | green | () | Between turnouts, signals and toggles or decoders - "straight" or "go" |  |
| blue | orange | () | Between turnouts, signals and toggles or decoders - "curved" or "stop" |  |


* If you use sleeve connectors or permanently solder, you can add colored tape to the end of the wire
