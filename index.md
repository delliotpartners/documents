<img src="https://github.com/delliotpartners/assets/blob/master/logo.png" style="float:right;" width="48"><br clear="all" />


# Dell IOT Solutions Partner Program

## Self-Certification Guide

Created by Chad Young  
<chad.young@dell.com>  
Version 0.001
August 17, 2016  

Self-Certification

Self-certification is being implemented to increase the speed with which
a potential partner can complete the qualification phase of onboarding
them into the partner program. The following document will guide you
through the steps that are needed to complete self-certification, point
out key areas of qualification process, supply links to supporting
documentation, and contact information if you still have questions after
reading the document.

## Steps needed to complete qualification


1.  Choose a qualification Method  
    a.  Qualification by Proxy  
    b.  Single unit qualification  

2.  Review the list of Dell IOT devices that are available to
    self-qualify on.  
    a.  Edge gateway 3001, 3002, 3003  
    b.  Edge gateway 5000/5100  
    c.  Embedded Box PC 3000  
    d.  Embedded Box PC 5000  

3.  Choose which factory installed Operating System you want to use for
    qualification  
    a.  Microsoft Windows  
    b.  Ubuntu Core 16  
    c.  Ubuntu Desktop 16.04  
    * This is only available on Embedded Box PCs  

4.  Acquire a system for testing/validation/and qualification.  
    &lt;Reference Section X&gt;

5.  Conduct testing and validation of your software  
    &lt;Reference Section X&gt;
    a.  If you have chosen UC16 as an OS you must follow the approved
        install method  
        i.  Ubuntu snap  
        ii. Docker image  
    b.  Complete your qualification testing  
    c.  Complete the qualification form  
        &lt;Reference this document&gt;
    d.  Send your qualification form to Chad Young  

6.  If you use UC16 and you make a snap – you have to send that snap to
    me  

Qualification of Dell IOT devices
=================================

Qualification by Proxy
----------------------

You can qualify on as many Dell IOT devices as you would like, however,
we would suggest that you consider the “Qualification by Proxy” method.
The “Qualification by Proxy” method is designed to give the potential
partner the easiest path to qualification on as many Dell IOT devices as
possible. In simple terms “Qualification by Proxy” allows you to qualify
your software application on the lowest common denominator Dell IOT
device and receive qualification for all higher configurations of Dell
IOT devices (given the same OS – Windows or Linux). Qualification by
Proxy primary tenets:

-   Select a Dell IOT device that meets the specifications supported by
    your application

-   Select a factory OS

-   Select application install method

-   Pass and achieve qualification status on all Dell IOT devices (a)
    with hardware specifications that are the same or greater than the
    device you are qualifying on for and (b) support the operating
    system you are qualifying on

Here are a few examples to help you understand how Qualification by
Proxy works.

Example 1: Qualification on a Single System

  ---------------------------------------------------------------------------------------------------------------------
  Application XYZ, requires a minimum processor speed of 2.0GHz and 16GB of RAM
  
  Partner chose the ePC 5000
  
  Partner chose Windows 10
  
  Partner chose the .exe application install method
  ---------------------------------------------------------------------------------------------------------------------
  Partner passes self-qualification

  Partner is granted qualification on only one IoT device, the ePC 5000

  Why? The EGW 3000, EGW 5000, and the ePC 3000 systems do not offer the minimum processor speed of 2.0GHz or higher.
  ---------------------------------------------------------------------------------------------------------------------

\*ePC = Embedded Box PC, \*EGW = Edge Gateway

Example 2: Qualification on Multiple Systems by Proxy

  -----------------------------------------------------------------------------------------
  Application PDQ, requires a minimum processor of 1.0Ghz and 4GB RAM
  
  Partner chose any system that supports 4GB memory, for example the EGW 5000
  
  Partner chose Ubuntu Core 16
  
  Partner chose the Docker application install method
  -----------------------------------------------------------------------------------------
  Partner passes self-qualification

  Partner is granted qualification across three IoT devices; EGW 5000, ePC 3000, ePC 5000

  The application would not be granted qualification for the GW 3000.
  
  Why? The GW 3000 only comes with 2GB of system memory
  -----------------------------------------------------------------------------------------

\*ePC = Embedded Box PC, \*EGW = Edge Gateway

Single Unit Qualification
-------------------------

Qualification by proxy is not required and in some cases it may make
more sense to complete qualification of a single Dell IOT device. If
that is the case you can still complete self-certification by following
the procedures listed in this guide.

### Other considerations for Qualification by Proxy

Qualifying that a software application can “run” on a particular Dell
IOT device does not reflect how it will behave when a complete IOT
solution is implemented in a given use case. Dell, encourage you to
consider future hardware and software needs when choosing a Dell IOT
device to qualify such that the hardware has sufficient headroom for
future product enhancements.

Dell IOT Devices available to self-qualify on
=============================================

Currently there are four models of Dell IOT devices that a potential
partner can qualify on. There is the Edge Gateway 3000, and 5000 series
as well as the Embedded Box PC 3000, and 5000 series. Dell does not
prescribe a minimum system configuration for qualification. We, Dell,
leave this up to the potential partner – we believe that you know the
needs and limitations of you software/application better than we do.
Choose what you think is best for your IOT solution.

Dell IOT Device Specification
-----------------------------

Specifications for Dell IOT devices can be found here:

-   Edge gateway 3000 series

    <http://i.dell.com/sites/doccontent/shared-content/data-sheets/en/Documents/Dell_Edge_Gateway_3000_Series_spec_sheet.pdf>

-   Edge gateway 5000/5100 series

    <http://i.dell.com/sites/doccontent/corporate/secure/en/Documents/edge-gateway-specsheet.pdf>

