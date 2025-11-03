TEMPLATE based on file for Budapest


TRACKS:

1 BINAURAL MASTER (volume of 5th order ambi signal to stereo out)

2 BINAURAL DECODER (decodes ambi signals from STEREO-ENCODER and MULTI-ENCODER TRACKS 9, 10)
	for more source-tracks simply copy track 9 or 10)

3 OCTO MASTER (volume of 5th order ambi signal to SEM octophonic out)

4 OCTO DECODER (decodes ambi signals from STEREO-ENCODER and MULTI-ENCODER TRACKS 9, 10)
	using SEM_octoDecoder.json (java-script-object notation file;
	generated via ALLRADecoder Plugin, read this: https://www.researchcatalogue.net/view/1418171/1424397 )

5 DOME_MASTER (volume of 5th order ambi signal to DOME - BUDAPEST)

6 DECODE DOME 
7 DECODE SUB (4 SUBS)

9 and 10 STEREO-ENCODER and MULTI-ENCODER TRACKS
	your sounds live here to move around (duplicate these tracks..)
	-> stereo-encoder (or mono): move mono(st)-sound
	-> multi-encoder (n chan-file): move n-channel-files

To listen and render use one of the masters while muting the others.
(The Master Track is not used in this template.)