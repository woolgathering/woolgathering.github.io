---
layout: default
permalink: /work/research/dbap
---

# Speaker Placement Agnosticism: Improving the Distance-based Amplitude Panning Algorithm

PDF: [Color](./sundstrom_dbapCOLOR.pdf), [B\&W](./sundstrom_dbapBW.pdf)

### High-Resolution Color Plots

#### 3x3 Grid Layout

[Figure 2](./grid/orig_gain.png): Original DBAP. Rolloff = 6, r_s = 1.073. *Top*: Plot of a 3x3 grid of loudspeakers with a line showing the movement of the source from the center of the field, extending in a spiral to a point outside the field. *Middle*: Gains of the each speaker, color coded to correspond to the above figure. Note the flat spot in the third speaker where the percieved motion stalls due to the nonunique projection. *Bottom*: The power of the entire field as a function of the source's angle. Notice the undulating power as the source traverses the boundary of the convex hull.

[Figure 3](./grid/new_gain.png): New DBAP. Rolloff = 6, r_s = 1.073. *Top*: Plot of a 3x3 grid of loudspeakers with a line showing the movement of the source from the center of the field, extending in a spiral to a point outside the field. *Middle*: Gains of the each speaker, color coded to correspond to the above figure. *Bottom*: The power of the entire field.

[Figure 4](./grid/abs_gain.png): ADBAP. Rolloff = 6. *Top*: Plot of a 3x3 grid of loudspeakers with a line showing the movement of the source from the center of the field, extending in a spiral to a point outside the field. *Middle*: Gains of the each speaker, color coded to correspond to the above figure. *Bottom*: The power of the entire field as a function of the source's angle.

#### 10 Speaker Asymmetrical Layout

[Figure 5](./asym/field.png): Speaker layout and movement of virtual source in the asymmetrical field.

[Figure 6](./asym/orig_gain.png): Gain curves for the original DBAP algorithm with projection. Note the very fast drop off in power once the virtual source exits the convex hull.

[Figure 7](./asym/abs_gain.png): Gain curves for ADBAP. Although the behavior is much more what is expected, note the spike in power around the first pi when the virtual source closes in on the cluster of speakers 2 and 8.

[Figure 8](./asym/new_gain.png): Gain curves for the version presented in this paper.
