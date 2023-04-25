# CIS565-Fall-2022-Subtitles
This repo includes subtitles for CIS565 Fall 2022 Video, generated by OpenAI Whisper.

Course website: [CIS 565 - Course Syllabus and Schedule | CIS 565 GPU Programming and Architecture](https://cis565-fall-2022.github.io/syllabus/)

Syllabus & Recordings & Slides: [Onedrive](https://onedrive.live.com/embed?cid=A6B78147D66DD722&resid=A6B78147D66DD722!96222&authkey=ANNkLBTO-JNtPW4&em=2)

Projects on GitHub: [UPenn CIS 565 Fall 2022 - GPU Programming](https://github.com/CIS565-Fall-2022)



Subtitle generation command:

```
.\venv\Scripts\whisper.exe --language English --model large --output_format srt --device cuda --verbose True <file_name>
```

TODO:

- [ ] add subtitles for all videos including labs & recitation

- [ ] fix faulty subtitles ("you", "bye-bye")
