# Gore Reach (Forge 1.20.1)

Gives chosen gore particles, gibs and corpses a longer draw distance. Only the ids listed in
config/gorereach-common.toml are affected.

## Get the mod (no installs needed)
1. Upload everything in this folder to a new GitHub repository.
2. Open the "Actions" tab, wait for the "Build mod" run to turn green (3-6 minutes).
3. Click the run, scroll to "Artifacts", download "gorereach-jar", unzip it.
4. Put the .jar (the one in build/libs, named gorereach-1.0.0.jar) in your mods folder.

## Not covered here (change these in the other mods' own configs)
- Ragdollified: ragdollified-client.toml -> renderDistance (and armorRenderDistance)
- Cruor: client config render_distance; server config send_range
- First Aid: client config bloodStainDistance
- Extra Gore: no distance setting found
