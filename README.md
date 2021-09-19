# SpellingCheck


Build from scratch a spelling corrector in Python. It includes:

  - tokenization

  - Levenshtein distance-based non-word spelling correction

  - de-tokenization

As an example use case, consider a version of Jane Austen’s Sense and Sensibility (available via nltk’s gutenberg corpus) corrupted by random insertions,
deletions, and substitutions.

  - accept a document as a single string and return the corrected
document as a single string.

  - may use only standard libraries and numpy.


  - may use this English word list, which is ordered by decreasing frequency.
