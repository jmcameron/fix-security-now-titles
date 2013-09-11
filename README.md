# Fix Security Now Titles #

**Fix Security Now MP3 episode titles to include the episode number at the start of the title**

This program will fix the titles of any Security Now episodes so that the
episode number is first in the title. This is useful for smal MP3 players to
make it easier to track your progress when playing multiple episodes.

### USAGE: ###
 - fix_sn_titles sn0420.mp3    # fix this file
 - fix_sn_titles *.mp3         # fix all .mp3 files in this directory
 - fix_sn_titles               # fix all .mp3 files in this directory

### NOTES: ###
  - If a file does not seem to be a Security Now episode, it will not be changed
  - You will need to install the 'tagpy' python library
  - Although created and tested on a Ubuntu system, it uses very generic code
    and should work on any system that supports 'tagpy'

**Jonathan M. Cameron**  
September 10, 2013  
jmcameron@gmail.com
