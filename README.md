# Unity Animation Post Processor

This repository contains the code and assets on how to fix Mixamo, Ramsterz and animations from other sources automatically in Unity using an Animation Post Processor. An Animation Post Processor solves issues like rig alignment, missing avatars, animation types (generic vs humanoid), unnamed animations, and more.

When importing a humanoid animation into a Unity project, proper alignment depends on the compatibility between the imported rig and the character's avatar. The animation might not align as expected if the imported rig does not accurately match the avatar's humanoid rig. This misalignment occurs because the rig's bone hierarchy and joint orientations may differ from the target avatar. This code will solve those issues automatically during import in most cases.
