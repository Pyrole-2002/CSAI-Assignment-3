Each tar.gz file has the beta (con_$XXXX.hdr/.img) and t-value maps (con_spmT_$XXXX.hdr/.img) for each subject,
$XXXX runs from 1 to 92, referring to the visual stimuli in the order as provided in visual_stimuli.mat
an additional mask.img/hdr file indicates voxels in the brain (=1) and outside (=0).


The file visual_stimuli.mat contains a 92 dimensional struct with several fields
category                        :   string indicating category
human, face, animal, natural    :   scalar, indicating membership (0= not a member, 1= member)
pixel_values                    :   the actual images