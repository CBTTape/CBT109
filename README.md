# CBT109
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 109 CONTAINS AN IEFACTRT SMF EXIT FROM FIRST CHICAGO,     *   FILE 109
//*           THIS VERSION OF THE CODE RUNS UNDER MVS/ESA.  THIS    *   FILE 109
//*           FILE ALSO CONTAINS CODE TO SUPPORT 2260'S UNDER ESA.  *   FILE 109
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT.  SEE FILE 110  *   FILE 109
//*           FOR A SAMPLE OF THE OUTPUT                            *   FILE 109
//*                                                                 *   FILE 109
//*           ASMACTRT IS THE JCL WE USE TO ASSEMBLE THE SMF        *   FILE 109
//*                    EXIT IEFACTRT.  YOU WILL NEED TO CHANGE      *   FILE 109
//*                    THE JCL ACCORDINGLY.                         *   FILE 109
//*                                                                 *   FILE 109
//*           IEFACTRT IS THE SOURCE CODE FOR THE IEFACTRT EXIT     *   FILE 109
//*                    AS WE USE IT.  THIS SOURCE IS A              *   FILE 109
//*                    COMBINATION OF VARIOUS IEFACTRT ROUTINES     *   FILE 109
//*                    FROM PREVIOUS CBT TAPES AND SOME OF MY       *   FILE 109
//*                    OWN ENHANCEMENTS.  IT HAS BEEN WRITTEN       *   FILE 109
//*                    TO USE THE SMF TYPE 30 RECORD AND TO RUN     *   FILE 109
//*                    IN 31 BIT ADDRESSING MODE.  AN EXAMPLE       *   FILE 109
//*                    OF THE OUTPUT IS INCLUDED IN ANOTHER         *   FILE 109
//*                    FILE ON THIS TAPE. THIS EXIT WILL WORK       *   FILE 109
//*                    UNDER MVS/XA 2.2 AND MVS/ESA.  IT SHOULD     *   FILE 109
//*                    BE ABLE TO RUN UNDER PREVIOUS XA             *   FILE 109
//*                    RELEASES.                                    *   FILE 109
//*                                                                 *   FILE 109
//*                    FEATURES - ISSUSES A WTO TO THE SYSTEM       *   FILE 109
//*                               CONSOLE WITH THE COMPLETION       *   FILE 109
//*                               CODE OF EACH STEP.                *   FILE 109
//*                                                                 *   FILE 109
//*                             - WRITES THE WTO INFORMATION TO     *   FILE 109
//*                               THE JOBLOG                        *   FILE 109
//*                                                                 *   FILE 109
//*                             - GIVES EXCP STATS FOR EACH DD      *   FILE 109
//*                               ALLOCATED.                        *   FILE 109
//*                                                                 *   FILE 109
//*                             - DDNAME, CONCATENATION NUMBER,     *   FILE 109
//*                               AND DEVICE ADDRESS ARE            *   FILE 109
//*                               INCLUDED. ON MESSAGE LOG.         *   FILE 109
//*                                                                 *   FILE 109
//*            LNKACTRT JCL USED TO LINK THE IEFACTRT EXIT.         *   FILE 109
//*                     THE JCL WILL HAVE TO BE CHANGED.            *   FILE 109
//*                                                                 *   FILE 109
//*            CBPUC001 THIS MODULE IS THE USER INTERFACE           *   FILE 109
//*                     MODULE (UIM) WE WROTE TO SUPPORT 2260       *   FILE 109
//*                     UNDER MVS/XA 2.2.  IT ALSO WORKS FOR        *   FILE 109
//*                     ESA                                         *   FILE 109
//*                                                                 *   FILE 109
//*            IEAMLT99 THIS MODULE IS ALSO REQUIRED TO SUPPORT     *   FILE 109
//*                     THE 2260'S                                  *   FILE 109
//*                                                                 *   FILE 109
//*                               DISCLAIMER                        *   FILE 109
//*                                                                 *   FILE 109
//*            THESE PROGRAMS ARE BEING USED SUCCESSFULLY IN        *   FILE 109
//*            OUR ENVIRONMENT.  SUPPORT IS ON AN AS IS BASIS.      *   FILE 109
//*            THESE MODULES HAVE BEEN RUNNING SUCCESSFULLY         *   FILE 109
//*            UNDER MVS/XA 2.2 AND MVS/ESA.  THEY SHOULD BE        *   FILE 109
//*            ABLE TO RUN WITH EARLIER RELEASES OF MVS/XA.         *   FILE 109
//*                                                                 *   FILE 109
```
