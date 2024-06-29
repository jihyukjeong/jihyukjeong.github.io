---
layout: page
title: Ph.D. Manuscript
description: Brief overview of the Ph.D. manuscript
img: assets/img/3Dmode.png
importance: 1
category: work
related_publications: false
---

An eutectic refrigeration system is proposed to replace conventional refrigeration systems powered by fossil fuel consumption for transporting frozen food products via refrigerated truck trailers. To study the feasibility of the eutectic system, numerical models have been first developed and favorably validated against published numerical and experimental results. The consolidated model has then been used to accurately predict the performance of the eutectic plates, while being compared to new measurements on a lab scale system.

Initially, an infiltration model was developed using a $k-\omega$ SST turbulence model to predict the thermoaerolic behavior of air during door-opening periods. Two fan modes and different configurations of eutectic plates were analyzed. Without any cargo, plates placed in series along the truck trailer's roof had a higher renewal time than those placed in parallel at the rear due to recirculation zones created by the pre-existing flow. However, as cargo is introduced into the system, both configurations behaved similarly as recirculation zones couldn't form.

Furthermore, a granular multiphase Eulerian-Eulerian model was developed to predict frost formation on top of a cold plate. The $k-\omega$ SST turbulence model was incorporated into the frost model to extend its applicability to a wider range of inlet velocities. Finally, the solidification and melting models were consolidated into the model as a user-defined function (UDF). With the consolidated model, the performance of a eutectic system was studied for typical summer conditions in Montreal, Canada. The analysis showed that approximately 2.3\% of the phase change material undergoes a phase change within the first 120 seconds. Overall, the performance of the eutectic system can be considered a viable replacement for the conventional system. Moreover, the system will be greatly enhanced through infiltration prevention and frost removal mechanisms.

{% include figure.liquid path="assets/img/sm_vel.png" title="example image" class="img-fluid rounded z-depth-1" %}

Velocity magnitude of the melted PCM for $A_{mush} = 10^6$ at four different times.
