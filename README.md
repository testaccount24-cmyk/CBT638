# CBT638
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 638 is a package to Send Email With Attachments, from     *   FILE 638
//*           Hunter Zhou.                                          *   FILE 638
//*                                                                 *   FILE 638
//*           Hunter Guanghui Zhou                                  *   FILE 638
//*           Phone: 1-(416)-602-9567                               *   FILE 638
//*           E-mail: zhough2000@yahoo.com                          *   FILE 638
//*                                                                 *   FILE 638
//*           The package SENDMAIL is from Hunter Zhou.             *   FILE 638
//*           The package SENDMAIL can send emails with             *   FILE 638
//*           attachments in Mainframe OS/390 and z/OS systems.     *   FILE 638
//*                                                                 *   FILE 638
//*       Program: SENDMAIL (REXX)                                  *   FILE 638
//*       Purpose: Interpret the SYSIN DD and ATTACH DD and send    *   FILE 638
//*                email messages for TCP/IP SMTP service with      *   FILE 638
//*                following features:                              *   FILE 638
//*           1. Support Email Header                               *   FILE 638
//*              . The header supports To: Cc: Bcc: and Subject:    *   FILE 638
//*              . Multiple email addresses are supported.          *   FILE 638
//*              . Supprt comments                                  *   FILE 638
//*           2. Support HTML tags                                  *   FILE 638
//*              . Read SYSIN column 1-72.                          *   FILE 638
//*              . Support HTML tags.                               *   FILE 638
//*           3. Attachements support:                              *   FILE 638
//*              . Text and Binary files                            *   FILE 638
//*              . Multiple attachements                            *   FILE 638
//*              . Descriptions for each attachements               *   FILE 638
//*              . Better performance as calling EMAILENC program.  *   FILE 638
//*                                                                 *   FILE 638
//*       Calling JCL:                                              *   FILE 638
//*           // job card here                                      *   FILE 638
//*           //SENDMAIL EXEC PGM=IKJEFT01,PARM=SENDMAIL            *   FILE 638
//*           //SYSEXEC  DD  DISP=SHR,DSN=SYS1.USER.REXXLIB         *   FILE 638
//*           //SYSTSPRT DD  SYSOUT=*                               *   FILE 638
//*           //SYSTSIN  DD  DUMMY                                  *   FILE 638
//*           //ATTACH   DD  *                                      *   FILE 638
//*             attachment statements                               *   FILE 638
//*           /*                                                    *   FILE 638
//*           //SYSIN    DD  *                                      *   FILE 638
//*             email statements                                    *   FILE 638
//*           /*                                                    *   FILE 638
//*                                                                 *   FILE 638
//*      Program: EMAILENC (HLASM)                                  *   FILE 638
//*      Purpose: Encode squential file for email attachement.      *   FILE 638
//*               The supported encoding algorithms are:            *   FILE 638
//*                                                                 *   FILE 638
//*      Format Encoding Algorithm       Sample data                *   FILE 638
//*      ====== ================== =============================    *   FILE 638
//*      TEXT   Quoted Printable   Any plain text, source code      *   FILE 638
//*      BINARY Base64             Images, program readable data    *   FILE 638
//*                                                                 *   FILE 638
//*      The statistics information is also provided in SYSPRINT    *   FILE 638
//*      DD. The program is designed for better performance.        *   FILE 638
//*                                                                 *   FILE 638
```
