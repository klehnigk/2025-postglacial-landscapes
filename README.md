# 2025-postglacial-landscapes
ESPIn 2025 project exploring landscape influence of glacier retreat.

Contributors:
* Viet M Bui (organic rice fed - Delta & SLR dude)
* Ari Koeppel (sol3ling)
* Shayla Triantafillou (river gal)
* Karin Lehnigk (glof club)
* Lucille Baker-Stahl (temperature + morphodynamics = ?)
* Tom Hoseason (tbd)

Project Summary
![](dutch_baby_slice.png)
  This project explores sediment movement in a de-glacieted landscape. We are going to do this by exploring lateral moraine diffusion and its interactions with fluvial transport. Moraine diffusion will be influenced by thawing of an ice-rich core (represented as "bedrock lowering") and diffusion will be calculated using a depth dependent diffusion componenent. 

Project Steps:
* Generate topography
*   Must have down-valley slope, mirrored sin moraines parrallel to valley gradient
* Classify sub-surface land classes
* Diffusion
* Ice melting
* Channelized water flow
* Sediment transport 

Project Tasks:
- [ ]  Initial maps of soil thickness, ice thickness, and bedrock elevation (L: Viet, S: Tom)
    - [ ]  Ice & soil thickness are connected
    - [ ]  Model ice as special bedrock, or permafrost
    - [ ]  Make layers —> wrinkle —> slice —> tilt
    - [ ]  Boundaries: closed at the sides, open on top & bottom
    - [ ]  Litholayers component (might not be necessary)
- [ ]  Moraine diffusion  (L: Lucille, S: Ari)
    - [ ]  Diffusion will be a function of composition
    - [ ]  DepthDependentTaylorDiffusion component
    - [ ]  Simple diffusion (1)
    - [ ]  Melt ice (2)
    - [ ]  Linear diffusion (3)
    - [ ]  When plotting, have axis limits at moraine centers
- [ ]  Overland flow (L: Karin, S: Viet)
- [ ]  Sediment transport (L: Shayla, S: Lucille)
- [ ]  Vegetation (L: Tom, S: Ari)
    - [ ]  Standard vegetation component
- [ ]  Compiling the document (L: Ari, S: Shayla)


