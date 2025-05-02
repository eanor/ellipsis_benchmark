# The Russian Ellipsis Benchmark (REB)
This corpus contains sentences with an ellipsis for Russian language. The corpus is designed to test the LLM's Ellipsis Resolution capability.

### Data
The corpus contains sentences with different types of ellipsis, mainly: NP-ellipsis, VP-ellipsis, gapping, stripping, sluicing, polarity ellipsis, answer ellipsis.
The data for the corpus was taken from existing ellipsis corpus in Russian, from articles about ellipsis in the Russian language, manually selected by the author from the Russian National Corpus or created by the author. To find out the source of the sentence, see the source column.

### Structure
| sentence  | suggested ellipsis resolution | ellipsis type | source |
| ------------- | ------------- | ------------- | ------------- |
| Котёнок пытался поймать муху, но не догнал __ и грустно смотрел ей вслед. | муху | NP_ellipsis | original |

Column "sentence" contains a sentence with an annotated ellipsis site, column "suggested ellipsis resolution" contains an ellipsis resolution, column "source" contains a reference to the source material.

### Cite
To cite this work:
S. Kuznetsova. (2025) The Russian Ellipsis Benchmark (REC). https://github.com/eanor/ellipsis_benchmark
