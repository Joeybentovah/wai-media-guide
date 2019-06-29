---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Transcribing Audio to Text"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Transcribing Audio to Text" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/transcribing/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/transcribing/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  previous: /design-develop/media/transcripts/
  next:     /design-develop/media/sign-languages/
  
---


{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on transcribing audio to text for captions and transcripts, for those who will **do it yourself** (DIY).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

_This page is part of a resource introduced in [Making Video and Audio Accessible - Introduction](http://@@)._

Good transcription requires knowledge of which non-speech audio information should be included in the transcription. It's more art than science — for example, it’s not always clear which non-speech audio information to include and how to communicate it in text.

If you have the resources to hire professionals to do your transcribing, that is best. If you don't, please **don't be deterred from providing transcripts or captions**. This page helps you do it yourself (DIY).

## How to Transcribe

You can just listen to the audio and type it up. That's usually pretty tedious because you have to stop and restart the audio a lot. There is software that can help by slowing down the audio and providing easy pause buttons.

<!-- There are some free services online. They tend to have lower accuracy. You can purchase speech recognition software and train it to be more accurate with your voice. This may be a viable option for things like regular podcasts that usually have a single speaker. -->

You can start with an automatically-generated text file. There's lots of software and services that provide speech-to-text. These have various levels of accuracy. Often the text does not match the spoken audio — and in ways that change the meaning (or are embarrassing). For example, missing just one word such as “not” can make the captions contradict the actual audio content.

<p style="text-align:center; text-size:85%">[<em>optionally as an illustration for visual interest (with text as true text):</em><br>
  &quot;Spoken text: 
  Broil on high for 4 to 5 minutes. You should not preheat the oven.&quot;<br>
  &quot;Automatic caption: Broil on high for 45 minutes. You should know to preheat the oven.&quot;<br>
  <em>optional illustration/picture:  fire coming from oven, or totally burned food on a broiler pan ;-)</em>]</p>

Therefore, plan to spend time correcting automatically-generated transcription.

More details on options and tools are in: Transcripts on the Web, [How to get or make transcripts [icon]]( http://www.uiaccess.com/transcripts/transcripts_on_the_web.html#justdoit).

{@@ update^^^ !}

## What to Transcribe

Generally, you transcribe all speech and relevant non-speech sound, such as {@@ example, example, example}. Keep in mind that the main purpose is to provide **the information that you hear to people who cannot hear the audio**. That will help you know which sounds to transcribe, and which are not needed. The following are common practices, not requirements.

### Basics
{:.no_toc}

* Identify the speakers as relevant. Often it is best to use the full name the first time and single name throughout &mdash; either first/given or last/family depending on the formality.

* You can include relevant information about the speech. For example:<br>

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

	<em>( between gritted teeth ):</em><br>
	I hate this computer!

{::nomarkdown}
{% include box.html type="end" %}
{:/}

* Put important non-speech sounds in parentheses, lowercase, italics, with a space before and after. For example:<br>
	 <em>( computer crashing into bits and parts sliding across the floor )</em>

* When a speaker is off-screen, you can put their speech in italics. For example:<br>
	<em>Jose: What was that awful noise?</em><br>
	Zoe: You don't want to know.<br>
	<em>Jose: Well, I'm coming to find out.</em>

* Only include background music if it's important to understand the content of the video. Use objective descriptions that indicate the mood; avoid subjective words, such as "beautiful." If the words in the music are important, add a musical note to the beginning and end of each caption. Put music information in italics. For example:<br>
	<em>♪ scary music, JAWS theme ♪</em>

* Do not emphasize a word using all capital letters, except to indicate screaming. For example:<br>
	Jose: YOU KILLED MY NEW LAPTOP!

### Be True to the Audio Content
{:.no_toc}

* **Do not change or adapt or add to the text**. Transcribe what is said accurately.
   * For example, it is usually not appropriate to correct grammar or other mistakes.
   * Do not censor. For example, if objectionable words are said, include those in the captions. If the audio is edited to obscure a phrase (e.g., "bleeped" audio), reflect that in the captions, e.g., <em> --bleep-- </em>
   * Do not provide additional clarifying information in the captions. (You can provide some in the transcript as appropriate.)

* Include the appropriate level of detail:
   * For some content, such as legal depositions, transcribe everything verbatim, including things like "um", "ah", and repeated phrases.
   * For most web content, it is acceptable to leave out non-substantive text to make the captions easier to process &mdash; while adhering to the tips above. For example, if the speaker says:<br><em><strong>I just got so frustrated</strong> (cough, cough) sorry – uhhh what was I saying?..., oh yea - <strong>I got so frustrated with my computer.</strong></em><br>
You can caption:<br>
<em><strong>I just got so frustrated with my computer.</strong></em>
   * If there is speech that is not at all relevant, indicate that it has been excluded from the captions. For example:<br>
	<em>[participants discuss the weather while the presenter reboots his computer]</em>

* If you cannot understand what is said, transcribe:<br>
[unintelligible]

* [@@ Do not caption the same, or nearly the same, information that is already shown onscreen. https://dcmp.org/learn/225 ]


@@@@@@@@@@@@@@@@@@@@@@@@@@

put back in captions page?

### What to Included in Caption Files
* The time each phrase should be displayed.
### Specific for captions
* Captions are one or two rows. ?? character length
* Put a new sentence on a new line.
* If you need to break a sentence into multiple segments, break it at a logical phrase.

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Captions not needed: The only sound with this video is background music. There is no speaking.

{::nomarkdown}
{% include box.html type="end" %}
{:/}