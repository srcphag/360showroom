Hap for vvvv by Demolition Studios
Free for non-commercial use
For commercial usage, a license is needed (direct contact me via lev.panov@gmail.com)
Please send any bug reports/feature requests to the same address

Requirements: 
1. vvvv >= 45beta34.2
2. dx11 pack >= 1.0.0
3. VAudio pack for audio output (optional)


Changelog

2017-06-20
1. Experimental support of non-multiple of 2 video resolutions
2. Accurate computation of the current frame index
3. The image queue size was increased to 10 frames/100Mb, which gives slightly better performance in some cases
4. Don't seek to the start when the playback is finished
5. Loop pin of HapAudioClock now accepts a boolean (on/off)
6. Fix Opened/Playing outputs of HapState: don't reset to false when opening a single video from the input Path spread
7. HapReaderNode: make number of ouput slices equal to maximum slicecount of (Path, Open) input spreads
8. You can open one video multiple times, or open a video using arbitrary Open slice, without opening all the slices prior to it in the Open spread
9. Now works with vvvv 45beta34.2


HAPEncoder (HAP FFMPEG).v4p contributed by @microdee
This software uses code of FFmpeg licensed under the LGPLv2.1