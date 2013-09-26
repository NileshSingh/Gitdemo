==================
**1.Introduction**
==================

Rich media resources transmitted over wired and wireless networks are becoming
more and more important in our lives. Users of devices, such as computers, PDAs,
mobile phones, require accessing the Internet and networks from anywhere and at
any time regardless of resources, network conditions, and capabilities of client
devices. Intelligent media conversions, such as scalability, transcoding and
modality changes, are the important means for multimedia adaptation and
Universal Multimedia Access (UMA).


Transcoding is defined, in general, as the conversion of one compressed signal to
another. Transcoding is the direct digital-to-digital data conversion of one
encoding to another, such as for movie data files or audio files. This is usually
done in cases where a target device (or workflow) does not support the format or
has limited storage capacity that mandates a reduced file size, or to convert
incompatible or obsolete data to a better-supported or modern format.


Transcoding can be performed just while files are being searched, as well as for
presentation. The research work concerning transcoding is mainly focused on
efficiency, complexity, latency, processing power, error resilience, bit rate change,
resolution change, frame rate change, picture quality and so forth. To solve the
problems, the coding methods, algorithms and international coding standards used
for design and implementation of transcoding architectures are critical.

============
1.1 Purpose
============

Choosing the perfect video converter software is like choosing the perfect car, it all
depends on what you need the program to do and how far you want to go. In some
cases, all you need is the basic sub-compact without luxury upgrades to get you
from point A to point B. Others need a powerful, feature-filled, mega-program that
will convert just about every file format under the sun.


The main purpose of most video converter programs is to convert media already
on your computer to a more compatible format on other computers or digital
devices. There are three main types of uses for video converter software; to
convert home video, online video and DVD or VCD video.


Emailing and sharing home videos with relatives near and far is a great way to
keep in touch. However, the camcorder or video editing software you use is
usually partial to certain file formats and you don‟t always know the software your
relatives will use to play the video back. Frequently, a well-meaning birthday hello
or introduction to the new baby turns into a lengthy technical phone call. With
video converter software, you can simply change your Windows Media Video to
.AVI or another friendly format.


Video converter software is particularly useful when you own an iPod, but have a
computer that uses Windows. A conundrum many are running into is they are
uploading and editing their home videos on their home computer, but they can‟t
transfer and play them on their iPod. Although iTunes works with Windows, most
of the other Mac based software doesn‟t; including video files.


If your main purpose is to convert home videos directly to your personal computer,
via USB, or to your portable media player look for simple, familiar formats like
.WMV, .AVI, DivX, Xvid and MPEG-2. If you are using a Mac or iPod look for
.MOV and .MP4.


Transcoding can be performed just while files are being searched, as well as for
presentation. For example, Cineon and DPX files have been widely used as a
common format for digital cinema, but the data size of a two-hour movie is about 8
terabytes (TB). That large size can increase the cost and difficulty of handling
movie files. However, transcoding into a JPEG2000 lossless format has better
compression performance than other lossless coding technologies, and in many
cases, JPEG2000 can compress images to half-size.


Transcoding is commonly a loss process, introducing generation loss; however,
transcoding can be lossless if the input is compressed without any loss and the
output is either compressed without any loss or uncompressed. The process of
loss-to-loss transcoding introduces varying degrees of generation loss. In other
cases, the transcoding of lossy to lossless or uncompressed is technically a lossless
conversion because no information is lost, however the process is irreversible and
is more suitably known as destructive.



==========
1.2 Scope
==========

The software helps the user to take existing video and change the format, bitrate
and/or resolution in order to view it on another video device. This software
provides a convenient and easy-to-use graphical user interface to easily and
quickly convert audio/video files to different formats supported by different
platforms (e.g. the newly developed Aakash Tablet), resolution, bit-rate, frame-
rate. The software also helps the user to extract audio from a given video file.


One can also split a video multiple times and assign a unique name to it depending
upon the theme. The application is very easy and convenient to use.



==============================
1.3 Definitions,Abbreviations
==============================
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



================
1.4 Motivation
================

The motivation behind developing Multimedia Transcoder was mainly to make
video converting easy, using the FFmpeg application. The motivation for the
project was to provide a video converter, which can convert a video in a given
format to a desired format, video to audio and to split a given video into the
desired length and parts.



==============================
1.5 Transcoding Vs Conversion
==============================

**Transcoding:** Changes the signal encoding from one format to another without
otherwise altering the signal. The encoding format is changed, but resolution,
aspect ratio, bit-rate, frame-rate, audio channels, etc. remain the same.


