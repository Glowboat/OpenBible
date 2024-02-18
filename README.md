The purpose of this project is to make several versions of the Bible easier to implement in electronic applications with rich formatting.

# The files contain various xml tags for formatting purposes:

## Tags in all versions:
* `<bible version="__">__</bible>` - The entire contents of the Bible version.
* `<book name="__" type="__">__</book>` - The contents of a single book of the Bible.
* `<chapter number="__">__</chapter>` - The contents of a single chapter within a Book.
* `<verse number="__">__</verse>` - The contents of a single verse within a chapter.

## Tags in KJV, ASV, and WEB:
* `<break/>` - Line break starting a new paragraph, possibly with some space between them.
* `<return/>` - Start of a new line within the same paragraph, with no extra space between the lines.
* `<start-quote/>` - A specially positioned glyph introducing the following quotation.
* `<end-quote/>` - A specially positioned glyph following the prior quotation.
* `<heading name="__"/>` - A brief summary of the following passage.
* `<title>__</title>` - Bible text considered introductory to the following text (such as "A Psalm of David" in Psalms).
* `<indent>__</indent>` - Bible text which is indented (such as part of poetry or a quote).
* `<right>__</right>` - Bible text which is justified right (such as "Selah" in Psalms).
* `<implied>__</implied>` - Bible text which was added by the translators to improve readability.
* `<jesus>__</jesus>` - Bible text which is a direct quote of Jesus.

## Tags in OpenHB and OpenGNT:
* `<word english="__" grammar="__" strong="__">__</word>` - A unit of text which has a translation.
* `<split/>` - Separates the textual components that are part of the same word.

_Please note that the tags themselves are not necessarily part of the actual version of the Bible._
