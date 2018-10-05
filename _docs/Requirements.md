## *NightBook* Requirements

*NightBook* will be a system for recording (from the DOL User Manual):

> the general happenings during each night of observation or maintenance session. This includes weather updates,
> people at the telescope (TOs, PIs and other visitors), as well as faults, errors, bugs, & oddities.*

1. *NightBook* will be written in Python
2. *NightBook* will have some kind of graphical user interface, probably PyQt but we should discuss it being
   a webapp that can be used in a browser.
3. *NightBook* will store event information in an SQL database, or some other easily searchable structure.
4. *NightBook* will record information in four categories (from current DOL version, with sub-categories):
   * People
   * System
     * Tuning
       * WOLM
       * Pointing
     * StartupShutdown
       * Startup
       * Shutdown
     * Configuration
       * Electrical
       * Mechanical
       * Software
       * Configuration File Update
     * System Note
   * Science
     * Data Collection
     * Environmental Update
     * Science Note
     * Time Lost
       * Guider/WFS Failure
       * Instrument Failure
       * Telescope/Facility
       * Weather
       * Other
   * Problems
     * Software
       * Instrument
       * GWAVES
       * Telescope
     * Hardware
       * GWAVES
       * Instrument
       * Telescope
     * Unclassified
5. *NightBook* will give the user a window to type in comments on the various categories.
6. *Nightbook* will allow the user to use voice recognition for input if desired.
7. *NightBook* will keep up-to-date information of all logs on disk at all times to enable recovery from
   power outages or computer crashes.
   
### Questions

1. Can *NightBook* be used by the NPOI operators at all?

Len says:

(NPOI operators use the "obslog" system for logging activity throughout the night). It may be possible
 to integrate the nightly obslog in to the "NightBook" log but I am uncertain of the motivation for doing so.
   