**Conversion:** Converts encoding and Signal format but not necessarily resolution
or aspect ratio. Converters with Scaling can adjust the input signal to fit he resolution and aspect ratio of the screen.

- The main thing is to know what you have for an input signal and want for
  an output signal before you begin. If you need a video input or output, then
  that part is easy - use a converter with composite input or output to match
  what you need. You just need to know what you want on the other
  end.Secondly, you have to know the input and output resolutions and signal
  types before choosing an appropriate Transcoder, Converter, or
  Converter/Scaler.
 
- Video Conversion always has an effect on your signal quality. The less
  conversions you do, the better off you will be.

- Quality of the Electronics can have a very large effect on the ultimate sig  nal quality. Since, conversion is NOT, a simple thing.



=============================
1.6 Drawbacks of Transcoding
=============================

The key drawback of transcoding in lossy formats is decreased quality.
Compression artifacts are cumulative, so transcoding causes a progressive loss of
quality with each successive generation, known as digital generation loss. For this
reason, transcoding is generally discouraged unless unavoidable.

It is better to retain a copy in a lossless format (such as TTA, FLAC or WavPack
for sound), and then encode directly from the lossless source file to the lossy
formats required. For digital audio editing, one is advised to save audio in a raw or
uncompressed format and edit (a copy of) that version, only converting to lossy
formats for distribution.

**Although the loss is unavoidable, it can be minimized by choosing the
appropriate resolution and bit-rate.**



================
**2.Objective**
================

To convert and split VIDEO (can be more than one) from one particular format to
any of the following VIDEO formats:

- Mp4

- Avi

- Webm

- Ogv

- Mpeg

- Wmv

- Flv

- Mp4(H.264)

with the change of some properties like

#. Resolution

#. Aspect Ratio

#. Frame Rate

#. Video Bit Rate

To convert and split VIDEO (can be more than one) from one particular format to
any of the following AUDIO formats

- Mp3

- Wav

with the change of some properties like

#. Audio Sample Rate

#. Audio Bit Rate
#. Audio Channels

using JavaFX and FFmpeg.


=====================
**Technologies Used**
=====================

FFmpeg
------

**FFmpeg** is a free software project that produces libraries and programs for
handling multimedia data. The most notable parts of FFmpeg are libavcodec, an
audio/video codec library used by several other projects, libavformat, an
audio/video container mux and demux library, and the FFmpeg command
line program for transcoding multimedia files. FFmpeg is published under
the GNU Lesser General Public License 2.1+ or GNU General Public License 2+
(depending on which options are enabled).

*FFmpeg* is a free software project that produces libraries and programs for
handling multimedia data. The most notable parts of FFmpeg are libavcodec, an
audio/video codec library used by several other projects, libavformat, an
audio/video container mux and demux library, and the FFmpeg command
line program for transcoding multimedia files. FFmpeg is published under
the GNU Lesser General Public License 2.1+ or GNU General Public License 2+
(depending on which options are enabled).

It is a wonderful library for creating video applications or even general purpose
utilities. ffmpeg takes care of all the hard work of video processing by doing all the
decoding, encoding, muxing and demuxing for you. This can make media
applications much simpler to write. It's simple, written in C, fast, and can decode
almost any codec you'll find in use today, as well as encode several other formats.

There is a sample program that comes with ffmpeg called ffplay. It is a simple C
program that implements a complete video player using ffmpeg.

JavaFX2.1
----------

**JavaFX** is a software platform for creating and delivering rich Internet
applications (RIAs) that can run across a wide variety of connected devices. The
current release (JavaFX 2.1, April 2012) enables building applications
for desktop, browser and mobile phones. TV set-top boxes, gaming consoles, Blu-
ray players and other platforms are planned.

Before version 2.0 of JavaFX, app developers used a statically typed, declarative
language called JavaFX Script to build JavaFX applications. However, Java code
could be integrated into JavaFX programs. JavaFX Script was compiled to Java
bytecode, so JavaFX applications could run on any desktop and browser that runs
the Java Runtime Environment (JRE) and on top of mobile phones running Java
ME.

The new JavaFX 2.0 and later is implemented as a native Java library and is
therefore written in native Java code. JavaFX Script has been scrapped by Oracle
but development is being continued in the Visage project.

