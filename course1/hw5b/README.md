# course1/hw5b teaching figures

Built by build/figures_hw5.py (hw5 stream, 1 Nov 2026). Hosted in Maggs31/course-figures,
referenced by raw URL pinned to the commit. Files are never renamed or deleted.

| File | Source |
|---|---|
| hw5b_roadmap.png | drawn for the notebook; the waveform and log-mel image are the lecture's jfk.flac example (kit data), shapes from the lecture (kit w5_data.json) |
| hw5b_logmel_pipeline.png | the lecture's jfk.flac example (openai/whisper tests), computed in the kit's data/w5_data.py following openai/whisper audio.py; parameters from Radford et al. 2022 Sec. 2.2 and the whisper-large-v3 card (128 mel bins) |
| hw5b_whisper.png | redrawn after Radford et al. 2022 Fig. 1 and Sec. 2.2 to 2.3; layer counts from the paper (Table 1, large) and the whisper-large-v3-turbo card (4 decoder layers); prompt token ids from the Whisper tokenizer (kit w5_data.json); 'Mister Quilter' is the first LibriSpeech test-clean transcript |
| hw5b_wer_example.png | the lecture's worked example, computed in the kit's data/wer_example.py (checked against a brute-force edit distance) |
| hw5b_cost_table.png | computed in this script for the lecture's worked example (kit data/wer_example.json); the standard word-level Levenshtein table |
| hw5b_turbo.png | openai/whisper-large-v3-turbo model card (decoder 32 to 4 layers, 809M against 1550M), as cited in the lecture (kit w5_data.json) |
