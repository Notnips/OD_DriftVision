# Drift Vision

A spectator camera system for **Orion Drift**, by **Pub | Ayzon**.

Drift Vision turns any spectator instance into a full camera rig with several
viewing modes, a grabbable "selfie-stick" extension arm, view flipping, and an
owner-based recall system for reliable shot control.

## Features

- **First-person (POV):** ride along attached to a player's head.
- **Third-person tracking:** smooth chase camera with obstacle-aware ray casting and
  distance-based FOV.
- **Handheld mode:** grab the camera with either hand by holding the trigger near your
  head, then reposition it freely.
- **Extension arm:** push the camera out or pull it in with the opposite hand
  (trigger extends, grip retracts), with adjustable range, speed, and smoothing.
- **View flip:** flip the camera 180° with grip to face yourself or face away.
- **Camera hand-off:** drop the camera on another player's head to transfer control.
  Facing them gives first-person, facing away gives third-person. You can also leave
  it free-floating.
- **Owner recall:** designate an owner who can pull the camera back by holding a
  trigger for a few seconds, no matter where it is.
- **Player search and selection**, configurable name-tag visibility, FOV, and more,
  all from the in-game GUI.

## Controls

- Hold **TRIGGER** near your head (about 1s) to grab the camera.
- While holding, use **GRIP** to flip the view 180°.
- Use the **opposite hand's TRIGGER** to extend the camera out, **GRIP** to pull it in.
- Release the camera on a head. Facing the player gives **First Person**, facing away
  gives **Third Person**.
- Use **TRIGGER** near a free-floating camera to pick it up.
- Drop it on another player's head to transfer control.

Owner (if set): hold any **TRIGGER** for a few seconds to recall the camera.

## Configuration

All settings are adjustable in-game under the **Camera Settings** panel: FOV, head
hide, name-tag visibility, view offset, grab/drop/pickup ranges, grab delay,
third-person distance, extension arm behavior, view flipping, and owner recall time.
Settings persist between sessions.

## License

Released into the public domain.
