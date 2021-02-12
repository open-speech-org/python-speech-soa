To get all the recordings please install the [Open Speech Corpus CLI](https://pypi.org/project/openspeechcorpus/)


```bash
ops      \
     --output_folder aphasia/ \
     --output_file aphasia_letters.txt \
     --corpus aphasia \
     --extra_query_params "level_sentence__id__gte=846&level_sentence__id__lte=870"
```

And to get the WAV files

```bash
recursive_convert aphasia aphasia_wav
```
