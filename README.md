# Music Alignment Uncovered: Representations, Algorithms and Hands-On Tools

This is the companion website for the workshop titled "Music Alignment Uncovered: Representations, Algorithms and Hands-On Tools" held at the Music Encoding Conference 2026 by Carlos Cancino-Chacón, Jiyun Park, Silvan Peter , Yigitcan Özer, Suhit Chiruthapudi.

## Abstract

Music lives in the interplay of different representations: from printed sheet music to machine-readable symbolic representations like MEI or MusicXML to audio and video recordings. For each of these representations, there could exist multiple versions that correspond to the same musical material (e.g., different performances of the same piece, different editions of the same work). Automatic music alignment is a task in the context of Music Computing and Music Information Research (MIR) that focuses on automatically linking elements from one representation to another. Automatic music alignment is a fundamental component of different applications, from comparative analysis of music performances to interactive applications such as automatic accompaniment systems and visualizations.

In this half-day workshop we will provide a practical, hands-on overview of music alignment. The workshop will consist of a comprehensive overview of alignment technologies for both symbolic music and audio, including a practical presentation of tools, datasets and formats for representing alignments. Rather than focusing primarily on the technical aspects of alignment algorithms, we will focus on practical aspects of using alignment for the purpose of music analysis in different contexts, showcasing pipelines, open-source tools and applications.

## Offline Alignment: Audio–Audio Notebook

A hands-on notebook for **offline audio-to-audio alignment** — synchronising two recordings of the same piece with chroma features and MrMsDTW ([Sync Toolbox](https://github.com/meinardmueller/synctoolbox)), with time-scale-modification sonification ([libtsm](https://github.com/groupmm/libtsm)), chroma sonification ([libsoni](https://github.com/groupmm/libsoni)), warping-path CSV export, and Sonic Visualiser layers. It closes with a bonus on cross-instrument alignment (piano reduction ↔ orchestra).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pymatchmaker/mec2026_alignment_workshop/blob/offline-alignment/MEC2026_audio_audio_alignment.ipynb)

Run it in **Google Colab** (no setup needed), or locally:

```bash
pip install -r requirements.txt
jupyter lab MEC2026_audio_audio_alignment.ipynb
```

The Mozart *"Ah! vous dirai-je, maman"* example audio is bundled in [`data_music/`](./data_music). Copyrighted recordings (the symphony piano reductions) are **not** redistributed here, the notebook fetches short excerpts from YouTube on demand.

## LICENSE

Unless indicated otherwise, the code contained in this repository is distributed under the Apache 2.0 license (see [LICENSE](./LICENSE)).

Data contained in this repository (e.g., audio, MIDI, etc.), unless indicated otherwise, is released under the [CC BY-NC-SA license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Acknowledgements

This work was supported by the Austrian Science Fund (FWF) under grants PAT 8820923 (“Rach3”) and PIN1347924 (“AURA”), the National Research Foundation of Korea (NRF) funded by the Korean government (MSIT) under Grant RS-2023-NR077289, the European Research Council (ERC) under the EU’s Horizon 2020 programme (Grant No. 101019375, “Whither Music?”), and Japan Society for the Promotion of Science (JSPS) MEXT KAKENHI Grant No. 26K21414.


