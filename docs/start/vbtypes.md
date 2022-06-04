# Voicebank Types (Japanese)

In UTAU, there are various formats of voicebanks. Each of them are used differently.

Each note is represented by 1 mora. A mora is basically one syllable; it can be a consonant-vowel pair [`ka`], or a single vowel [`a`]. In some cases Japanese uses C-C-V syllables [`sha`], [`nya`], and these are treated the same as normal CV notes. 

Most Japanese voicebanks use kana aliasing, which uses Japanese characters. There are romaji (romanization of japanese characters) aliased voicebanks, but the standard is to use kana aliasing. Because of this, it is recommended (but not required!) to learn to read kana when using Japanese voicebanks.

Aliasing is how each mora is registered in the oto.ini, which is the configuration file for UTAU voicebanks.

The way that voicebank formats are named is by how you type the notes in the piano roll.

For example, `C` represents a consonant, and `V` represents a vowel.

!!! info

    It's recommended to start with Japanese because it's the easiest to use, but there are many languages that can be used in UTAU!


### CV

Consonant-Vowel notes  

CV only has CV and Vs. It's the only format UTAU originally had, and is simple and easy to use.

[`か`] [`え`] [`る`] [`の`] [`う`] [`た`] [`が`]

[`ka`] [`e`] [`ru`] [`no`] [`u`] [`ta`] [`ga`] (romaji)

### VCV

Vowel-Consonant-Vowel notes

VCV has starting CV, VCV, V, and VV. Ending Vs are common but not required.

[`- か`] [`a え`] [`e る`] [`u の`] [`o う`] [`u た`] [`a が`] [`a R`]

[`- ka`] [`a e`] [`e ru`] [`u no`] [`o u`] [`u ta`] [`a ga`] [`a R`] (romaji)

### CVVC

Consonant-Vowel Vowel-Consonant notes

CVVC has CV, V, VV, and VC. Starting CV, V, and ending Vs are optional.

[`か`] [`a え`] [`e r`] [`る`] [`u n`] [`の`] [`o う`] [`u t`] [`た`] [`a g`] [`が`]

[`ka`] [`a e`] [`e r`] [`ru`] [`u n`] [`no`] [`o u`] [`u t`] [`ta`] [`a g`] [`ga`] (romaji)

or

[`- か`] [`a え`] [`e r`] [`る`] [`u n`] [`の`] [`o う`] [`u t`] [`た`] [`a g`] [`が`] [`a R`]

[`- ka`] [`a e`] [`e r`] [`ru`] [`u n`] [`no`] [`o u`] [`u t`] [`ta`] [`a g`] [`ga`] [`a R`] (romaji)

