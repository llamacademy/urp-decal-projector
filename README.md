# URP Decal Projection

Many of us who aren't super comfortable writing our own shaders relied on 3rd party tools for decal projections or went with simple quads for decals. As of Unity 2021, URP now has a Decal Projector much like HDRP has had for a while. It's not perfect, but it's a big improvement over the quad-based decal systems I've implemented before. I'm hopeful the URP one continues to get improvements as new URP and Unity releases come out. 

In this tutorial I'll show how to enable decals in URP, review all the configuration options in the render asset and what they do, and go over what all the decal projector options do. With this tutorial you will have an informed starting point for adding decals into your game in URP. 

In this tutorial I'll show how to enable decals in URP, review all the configuration options in the render asset and what they do, and go over what all the decal projector options do. With this you should have an informed starting point for adding decals into your game!

As always, all code from [this video](https://youtu.be/5p8cKIu3P_8) is available on GitHub: https://github.com/llamacademy/urp-decal-projector

## 📚 Resources 📚
* Decal Projector: https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@12.0/manual/renderer-feature-decal.html
* Decal Shader:  https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@12.0/manual/decal-shader.html
* HDRP Repo: https://github.com/llamacademy/hdrp-decal-projector

[![Youtube Tutorial](./Video%20Screenshot.png)](https://youtu.be/5p8cKIu3P_8)

## Patreon Supporters
Have you been getting value out of these tutorials? Do you believe in LlamAcademy's mission of helping everyone make their game dev dream become a reality? Consider becoming a Patreon supporter and get your name added to this list, as well as other cool perks.
Head over to https://patreon.com/llamacademy to show your support.

### Phenomenal Supporter Tier
* YOUR NAME HERE!

### Tremendous Supporter Tier
* YOUR NAME HERE!

### Awesome Supporter Tier
* Andrew Bowen
* Gerald Anderson
* AudemKay
* Paul Berry
* Matt Parkin
* YOUR NAME HERE!

### Supporters
* Bastian
* Trey Briggs
* YOUR NAME HERE!

## Other Projects
Interested in other AI Topics in Unity, or other tutorials on Unity in general? 

* [Check out the LlamAcademy YouTube Channel](https://youtube.com/c/LlamAcademy)!
* [Check out the LlamAcademy GitHub for more projects](https://github.com/llamacademy)

## Requirements
* Requires Unity 2021.3 LTS or higher. 
* Importing the [Unity Particle Pack](https://assetstore.unity.com/packages/essentials/tutorial-projects/unity-particle-pack-127325) "Weapon Effects" folder for the wood texture and bullet hole texture.