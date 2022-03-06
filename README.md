# AI-art-gen

AI-powered art generator based on VQGAN+CLIP

Open the jupyter notebook in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rxchit/AI-art-gen/blob/main/ArtFromText_AI.ipynb)
> Prompt "Hindu_God"

![Hindu_God](pics/01.gif?raw=true "Hindu_God")

# Aspect Ratios and Re-Sizing

I struggle to generate images in sizes larger than 700x700 pixels. Collab runs out of memory.

I use that total number of pixels (700x700 = 490000) whenever I try other aspect ratios. Here are some useful ones:

| Ratio               | Resolution |
| ------------------- | ---------- |
| 1:1                 | 700x700    |
| 4:3                 | 808x606    |
| 16:9                | 928x522    |
| 2:1                 | 988x494    |
| 1.66:1              | 904x544    |
| 2:3                 | 568x852    |
| 4:5                 | 624x780    |
| 10:13               | 600x780    |
| 7:10                | 588x840    |
| 3:5                 | 540x900    |
| 5:6                 | 630x756    |
| 11:9                | 528x912    |
| Cinemascope (2.4:1) | 1084:452   |
| Manga (250:353)     | 576x812    |
| Super 8 (1:1.33)    | 600x798    |

# License

See ```LICENSE``` for more information.
