# Speechcatcher

Speechcatcher is an open source toolbox for transcribing and translating speech from media files (audio/video). Speechcatcher models are trained using whisper as teacher and offer compact and small ASR models that run fast on CPUs too:

![Speechcatcher Teacher/student training](https://github.com/speechcatcher-asr/speechcatcher/raw/main/speechcatcher_training.svg)

## Speechcatcher CLI

You can find the command line interface <a href="https://github.com/speechcatcher-asr/speechcatcher">here</a>. It can transcribe any media file and can also be used for live transcription with your microphone. In this repository, there is also an overview of all available speechcatcher models.

## Data

Scripts to replicate the data gathering can be found in: <a href="https://github.com/speechcatcher-asr/speechcatcher-data">speechcatcher-data</a>. There also instructions on how to replicate the training procedure with espnet.

## Webgui

Speechcatcher also comes with an easy to use <a href="https://github.com/speechcatcher-asr/speechcatcher-webgui">webgui</a>. It is going to support multiple ASR engines: <a href="https://github.com/speechcatcher-asr/speechcatcher">speechcatcher (GPU/CPU)</a>, <a href="https://github.com/uhh-lt/subtitle2go">subtitle2go (CPU-only)</a> or <a href="https://github.com/openai/whisper">whisper (GPU)</a>.  

## Benchmarks

By using models that target a single language, Speechcatcher models aim to be much faster than single-model transcribe systems for multiple languages such as <a href="https://github.com/openai/whisper">whisper</a>. 

See our results <a href="https://github.com/speechcatcher-asr/speechcatcher">here</a>.  

Currently the focus is on transcribing German speech. Later, more languages might be added. If you would like to help to expand Speechcatcher, please get in touch!

## Citation

If you use speechcatcher models in your research, for now just cite this repository:

    @misc{milde2023speechcatcher,
      author = {Milde, Benjamin},
      title = {Speechcatcher},
      year = {2023},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/speechcatcher-asr/speechcatcher}},
    }

## Sponsors

Speechcatcher is gracefully funded by

<a href="https://media-tech-lab.com">Media Tech Lab by Media Lab Bayern</a> (<a href="https://github.com/media-tech-lab">@media-tech-lab</a>)

<a href="https://media-tech-lab.com">
    <img src="https://raw.githubusercontent.com/media-tech-lab/.github/main/assets/mtl-powered-by.png" width="240" title="Media Tech Lab powered by logo">
</a>
