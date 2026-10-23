# MG4
## Devlog
when Start is called at the start of the game, the _timer variable is set to the value chosen for _switchSpeed, after which the Update function begins decrementing the time on _timer based on Time.deltaTime(). when _timer reaches 0, the _timer resets back the _switchSpeed, while the _up boolean becomes inverted. inside of Update, the location of the attached GameObject transform is updated based on the value of _up, with True indicating it should move upwards and False indicating it should move downwards
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
