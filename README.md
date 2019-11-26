# Eliot's-NIKA
Branch of NIKA which adds custom functionality for RSoXS and GIWAXS based in Igor Pro

developed by Eliot Gann originally at North Carolina State University, then at Monash university, and currently at NIST with the help of many other people (most notably Brian Collins of NCSU and now WSU) contact Eliot Gann (eliot.gann@nist.gov) with any questions.  The NIST RSoXS browser component is the only actively maintained part of the package, but I will probably be able to help with any reasonable requests.

These are a set of useful tools which I have used in my research over the last decade, and which I made before I knew how to code properly.  I include the branched NIKA files which have been edited from the original signifigantly, but are still under that license.  Please cite NIKA properly if you use this to analyze any data.  (see https://usaxs.xray.aps.anl.gov/software/nika for how to cite NIKA as well as the much updated current version of NIKA which is  of course NOT compatible with any of these procedures anymore, but has also added some of these features over the years). This is not how software development should happen, so please feel free to make any changes you like to this code, but please just make them available to everyone by creating pull requests on this repository.

If you run into any problems, besides just emailing me, please create an issue in github as well, so others can try their hand at fixing it as well.

Suggested Installation Method:

1.) Clone this repository to your local machine.  (I strongly suggest to download github desktop, which makes this incredibly easy, unless you are a github expert already.  Just paste the repository address in and hit clone)

2.) Find out where the repository is stored on your local computer

3.) open your user files directory (from Igor Pro  select Help-> Igor Pro User Files)
    usually this is in the documents/wavemetrics/ folder
    (close Igor after this step)

4.) create a shortcut (windows) or alias (Mac) of RSoXSMenus.ipf and 'Boot Nika.ipf' files in the "Igor Procedures" directory

5.) create a shortcut or alias of all of the rest of the files and those in the directory and subdirectory into a NIKA subdirectory (make one if there isn't one already) within the "User Procedures" directory

6.) Install XMLUtils (https://www.wavemetrics.com/project/XMLutils)

7.) Restart Igor Pro, you should see the RSoXS menu appear
