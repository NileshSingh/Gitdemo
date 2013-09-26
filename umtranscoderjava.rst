================
**Introduction**
================

Transcoding is defined, in general, as the conversion of one compressed signal to another. Transcoding is the direct digital-to-digital data conversion of one encoding to another, such as for movie data files or audio files.This is usually done in cases where a target device (or workflow) does not support the format or  has limited storage capacity that mandates a reduced file size, or to convert  incompatible or obsolete data to a better-supported or modern format.

Transcoding can be performed just while files are being searched, as well as for presentation. The research work concerning transcoding is mainly focused on efficiency, complexity, latency, processing power, error resilience, bit rate change, resolution change, frame rate change, picture quality and so forth. To solve the problems, the coding methods, algorithms and international coding standards used for design and implementation of transcoding architectures are critical.

Transcoding is commonly a loss process, introducing generation loss; however, transcoding can be lossless if the input is compressed without any loss and the output is either compressed without any loss or uncompressed. The process of loss-to-loss transcoding introduces varying degrees of generation loss. In other cases, the transcoding of lossy to lossless or uncompressed is technically a lossless conversion because no information is lost, however the process is irreversible and is more suitably known as destructive.


============
**Purpose**
============

If your main purpose is to convert home videos directly to your personal computer, via USB, or to your portable media player look for simple, familiar formats like .WMV, .AVI, DivX, Xvid and MPEG-2. If you are using a Mac or iPod look for .MOV and .MP4.

=================================
**Definitions and Abbreviations**
=================================
+--------------+------------------------------------------------+
| ABBREVIATIONS|       DEFINITIONS                              | 
+==============+================================================+
| FFmpeg       | Fast Forward Motion Picture Experts Group      |
+--------------+------------------------------------------------+
| Transcoding  | digital-to-digital data conversion             |
+--------------+------------------------------------------------+
| Codec        | Program that does both encoding and decoding   |
+--------------+------------------------------------------------+
| GUI          | Graphical User Interface                       |
+--------------+------------------------------------------------+
| AAC	       | Advanced Audio Coding                          |
+--------------+------------------------------------------------+
| FFPlay       | fast Forward Play                              |
+--------------+------------------------------------------------+
| AVI          | Audio Video Interleave                         |
+--------------+------------------------------------------------+
| FLV          | Flash Video                                    |
+--------------+------------------------------------------------+
| OGG          | Operation Good Guys                            |
+--------------+------------------------------------------------+
| OGV	       | Ogg Video                                      |
+--------------+------------------------------------------------+
| MPEG	       | Motion Picture Expert Group                    |
+--------------+------------------------------------------------+
| WAV	       | Windows Wave                                   |
+--------------+------------------------------------------------+
| WMA	       | Windows Media Audio                            |
+--------------+------------------------------------------------+


=============
**Objective**
=============

To convert and split VIDEO (can be more than one) from one particular format to any of the following VIDEO formats:

- Mp4

- Avi

- Webm

- Ogv

- Mpeg

- Wmv

- Flv

- Mp4(H.264)

with the change of some properties like

1. Resolution

2. Aspect Ratio

3. Frame Rate

4. Video Bit Rate

To convert and split VIDEO (can be more than one) from one particular format to

any of the following AUDIO formats

- Mp3

- Wav

with the change of some properties like

1. Audio Sample Rate

2. Audio Bit Rate

3. Audio Channels

using JavaFX and FFmpeg.


=====================
**Technologies Used**
=====================

Technologies Used:

- FFmpeg

- JavaFX 2.1

===========================
**Installation of FFmpeg**
===========================

One can download the latest builds of FFmpeg from http://ffmpeg.zeranoe.com/builds/ and install the suitable setup. Then setup system path by editing the “user‟s path variable”.

=========================================
**FFmpeg options used in “FX Converter”**
=========================================
::

 '-i filename (input)'

input file name

::

 '-target type(output)'

Specify target file type (vcd, svcd, dvd, dv, dv50). type may be prefixed with pal-,
ntsc- or film- to use the corresponding standard. All the format options (bitrate,
codecs, buffer sizes) are then set automatically.

**Split Options**
-----------------

::
 
 '-t duration (output)'

Stop writing the output after its duration reaches duration. duration may be a number in seconds, or in hh:mm:ss[.xxx] form.

::

 '-ss position (input/output)'

When used as an input option (before -i), seeks in this input file to position.
When used as an output option (before an output filename), decodes but
discards input until the timestamps reach position. This is slower, but more
accurate. position may be either in seconds or in hh:mm:ss[.xxx] form.


**Video options**
-----------------
::

 '-vframes number(output)'

Set the number of video frames to record. This is an alias for -frames:v.

::

 '-r[:stream_specifier]fps(input/output,per-stream)'
  