On desktop, the current release supports Windows XP, Windows Vista and Mac
OS X operating systems. Beginning with JavaFX 1.2, Oracle has released beta
versions for Linux and OpenSolaris. On mobile, JavaFX is capable of running on
multiple mobile operating systems, including Symbian OS, Windows Mobile, and
proprietary real-time operating systems.

**JavaFX 2.1 includes the following main features:**

- H.264 and AAC support
- First official version for Mac OS X (desktop only)
- LCD text
- UI enhancements including combo box controls, charts (stacked chart), and
  menu bars
- Webview component now allows JavaScript to make calls to Java methods

JDK and JRE versions from 1.7.0_04 and onwards include JavaFX bundled to be
installed with them. When Java 8 is available, JavaFX will become part of the
JRE/JDK.


=========================
**4.1JavaFX Application**
=========================

The JavaFX platform is the evolution of the Java client platform designed to
enable application developers to easily create and deploy rich internet applications
(RIAs) that behave consistently across multiple platforms. Built on Java
technology, the JavaFX platform provides a rich set of graphics and media API
with high-performance hardware-accelerated graphics and media engines that
simplify development of data-driven enterprise client applications.

The main focus areas for the JavaFX 2 release include the following features,
many of which are also described in the JavaFX Architecture and Framework
document:

- **Java APIs for JavaFX** that provide all the familiar language features (such
  as generics, annotations, and multithreading) that Java developers are
  accustomed to using. The APIs are designed to be friendly to alternative
  JVM languages, such as JRuby and Scala. Because the JavaFX capabilities
  are available through Java APIs, you can continue to use your favorite Java
  developer tools (such as IDEs, code refactoring, debuggers, and profilers) to
  develop JavaFX applications.

- **A new graphics engine** to handle modern graphics processing units
  (GPUs). The basis of this new engine is a hardware accelerated graphics
  pipeline, called Prism, that is coupled with a new windowing toolkit, called
  Glass. This graphics engine provides the foundation for current and future
  advancements for making rich graphics simple, smooth, and fast.
 
- **FXML, a new declarative markup language** that is XML-based and is
  used for defining the user interface in a JavaFX application. It is not a
  compiled language and, hence, does not require you to recompile the code
  every time you make a change to the layout.

- **A new media engine** that supports playback of the web multimedia content.
  It provides a stable, low latency media framework that is based on the
  GStreamer multimedia framework.

- **A web component** that gives the capability of embedding web pages within
  a JavaFX application using the WebKit HTML rendering technology.
  Hardware accelerated rendering is made available using Prism.

- **A refreshed browser plug-In** for JavaFX 2 that allows the loading of
  JavaFX applets based on Prism.

- **A wide variety of built-in UI controls**, which include Charts, Tables,
  Menus, and Panes. Additionally, an API is provided to allow third parties to
  contribute UI controls that the user community can use

- **Sample applications** that showcase the different features of the JavaFX 2
  technology, along with a large number of code samples and snippets.

- **An updated doclet** used with the Javadoc tool to generate JavaFX API
  documentation in HTML format. Detailed information on how to use this
  updated doclet can be found in Using a Doclet with JavaFX.

=======================================
**4.2 Architecture -JavaFX(Front End)**
=======================================

The sections following the diagram describe each component and how the parts
interconnect. Below the JavaFX public APIs lies the engine that runs your JavaFX
code. It is composed of subcomponents that include the new JavaFX high
performance graphics engine, called Prism; the new small and efficient windowing
system, called Glass; a media engine, and a web engine. Although these
components are not exposed publicly, their descriptions can help you to better
understand what runs a JavaFX application.

.. image :: /image/img1.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

The JavaFX platform combines the best capabilities of the Java platform with
comprehensive, immersive media functionality into an intuitive and
comprehensive one-stop development environment. These new Java APIs for
JavaFX features:

- Allow the use of powerful Java features, such as generics, annotations, and
  multithreading.
- Make it easier for Web developers to use JavaFX from other popular
  dynamic languages, such as JRuby, Groovy, and JavaScript.
- Allow Java developers to use other system languages, such as Groovy, for
  writing large or complex JavaFX applications.

- Allow the use of binding similar to that in JavaFX Script language. This
  includes support for high performance lazy binding, binding expressions,
  bound sequence expressions, and partial bind reevaluation. Alternative
  languages (like Groovy) can use this binding library to introduce binding
  syntax similar to that of JavaFX Script.

- Extend the Java collections library to include observable lists and maps,
  which allow applications to wire user interfaces to data models, observe
  changes in those data models, and update the corresponding UI control
  accordingly.


