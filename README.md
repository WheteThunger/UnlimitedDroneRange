**Remote-controllable drones are still a work-in-progress by the Rust developers. This plugin fixes one of the current issues with them, and will likely not be necessary in the future.**

This plugin fixes the issue where remote-controlling a Drone via a computer station can cause it to lose signal when it gets out of range. With this plugin installed, the signal is never lost.

## FAQ

#### How do I spawn a drone?

Admins can spawn a drone entity with the `spawn drone.deployed` command in the F1 client console.

#### How do I get the deployable drone item?

Admins can use the command `inventory.give drone 1` to give themselves one or more drones. They can also be added to kits.

#### How do I remote-control a drone?

If a player has building privilege, they can pull out a hammer and set the ID of the drone. They can then enter that ID at a computer station and select it to start controlling the drone.

#### What are the controls?

`W`/`A`/`S`/`D` to move, `shift` (sprint) to go up, `ctrl` (duck) to go down, and mouse to steer.
