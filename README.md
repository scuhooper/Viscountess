# Prominent Features
## Rocket Pickups
For a more powerful weapon, I though it would be fun to have a collectible powerup that allowed the player to destroy enemy ships in a single attack. Thus, packs of 5 missiles began to float through space. The missiles are spawned at a variable time rate and start at random locations. The missiles provide a significant boost to firepower, but collecting them can sometimes mean having to blast your way through lines of enemy ships where the threat of colliding with one becomes quite substantial.

<br />
<hr>

## Random Enemy Spawner
The game features several different alien/enemy spaceships that all start from various heights off screen. To spawn them at a random location that would keep them within the gameplay area, I instantiated them using the edges of a bounding box as clamps for a random range. This lets the ships come in at varying heights and from varying distances. I also made an array of the Enemy ships as objects and used a random integer clamped to the size of the array to spawn varying ships without a clear or decipherable pattern.

<br />
<hr>

## Kill Zone

<br />
<hr>

# Code Repository
## [Viscountess Repo](https://github.com/scuhooper/Viscountess)
