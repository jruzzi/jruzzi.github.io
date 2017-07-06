++++
<table cellspacing="0" cellpadding="0" width="100%">
<tr>
<td align="left" valign="top"><b>Java Platform, Enterprise Edition The Java EE Tutorial</b><br />
<b>Release 7 Java Platform, Enterprise Edition</b><br />
E39031-02</td>
<td valign="bottom" align="right">
<table cellspacing="0" cellpadding="0" width="225">
<tr>
<td>&nbsp;</td>
<td align="center" valign="top"><a href="toc.md"><img src="img/toc.gif" alt="Go To Table Of Contents" /><br />
<span class="icon">Contents</span></a></td>
</tr>
</table>
</td>
</tr>
</table>
<hr />
<table cellspacing="0" cellpadding="0" width="100">
<tr>
<td align="center"><a href="toc.md"><img src="img/leftnav.gif" alt="Previous" /><br />
<span class="icon">Previous</span></a>&nbsp;</td>
<td align="center"><a href="preface.md"><img src="img/rightnav.gif" alt="Next" /><br />
<span class="icon">Next</span></a></td>
<td>&nbsp;</td>
</tr>
</table>
++++


[[java-platform-enterprise-edition]]
Java Platform, Enterprise Edition
---------------------------------

The Java EE Tutorial

Release 7

E39031-02

September 2014

Beta Draft

[[sthref1]]

'''''

Java Platform, Enterprise Edition The Java EE Tutorial, Release 7

E39031-02

Copyright © 2014, Oracle and/or its affiliates. All rights reserved.

Primary Author:  Eric Jendrock, Ricardo Cervera-Navarro, Ian Evans, Kim
Haase, William Markito

Contributing Author:  

Contributor:  

This software and related documentation are provided under a license
agreement containing restrictions on use and disclosure and are
protected by intellectual property laws. Except as expressly permitted
in your license agreement or allowed by law, you may not use, copy,
reproduce, translate, broadcast, modify, license, transmit, distribute,
exhibit, perform, publish, or display any part, in any form, or by any
means. Reverse engineering, disassembly, or decompilation of this
software, unless required by law for interoperability, is prohibited.

The information contained herein is subject to change without notice and
is not warranted to be error-free. If you find any errors, please report
them to us in writing.

If this is software or related documentation that is delivered to the
U.S. Government or anyone licensing it on behalf of the U.S. Government,
then the following notice is applicable:

U.S. GOVERNMENT END USERS: Oracle programs, including any operating
system, integrated software, any programs installed on the hardware,
and/or documentation, delivered to U.S. Government end users are
"commercial computer software" pursuant to the applicable Federal
Acquisition Regulation and agency-specific supplemental regulations. As
such, use, duplication, disclosure, modification, and adaptation of the
programs, including any operating system, integrated software, any
programs installed on the hardware, and/or documentation, shall be
subject to license terms and license restrictions applicable to the
programs. No other rights are granted to the U.S. Government.

This software or hardware is developed for general use in a variety of
information management applications. It is not developed or intended for
use in any inherently dangerous applications, including applications
that may create a risk of personal injury. If you use this software or
hardware in dangerous applications, then you shall be responsible to
take all appropriate fail-safe, backup, redundancy, and other measures
to ensure its safe use. Oracle Corporation and its affiliates disclaim
any liability for any damages caused by use of this software or hardware
in dangerous applications.

Oracle and Java are registered trademarks of Oracle and/or its
affiliates. Other names may be trademarks of their respective owners.

Intel and Intel Xeon are trademarks or registered trademarks of Intel
Corporation. All SPARC trademarks are used under license and are
trademarks or registered trademarks of SPARC International, Inc. AMD,
Opteron, the AMD logo, and the AMD Opteron logo are trademarks or
registered trademarks of Advanced Micro Devices. UNIX is a registered
trademark of The Open Group.

This software or hardware and documentation may provide access to or
information about content, products, and services from third parties.
Oracle Corporation and its affiliates are not responsible for and
expressly disclaim all warranties of any kind with respect to
third-party content, products, and services unless otherwise set forth
in an applicable agreement between you and Oracle. Oracle Corporation
and its affiliates will not be responsible for any loss, costs, or
damages incurred due to your access to or use of third-party content,
products, or services, except as set forth in an applicable agreement
between you and Oracle.

This documentation is in preproduction status and is intended for
demonstration and preliminary use only. It may not be specific to the
hardware on which you are using the software. Oracle Corporation and its
affiliates are not responsible for and expressly disclaim all warranties
of any kind with respect to this documentation and will not be
responsible for any loss, costs, or damages incurred due to the use of
this documentation.

The information contained in this document is for informational sharing
purposes only and should be considered in your capacity as a customer
advisory board member or pursuant to your beta trial agreement only. It
is not a commitment to deliver any material, code, or functionality, and
should not be relied upon in making purchasing decisions. The
development, release, and timing of any features or functionality
described in this document remains at the sole discretion of Oracle.

This document in any form, software or printed matter, contains
proprietary information that is the exclusive property of Oracle. Your
access to and use of this confidential material is subject to the terms
and conditions of your Oracle Master Agreement, Oracle License and
Services Agreement, Oracle PartnerNetwork Agreement, Oracle distribution
agreement, or other license agreement which has been executed by you and
Oracle and with which you agree to comply. This document and information
contained herein may not be disclosed, copied, reproduced, or
distributed to anyone outside Oracle without prior written consent of
Oracle. This document is not part of your license agreement nor can it
be incorporated into any contractual agreement with Oracle or its
subsidiaries or affiliates.

++++
<hr />
<table cellspacing="0" cellpadding="0" width="100%">
<col width="33%" />
<col width="*" />
<col width="33%" />
<tr>
<td valign="bottom">
<table cellspacing="0" cellpadding="0" width="100">
<col width="*" />
<col width="48%" />
<col width="48%" />
<tr>
<td>&nbsp;</td>
<td align="center"><a href="toc.md"><img src="img/leftnav.gif" alt="Previous" /><br />
<span class="icon">Previous</span></a>&nbsp;</td>
<td align="center"><a href="preface.md"><img src="img/rightnav.gif" alt="Next" /><br />
<span class="icon">Next</span></a></td>
</tr>
</table>
</td>
<td><img src="img/oracle.gif" alt="Oracle Logo" /> <a href="img/cpyr.md"><br />
<span>Copyright&nbsp;&copy;&nbsp;2014,&nbsp;Oracle&nbsp;and/or&nbsp;its&nbsp;affiliates.&nbsp;All&nbsp;rights&nbsp;reserved.</a><br>
ORACLE&nbsp;CONFIDENTIAL.&nbsp;For&nbsp;authorized&nbsp;use&nbsp;only.&nbsp;Do&nbsp;not&nbsp;distribute&nbsp;to&nbsp;third&nbsp;parties.</span></td>
<td valign="bottom" align="right">
<table cellspacing="0" cellpadding="0" width="225">
<tr>
<td>&nbsp;</td>
<td align="center" valign="top"><a href="toc.md"><img src="img/toc.gif" alt="Go To Table Of Contents" /><br />
<span>Contents</span></a></td>
</tr>
</table>
</td>
</tr>
</table>
<p align="center"></p>
++++