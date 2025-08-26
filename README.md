README
======


------------
 Deaf Tunes
------------
Trey Adams, Drew Culberth, Kenny Ma, Aayush Nanju


----------
 Overview
----------
Deaf Tunes is a program designed to conver audio files into sheet music using the Fast Fourier Transformation (FFT) method. 
The program extracts musical notes from the audio and generates sheet music to help musicians with music transcription.


------------------------------------
 Recommended Hardware Configuration
------------------------------------
	- Operating System: Windows 10 or 11
	- Processor: Intel i5 or higher
	- Memory: 6+ GB
	- Storage: 400+ MB
	
	
----------
 Contents
----------
README.txt					This file
DeafTunes.sln				The Deaf Tunes application
DeafTunes Folder			The folder containing Deaf Tunes resources


---------------------
 Running the program
---------------------
1. Run the DeafTunes.sln file
2. Select the instrument you wish to transcribe. (as of version 1.0.0, only piano is implemented)
3. Click the "Import File" button and import the audio file you wish to transcribe.
4. Click the "Convert Sound to Text" button to convert the audio to data the application can display.
5. Display your sheet music using either buttons under display notes.
6. If you wish to print it or save it as a PDF, click the Export to PDF button.
7. If you have other files you wish to transcribe, click File -> New to load a new window


---------------------------
 Required Program Packages
---------------------------
Music_Transcriber [net8.0-windows7.0]
   > coverlet.collector                   6.0.1
   > FftSharp                             2.1.0
   > Manufaktura.Controls                 1.4.2
   > Manufaktura.Controls.WPF             1.4.0
   > Manufaktura.Core                     1.0.2
   > Manufaktura.Music                    1.1.3
   > Microsoft.NET.Test.Sdk               17.11.1
   > Microsoft.Windows.Compatibility      9.0.0
   > MSTest.TestAdapter                   3.6.4
   > MSTest.TestFramework                 3.6.4
   > NAudio                               2.2.1 
   > NAudio.Core                          2.2.1
   > NAudio.Wasapi                        2.2.1
   > PDFsharp                             6.1.1 
   > QRCoder                              1.6.0
   > ScottPlot.WPF                        5.0.47
   > System.Reactive.Windows.Forms        6.0.1
   > System.Windows.Forms.Ribbon35        3.5.8 
   > TagLibSharp                          2.3.0  
   > WPFSoundVisualizationLibNet5         1.0.0

TestDataViewModelTest [net8.0]
   > Manufaktura.Controls                1.4.2
   > Manufaktura.Core                    1.0.2
   > Manufaktura.Music                   1.1.3
   > Microsoft.NET.Test.Sdk              17.12.0
   > MSTest.TestAdapter                  3.6.4
   > MSTest.TestFramework                3.6.4
   > System.Net.Http                     4.3.4
   > System.Text.RegularExpressions      4.3.1
   
