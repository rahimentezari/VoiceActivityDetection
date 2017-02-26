These are mp3 files for 3 training movies.
Using the following command each mp3 breaks to slices of 200ms, each of which we have label(speech/nonspeech)for.
sox MovieName out.mp3 trim 0 0.200 : newfile : restart
