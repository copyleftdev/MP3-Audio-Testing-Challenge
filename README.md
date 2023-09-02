# MP3 Audio Testing Challenge

## Introduction

Welcome to the MP3 Audio Testing Challenge. In this exercise, you are provided with an MP3 file. Your objective is to extract various audio attributes from this file and assert their accuracy based on specific specifications provided.

## Objectives

Your challenge is to extract the following details from the MP3 file:

- Title
- Artist
- Album
- Genre
- Duration
- Channels
- Sample Rate
- Bit Rate
- RMS Value
- Spectrogram File Name
- MD5 Checksum
- SHA256 Checksum

And ensure they match the given specifications.

## Provided Materials

1. **MP3 File:** never_gonna_give_you_up.mp3
2. **Spectrum Reference**  rick-roll_spectrogram.png

## Specifications

You are expected to ensure that the MP3 file meets the following specifications:

- **Title:** None
- **Artist:** None
- **Album:** None
- **Genre:** None
- **Duration:** 211.181875
- **Channels:** 1
- **Sample Rate:** 44100
- **Bit Rate:** 128000
- **RMS Value:** 0.11535356193780899
- **Spectrogram File Name:** rick-roll_spectrogram.png compare spectrum image to reference image
- **MD5 Checksum:** ee36d061b7345b8cbbd3157fa78ba162
- **SHA256 Checksum:** ef62dbc5a733f97af7f692fc8deff70e885b210a6585cf420f78f3f3b2ba4127

## Evaluation Criteria

1. Accurate extraction and verification of each MP3 attribute against the specifications provided.
2. The efficiency of the implemented solution.
3. Clarity, organization, and documentation of the code.
4. Handling potential errors or discrepancies in the MP3 file attributes.

## Hints

- While solutions in all programming languages are welcomed, consider using Python with libraries like `librosa`, `pydub`, and `hashlib` if you're familiar with them.
- Make sure to save the spectrogram image with the specified name and format.
- It may be useful to wrap your tests in a testing framework (like pytest for Python) for easy validation and repeatability.

## Deliverables

1. A script, program, or toolset, written in the language of your choice, that extracts and validates the required information from the MP3 file against the provided specifications.
2. Any accompanying documentation or notes on the implementation, discrepancies (if found), and the methodology used.

## Conclusion

This challenge is designed to assess your skills in audio processing, data validation, and software testing. Approach it methodically, ensuring every specification is met and validated. Good luck!

---

You can use the above markdown content for your challenge README.md file. Adjust any details, such as the MP3 filename, if necessary.
