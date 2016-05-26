# pride-and-prejudice
Gold standard, character-resolved mentions for the novel _Pride and Prejudice_, by Jane Austen.

* `orig.txt` contains the original story text (all labels and offsets are determined off this file).
* `resolved.tsv` contains the gold, character-resolved mentions in Pride and Prejudice.

The columns of `resolved.tsv` are headed as follows:
* `SPAN` - The textual span of a character mention.
* `CHARACTER` - The label of the character referred to by the mention, usually just a unique name used for the character that easily identifies them (`NON-CHARACTER` denotes a non-character mention and `OTHER` denotes individuals not part of the story).
* `START OFFSET` - The starting character (the non-literary kind) offset of the mention (inclusive).
* `END OFFSET` - The ending character offset of the mention (exclusive).
* `CHAPTER #` - The chapter number containing the given mention.
* `PASSAGE #` - The passage number within the chapter containing the given mention (passages are contiguous blocks of text, approx. 250 words in size, that make up a chapter and are indexed by line number in the story, starting from 0).

Please source the following paper if you use this data in your own work:

(TODO)
