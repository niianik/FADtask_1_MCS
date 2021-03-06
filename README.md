# EmotionDiscriminationTask

README

Thank you for your interst in doing this task!

We aim to investigate how people discriminate between happy and angry facial expressions. 

Who is eligible? 
- Adults with normal or corrected-to-normal vision


What does the task consist of?
On each trial, a face will briefly appear on the screen. Then, you'll be asked to decide
whether the face was ANGRY or HAPPY, using the left and right arrow keys on the keyboard to respond (1AFC).
You will have 2 seconds to do this. 

The run consists of 480 trials, spread over 5 blocks. You will have a short break every ~5 minutes, 
and the run will take about 30 min in total. 


Want to participate? 

1. Get in touch with me (through Slack, or by sending me an e-mail (niianikolova [at] gmail [dot] com), and I will reply to you with a subject ID code (3 digits, e.g. 001), which you can enter when completing the task. 
2. Make sure you have a working installation of Matlab and Psychtoolbox (Windows: You'll also need GStreamer [download here: https://gstreamer.freedesktop.org/data/pkg/windows/1.16.2/gstreamer-1.0-msvc-x86_64-1.16.2.msi]).
3. Download & save 'EmotionDiscriminationTask' to a directory.
      The directory should contain the following:
         ./code
         ./data
         ./stimuli
         experimentLauncher.m
4. Use a ruler to measure the height and width of your screen (in cm), and note the distance at which you are sitting from the display (default: 2nd screen if there is one). If you don't have a ruler, you can use the default values later, which are for a 13" screen
5. To begin the experiment, navigate to the 'EmotionDiscriminationTask' directory, and 
run 'experimentLauncher.m'.
   You will be asked to enter basic demographic information, your subject ID, and display dimension and viewing distance. If you leave the screen dimensions and viewing distance blank, the default size will be used. Then, the run will begin. Press Esc to quit (partial results will be saved).
   
6. When you have completed a run, the data will be saved in ./data/ with your subject ID. Please e-mail this file back to me. 

*** Please let me know any feedback and bug reports. 
Contact: niianikolova [at] gmail [dot] com ***
