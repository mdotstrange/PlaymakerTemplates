# PlaymakerTemplates
-- Playmaker templates as Unity packages, associated custom Playmaker actions included

# Generate Waypoints and Patrol
  - this package uses the NEW Unity Navmesh system that utililzes NavMesh Surfaces, it won't work with the old baked Navmeshes- [Get the new navmesh components here](https://github.com/Unity-Technologies/NavMeshComponents/tree/2017.2)
  
  Put it on a NavmeshAgent and fill in the data- it will randomly patrol generated waypoints
  
![alt text](https://i.imgur.com/Pvg97xQ.png "The template")

- The Navmesh surface game objects MUST have a collider on them- only tested with box colliders- the ground layer name must match these layers

![alt text](https://i.imgur.com/0St1nJK.png "Example")
