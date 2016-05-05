# pride-and-prejudice
Gold standard character mentions resolved to characters, for Pride and Prejudice.

* `orig.txt` contains the original story text (all labels and offsets are determined off this file).
* `resolved.tsv` contains the gold, character-resolved mentions in Pride and Prejudice.

The columns of `resolved.tsv` are headed as follows:
* `SPAN` - The textual span of a character mention.
* `CHARACTER` - The character referred to by the mention (`NON-CHARACTER` denotes a non-character mention and `OTHER` denotes individuals not part of the story).
* `START OFFSET` - The starting character (the non-literary kind) offset of the mention (inclusive).
* `END OFFSET` - The ending character offset of the mention (exclusive).
* `CHAPTER #` - The chapter number containing the given mention.
* `PASSAGE #` - The passage number within the chapter containing the given mention (passages are contiguous blocks of text, approx. 250 words in size, that make up a chapter and are indexed starting from 0).
