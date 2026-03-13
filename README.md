# packings-shear-angle
Configurations and displacements of packings sheared at variable angle

Each folder includes the initial configuration, particle sizes, and other details of a packing

For cases where rearrangements are plotted, a text file (rearrOutward.txt or rearrOutwardToMaxStrain.txt depending on whether only the first rearrangements or all rearrangements to a fixed strain were saved) has the strains of each rearrangement while the folder rearrangements/ or rearrangementsMaxStrain/ has the particle positions and displacements associated with each rearrangement. Positions and displacements have been mapped back to the unit box as described in the main text before saving.

For cases where a hysteron was measured, the higher-precision strain values of \gamma^+ and \gamma^- are stored in nearerTopStrain.txt and nearerBotStrain.txt, respectively. Particle positions and displacements (for calculating dr) are saved in the corresponding folders. And energy drops are in energyDropNearerTopStrain.txt. Two of the hysterons measured came from the same N=11 packing, so the one at smaller angle (red triangles) is as described above and the one close to theta=170 degrees (teal circles) has a "-2" subscript on all the file and directories.
