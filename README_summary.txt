CHARGED Run File Repository: A collection of run cases for testing the SWMF couplings and ability to reproduce reality. 


Current test run cases include:

test_event:
This is a brief, few-hour idealized event.  It should be the basis for doing
functionality tests on new couplings.  Does a new coupling have a tangible
impact?  Use this "event" to test things in a controlled manner.  As new
functionality is added, duplicate & edit these params to create new tests.

test1_doesitwork_RIM: A short run to test the function (or not) of the couplings between RIM and GITM. Uses GM/BATSRUS,IM/RCM2,IE/RIM,UA/GITM.

test2_doesitwork_Ridley_serial: A short run to test the function (or not) of the couplings between Ridley_serial and GITM. Uses GM/BATSRUS,IM/RCM2,IE/Ridley_serial,UA/GITM.




Current real run cases include:
April 5 2010 - Galaxy 15 Event

In each event directory, there are the following sub-directories:
   "Basic" -- A run representing the SWPC v2 configuration (GM/IM/IE only).
              1.9M BATS cells, RCM2, Ridle_serial, robust configuration.
   Add more as necessary!


Current THE CHARGED RUNS include:
