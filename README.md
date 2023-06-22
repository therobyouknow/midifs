# midifs

A very basic patch librarian for the Korg M1

Given that the M1 is a music synthesizer keyboard, one can adjust the playback of its sound oscillators (PCM samples), using ADSR envelopes filters etc. These adjustments were stored as small records of parameters, often generally called "patches" on synthesizers. They weren't the PCM samples themselves, but settings that described how the are played. The naming convention for the Korg M1 for a patch is a Program. The Korg M1 also has Combi programs, which are combinations of individual Program patches, e.g. Piano and Strings, so you can allocate more than one sound to the keyboard at once. There's also Song data, because the M1 has a built in music sequencer for recording the notes played. The recording is a list of the notes as a sequence, not digital audio.

I wrote a librarian tool to download and store these parameters records on a computer and to be able to send them back. Which meant I could make many more patches than the synth's memory could store. The Korg M1 has space for up to 100 programs, 100 combis. The benefit of being able to store programs externally is therefore apparent, original factory programs can be kept and new programs added.

Reference:
https://forums.theregister.com/forum/all/2022/12/19/in_praise_of_midi_techs/#c_4589223