Set frame rate (Hz value, fraction or abbreviation). As an input option,ignore any timestamps stored in the file and instead generate timestamps assuming constant frame rate fps. As an output option, duplicate or drop input frames to achieve constant output frame rate fps (note that this actual  ly causes the fps filter to be inserted to the end of the correspondingfiltergraph).

::

 '-s[:stream_specifier] size (input/output,per-stream)'

Set frame size. As an input option, this is a shortcut for the "video_size" private option, recognized by some demuxers for which the frame size is 21 either not stored in the file or is configurable – e.g. raw video or video grabbers. As an output option, this inserts the scale video filter to the end  of the corresponding filtergraph. Please use the scale filter directly to insert  itat the beginning or some other place. The format is "wxh" (default - same as source).

::

 '-aspect[:stream_specifier] aspect (output,per-stream)'

Set the video display aspect ratio specified by aspect. aspect can be a floating point number string, or a string of the form num:den, where num and den are the numerator and denominator of the aspect ratio. For example "4:3", "16:9", "1.3333", and "1.7777" are valid argument values.

::

 '-vcodec codec(output)'

Set the video codec. This is an alias for -codec:v.



**Audio options**
------------------

::

 '-aframes number (output)'
  
Set the number of audio frames to record. This is an alias for -frames:a.

::

 '-ar[:stream_specifier] freq (input/output,per-stream)'

Set the audio sampling frequency. For output streams it is set by default to the frequency of the corresponding input stream. For input streams this option only makes sense for audio grabbing devices and raw demuxers and is mapped to the corresponding demuxer options

::

 '-ac[:stream_specifier] channels (input/output,per-stream)'

Set the number of audio channels. For output streams it is set by default to
the number of input audio channels. For input streams this option only
makes sense for audio grabbing devices and raw demuxers and is mapped to
the corresponding demuxer options.

::

 '-acodec codec (input/output)'

Set the audio codec. This is an alias for -codec:a.


=====================================
**Design and Implementation of GUI**
=====================================

**Main GUI**
-------------


.. image :: /image/img3.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



**CONVERT PANEL**
------------------

Browse Button:



	It is used to browse the files for the input List.
	

.. image :: /image/img4.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



Multi Selection:


	One can browse multiple files to the Input List.


Drag and Drop multiple files:

 
	One can also browse multiple files to the Input List through drag and drop.

.. image :: /image/img5.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


Play Button:


	It is used to play the selected input file from List.


.. image :: /image/img6.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


Remove Button:


	 It is used to remove the selected file from Input/Output List.

.. image :: /image/img7.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

Clear All Button:

	It is used to clear the entire Input List.

.. image :: /image/img8.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


Destination Button:


	The default Output folder is the current working directory.The user can choose any destination folder by browsing, using this button.
 
.. image :: /image/img9.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



**Audio-video Properties:**


	Additional options can be selected by using settings button.

- Video Bit rate: It is used to select different bitrates from listed values.

- Video Frame Rate: It is used to select different frame rates from listed values.

- Resolution: It is used to set the different resolutions for videos.

- Aspect Ratio: It is used to set the aspect ratio for video.

- Audio Bit rate: It is used to select different bitrates from listed values.

- Sample Rate: It is used to select different frame rates from listed values.

- Audio Channels: It is used to set number of audio channels to either 1 or 2. It is 2 by default.

.. image :: /image/img10.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



Format Radio Buttons:


	They are used to convert the Input files to a particular format.

Convert Button:


	It is used to convert the input files to different formats and codecs.

.. image :: /image/img11.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

Cancel Button:


	The conversion of files can be cancelled using cancel button. It will delete the file which is presently converting.

.. image :: /image/img12.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


**SPLIT PANEL**
----------------

.. image :: /image/img13.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


File Names:


	The different parts of same converted file can be given different names.

.. image :: /image/img14.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

Start and End Times:


	The video can be split in different parts, for that the text fields will get the start and end time in the format of hh:mm:ss.


.. image :: /image/img15.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

Destination Button:


	The default output folder is the current working directory. The user can choose any destination folder by browsing, using this button.


.. image :: /image/img16.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


**AUdio-Video Properties**

- Audio Bit rate: Select different bitrates from listed values.

- Sample Rate: Select different frame rates from listed values.

- Audio Channels: Set the number of audio channels to either one or two. It is 2  by default.
- Video Bit rate: It is used to select different bitrates from listed values.

- Video Frame Rate: It is used to select different frame rates from listed value  s.
- Resolution: It is used to set the different resolutions for videos.

- Aspect Ratio: It is used to set the aspect ratio for video.

.. image :: /image/img17.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


Split Button:


	It will convert and split the selected video in one or more parts(max 3).

.. image :: /image/img18.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%






