# LookAt-Data
This repository contains the motion capture data pertraining to our work [Generating Emotionally Expressive Look-At Animation](https://dl.acm.org/doi/10.1145/3623264.3624438).

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

## Using this data
This dataset is for non-commericial research purposes only. If you use this dataset, you must cite the paper:

```
@inproceedings{ferstl2023generating,
  title={Generating Emotionally Expressive Look-At Animation},
  author={Ferstl, Ylva},
  booktitle={Proceedings of the 16th ACM SIGGRAPH Conference on Motion, Interaction and Games},
  pages={1--6},
  year={2023}
}
```

© [2023] Ubisoft Entertainment. All Rights Reserved