==========================================
**5.1 FFmpeg(The Backend Software used)**
==========================================

FFmpeg is a complete, cross-platform solution to record, convert and stream audio
and video. It includes libavcodec - the leading audio/video codec library.

FFmpeg reads from an arbitrary number of input "files" (which can be regular
files, pipes, network streams, grabbing devices, etc.), specified by the -i option,
and writes to an arbitrary number of output "files", which are specified by a plain
output filename. Anything found on the command line which cannot be interpreted
as an option is considered to be an output filename.

Each input or output file can, in principle, contain any number of streams of
different types (video/audio/subtitle/attachment/data). Allowed number and/or
types of streams can be limited by the container format. Selecting, which streams
from which inputs go into output, is done either automatically or with the –map.

.. image :: /image/img2.png
     :width: 1500px
     :height: 300px
     :align: center
     :scale: 50%


FFmpeg provides various tools:

- FFmpeg is a command line tool to convert multimedia files between formats.

- FFplay is a simple media player based on SDL and the FFmpeg libraries.

- FFprobe is a is a simple multimedia stream analyzer.


FFmpeg provides various developers libraries:

- libavutil is a library containing functions for simplifying programming,
  including random number generators, data structures, mathematics routines,c  ore multimedia,utilities,and much more.

- libavcodec is a library containing decoders and encoders for audio/video
  codecs.

- libav format is a library containing demuxers and muxers for multimedia
  container formats.

- libavdevice is a library containing input and output devices for grabbing
  from and rendering to many common multimedia input/output software
  frameworks, including Video4Linux, Video4Linux2, VfW, and ALSA.

- libavfilter is a library containing media filters.

- libswscale is a library performing highly optimized image scaling and
  colour space/pixel format conversion operations.

- libswresample is a library performing highly optimized audio resampling,
  rematrixing and sample format conversion operations.



==============================
**5.2 Installation of FFmpeg**
==============================

One can download the latest builds of FFmpeg from
http://ffmpeg.zeranoe.com/builds/ and install the suitable setup. Then setup system path by editing the “user‟s path variable”.



==============================================
**5.3 FFmpeg options used in "FX Converter"**
==============================================

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


================
**UML DIAGRAMS**
================

**USE CASE**
-------------

.. image :: /image/img19.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%

**Use Case 1: Add files**

Primary Actor: End user

Precondition: A new file is to be browsed.

Main scenario:

(a) User can play a file from the list.

(b) User can split a file from the list.

(c) User can convert files as many as needed.

(d) User can split and convert the files.


.. image :: /image/img20.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


**Use Case 2: Video to Video conversion**

Primary Actor: End user

Precondition: A new file is to be browsed.

Main scenario:

(a) User can browse the videos.

(b) User can change the video‟s aspect ratio.

(c) User can change the video‟s resolution.

(d) User can change the video‟s frame rate.

(e)User can select a particular format.


.. image :: /image/img21.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%


**Use Case 3: Video to Audio conversion**

Primary Actor: End user

Precondition: A new file is to be browsed.

Main scenario:

(a) User can browse the videos.

(b) User can select the audio bit rate.

(c) User can select the audio channels.

(d) User can select a particular audio format and convert.


**ACTIVITY DIAGRAM**
---------------------

.. image :: /image/img22.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



#.Browse files to the list.
#.Can drag and drop multiple files
#.Select a file to play.
#.Can select a file and remove.
#.Can clear the whole list
#.Change audio video properties
#.Convert all the files
#.Select a file to split
#.Enter start and end times, and split.
#. Want to split more, browse again.

**CLASS DIAGRAMS**
------------------


.. image :: /image/img23.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%






.. image :: /image/img24.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%






.. image :: /image/img25.png
     :width: 900px
     :height: 600px
     :align: center
     :scale: 50%



===============================
**Conclusion and Future Work**
===============================

To conclude with, all the assigned tasks have been successfully completed by the
team and the above mentioned features are integrated with the project.

Irrespective of this, some future improvements can be done like:

1. File names with commas cannot be converted by this converter. It needs some amendment.

2. Implementation of various splits in the same video. Here a video can be split in maximum 3 parts.

3. HandBrake can be used instead of FFmpeg to improve the efficiency.

4. Design Linux version.


================
**Bibliography**
================

#. http://www.ffmpeg.org

#. http://docs.oracle.com/javafx/index.html

#. http://www.stackoverflow.com

#. http://www.wikipedia.com







