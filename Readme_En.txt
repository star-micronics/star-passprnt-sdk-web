************************************************************
      Star PassPRNT Web SDK Ver 1.1.0
         Readme_En.txt             Star Micronics Co., Ltd. 
************************************************************

 1. Overview
 2. Contents
 3. Scope
 4. Copyright
 5. Release History


=============
 1. Overview
=============

   This package contains Web SDK for Star PassPRNT for iOS / Android / Windows UWP.
   "PassPRNT" is an application intervening outer applications (hereinafter 
   called "Coordinating App" and Star Device (hereinafter called "Device").
   This App transfers to the printer the print data converted from all Coordinating
   App information including receipt design, paper width and other related data.
   Therefore the Coordinating App needs no designing or development to establish
   communication with the printer.
   Similarly printer status and print result are monitored as well so that 
   Coordinating App is not required on such control.

   Receipt design put out of this system is supported by HTML layout, so there is
   no need to understand the device unique command specifications.
   Please refer to document including this package for details.

=============
 2. Contents
=============

  PassPRNT_Web_SDK_Ver1.1.0_20211029
  |
  | Readme_En.txt                       // Release Note(English)
  | Readme_Jp.txt                       // Release Note(Japanese)
  | SoftwareLicenseAgreement.pdf        // Software License Agreement(English)
  | SoftwareLicenseAgreement_jp.pdf     // Software License Agreement(Japanese)
  | UsersManual_Android.url             // Shortcut to User Manual
  | UsersManual_iOS.url
  | UsersManual_UWP.url
  +- Samples                            // Sample program for Star PassPRNT


=================
 3. Scope
=================
  [Software]
    PassPRNT Ver2.5.0 for iOS / Android / Windows UWP

  [Printer Model]
  [Interface]
    Please refer to Users Manual.


==============
 4. Copyright
==============

  Copyright 2020-2021 Star Micronics Co., Ltd. All rights reserved.


==========================================
 5. Star PassPRNT Web SDK Release History
==========================================

 Ver 1.1.0
  2021/10/29  : Added TSP100IV support.
                Added Buzzer (BU01) and  Melody Speaker (mC-Sound) support.

 Ver 1.0
  2020/01/23 : First release.
