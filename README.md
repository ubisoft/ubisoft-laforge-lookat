# LookAt-Data
This repository contains the motion capture data pertraining to our work "Generating Emotionally Expressive Look-At Animation".

## File Naming

Files are named in the format `[RecordingNumber]_[EngagingStyle][EngagingStyleIntensity]_[DisengagingStyle][DisengagingStyleIntensity]`. The style names are herby abbreviated to a single letter based on the following mapping:

- C = Confrontational
- D = Down
- F = Fearful
- G = Disgust
- H = Happy
- I = Interested
- S = Surprise
- N1 = Bored
- N2 = Neutral
- N3 = Distracted


Each style except the 'N' styles (neutral, bored, distracted) was captured with 2 intensity, for example, 'C2' and 'C3' refer to medium and high level expression of confrontation, respectively.

When recoding of a style combination was repeated, _000 and _001 are added to the file name for the first and second repeat, respectively.

## File Contents

Each file contains the full body motion-capture plus the tracked motion of the two look-at targets. The actor alternates between the two targets, which are moved after each look-at take.  
Start frame of each look-at take at 120fps are listed in `all_frame_ranges.csv`. End frames are simply listed as the start frame of the next take.


© [2023] Ubisoft Entertainment. All Rights Reserved