-   Embedded Box PC 3000 & 5000 series

    <http://i.dell.com/sites/doccontent/shared-content/data-sheets/en/Documents/specsheet-dell-embedded-box-PC-3000-5000.pdf>

Dell IOT Factory Operating System
=================================

As part of the self-qualification process ***you MUST qualify your
software application on one of the factory images listed below that is
associated with the Dell IOT device you are qualifying on. ***

Dell Edge Gateways – two operating systems

1.  Ubuntu Core 16

    a.  Ubuntu Core 16 and Ubuntu Desktop 16.04 are not the same.

    b.  <https://www.ubuntu.com/core>

2.  Windows 10 IOT Enterprise 2015 LTSB

    a.  <http://wincom.blob.core.windows.net/documents/Windows_10_IoT_Platform_Overview.pdf>

Dell Embedded Box PCs – two operating systems

1.  Ubuntu Desktop 16.04

    a.  <https://www.ubuntu.com/desktop>

2.  Windows 10 IOT Enterprise 2015 LTSB

    a.  <http://wincom.blob.core.windows.net/documents/Windows_10_IoT_Platform_Overview.pdf>

Approved application installation methods
=========================================

                               EGW 3K   EGW 5K/51K   ePC 3K   ePC 5K
  ---------------------------- -------- ------------ -------- --------
  UC16 Snap                    X        X            ---      ---
  UC16 Docker                  X        X            ---      ---
  Windows (\*.exe or \*.msi)   X        X            X        X
  Windows Docker               X        X            X        X
  Windows Other                ?        ?            ?        ?
  UD 16.04 Snap                ---      ---          X        X
  UD 16.04 Docker              ---      ---          X        X
  UD 16.04 Other               ?        ?            ?        ?

? = inquire with the qualification manager <chad.young@dell.com>

Acquire a system for testing/validation/and qualification. 
===========================================================

One of the requirements for passing qualification is that you
demonstrate that your software application will run/perform on a Dell
IOT device; the Dell Edge Gateway 300\[1,2,3\], the Dell Edge Gateway
5000/51000, the Dell Embedded Box PC 3000, or the Dell Embedded Box PC
5000. There are two ways of acquiring Dell IOT Devices:

**Primary**

Purchase a system on the open market

-   *Dell Website*

    <http://www.dell.com/en-us/work/shop/scc/sc/gateways-embedded-pcs?~ck=mn>

-   *Mouser Website*

    <http://www.mouser.com/Search/Refine.aspx?Keyword=dell+gateway>

    <http://www.mouser.com/All-Manufacturers/_/N-0?Keyword=dell+embedded+box+pc>

**Secondary\***

Inquiring with your existing Dell Sales Executive or regional Business
Development Manager if a loaner system is available for use.

------------------------------------------------------------------------------------------------------------------------------------------

\* This method, while attractive from a cost savings perspective, is
usually not preferable as there can be long delays in receiving loaner
units due to their limited availability. Most partners, after waiting to
receiving a loner, have said that they would have purchased a unit if
they had known how long it would take to get one. Additionally you will
have to return the system which will keep you from actively validating
you software application runs on the Dell IOT Device.

Partner validation and testing 
===============================

Dell trusts that potential partners will conduct their own hardware and
software validation. In addition to that validation effort, Dell
requires that you add the following process to your validation work, if
not already included, to ensure that your software application is
functioning as expected on the Dell IOT device that you are qualifying
on.

Step 1 – Data comes into the box.
---------------------------------

As an Edge Gateway or Embedded Box PC it is expected that some kind of
data will be flowing into the system from a data source; another box
collecting data, IP devices (TCP/IP, Modbus TCP, etc., wireless (Wi-Fi,
BT, ZigBee), or even serial devices (RS-232/RS-422, RS-485, or other).
You will need to demon straight that your box will receive data via some
communication protocol (which communication protocol used is completely
up to you.)

Step 2 – Data interacts with your software application
------------------------------------------------------

Now that you have data coming into the box, your software application
needs to do something with it. A couple of quick examples that I have
seen are (1) data pass through – this is where the box is simply used to
pass data from a sensor to a cloud instance where that data can be
analyzed in the cloud or data center. (2) Edge analysis – this is where
the box analyses incoming data and then if an event is recognized it
directs action to be taken.

Step 3 – View that something has occurred
-----------------------------------------

Now that the data has interacted with your software there are a few ways
that we can ensure that some interaction has occurred.

\(1) The data that was passed to the data center or a cloud instance – we
can see via a remote file manager or cloud dashboard that files were in
fact sent and or received.

\(2) The data that was used in local analytics and then passed to a data
center or cloud instance - we can see via a local or remote file manager
or cloud dashboard that files were in fact sent and or received. We can
also look at local or remote log files show if actions were taken when
actions were triggered.

3 part process

Data comes into the box

Data interacts with your software application

Data is passed to a cloud instance
----------------------------------

Modified data is either stored locally and can be viewed locally or is
pushed to a cloud instance where it can be viewed in cloud dashboard

Your software application and the Dell IOT device can

What we are looking for is verification that you can do end – to – end
data transfer

We want to see end to end data transfer in the demonstration

Whatever your application does it is expected to do something with the
data that is coming into the system from either sensors or other data
streams.

\(1) Your application must run on the EGW3000 and on one of our factory
OS images in one of the following ways

Windows 10 IOT Enterprise – Typical Windows application

Ubuntu Core 16 – All components of your application/software running
from a UC snap

Ubuntu Core 16 – All components of your application/software running
from a Docker container/image.

(2)

I need to be able to see the end-to-end data flow on a EGW 3000 – the
three phases below:

\(a) data flowing into the box

\(b) said data interacting with your application/software

\(c) visualization of your data being transformed in some manner, either
locally on the gateway or in the cloud.
