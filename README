Overview
--------
This is the dataset for our study investigating the
effects of selective attention to speech stimuli in the subcortex and cortex,
entitled "The auditory brainstem response to natural speech is not affected 
by selective attention" by Stoll et al. (2025). Please cite our paper if 
you use our dataset.

It contains EEG data for three experiments, detailed in the paper and 
briefly summarized below. Code and stimuli to derive the responses are 
provided in the Dataset folder and on our lab's github: 
https://github.com/maddoxlab/stoll_et_al_selective_attention.

Experiment 1 - diotic stimuli (exp1Diotic)
This "task" includes EEG data for 28 subjects who listened to 120 trials
each (64 s each; total 128 minutes) of two audiobooks - A Wrinkle in Time
(Female narrator) and The Alchemyst (male narrator). Stimuli were set to
65 dB SPL then summed together to be presented diotically.
Subjects sat at a computer desk in a soundproof room.
They were instructed to attend to only one narrator on each trial, with cues
given before they started the trial and through a fixation dot which remained
for the duration of the trial. For details, see the
`Details about the experiment` section and refer to our paper.

EEG was recorded simultaneously from a 32 channel activate montage (to examine
cortical responses) and a 2 channel passive bipolar montage (FCz to earlobes, 
to examine subcortical responses). On a subset of the subjects 
(1, 3, 4, 7, 8, 9, 10, 11, 12, 13, 16, 18) an additional electrode was placed 
on the eardrum. Data are split into cortical (active) electrodes and 
subcortical (passive) electrodes. Since data was collected simultaneously, 
data from all electrodes were sampled at 25 kHz. To reduce file size and 
computation time, the cortical electrodes were downsampled to 1 kHz and 
the subcortical electrodes were downsampled to 10 kHz.

Experiment 2 - dichotic stimuli (exp2Dichotic)
This "task" contains EEG data for 25 subjects who listened to 60 trials
each (64 s each; total 64 minutes) of two audiobooks - A Wrinkle in Time
(Female narrator) and The Alchemyst (male narrator). Stimuli were set to
65 dB SPL and presented diotically. Subjects sat at a computer desk in a 
soundproof room. They were instructed to attend to only one narrator on
each trial (indicated by the story name, talker sex, and direction) with cues
given before they started the trial and through a fixation dot with an arrow 
which remained for the duration of the trial. For details, see the 
`Details about the experiment` section and refer to our paper. The records
of individual participant age and sex no longer exist, but overall statistics
are reported in the paper.

EEG was recorded simultaneously from a 32 channel activate montage (to examine
cortical responses) and passive electrodes using a bipolar montage, with the
noninverting electrode placed on FCz and the inverting electrode on the earlobe, 
with ground on the forehead. The side the electrode was placed on was
counterbalanced across subjects.

Experiment 3 - passive listening to stimuli from Forte et al. (exp3Passive)
This "task" contains EEG data for 14 subjects who listened to 32 trials
each (~117 s each; total ~62 minutes) of four audiobooks - Tales of Troy:
Ulysses the Sacker of Cities and The Green Forest Fairy Book narrated by 
James K. White for the male speech and The Children of Odin and The Adventures
of Odysseus and the Tale of Troy narrated by Elizabeth Klett for the female
speech. These audiobooks were selected to match the study by Forte et al. (2017),
who provided us with the audio files. Stimuli were set to 73 dB SPL then
summed together to be presented diotically (i.e., at 76 dB SPL). The stories 
were paired in the same manner as in Forte et al. (2017). Subjects sat at a
computer desk in a soundproof room. They were instructed to ignore the audio
as best they could and distract themselves by watching silent captioned videos
of their choosing or by reading.  For details, see the `Details about the experiment`
section and refer to our paper.

EEG was recorded with a passive electrodes using a bipolar montage, with the
noninverting electrode placed on FCz and the inverting electrode on the earlobe, 
with ground on the forehead.


Format
------
The dataset is formatted according to the EEG Brain Imaging Data Structure.
See the `dataset_description.json` file for the specific version used.
Generally, you can find detailed event data in the .tsv files and descriptions
in the accompanying .json files. Raw eeg files are provided in the Brain
Products format.

Details about the experiment
----------------------------
For a detailed description of the task, see Stoll et al. (2025) as well
as the supplied file json files.

Trigger onset times have already been corrected for the tubing delay of the
insert earphones. Trial numbers and more metadata of the events are in each
of the '*_eeg_events.tsv" file, which is sufficient to know which trial 
corresponded to which chapter and which narrator
the subjects were instructed to attend. As chapters were
organized to allow subjects to follow to stories, all subjects had the same
trial order in experiment 1 and 2. Story order was randomized in experiment
3, with that information stored in the '*_eeg_evnets.tsv" file.


