BC eZ Admin Design Override
========================

bcezadmindesignoverride is a simple design extension override for the default eZ Publish Legacy Administration

- Source code: http://github.com/bcezadmindesignoverride

Brief
=====

Branding Example For eZ Publish Legacy Default Administration. Replaces Default eZ5 Website Login Page and Layout Header Images with BC Logo Images as an example of how to do this to a ezpublish legacy admin installlation without changing existing design files directly.

Requirements
============

This extension is now compatible and tested with eZ Publish 5.x+ (Legacy) and PHP 5.4

Tested with eZ Publish Community Project 2018.06


Features
===========================

1. Added full copy of current default admin pagelayout.css into this separate design extension and not modified in any way. This provides for the following two features.
1.1 Style+Image Additions: Add BC eZ Logo to Admin Login Pagelayout
1.2 Add BC eZ Logo to Admin Pagelayout Header

2. Added full copy of current file, admin2/templates/page_copyright.tpl customized to contain much less offending branding in the footer of every admin page view.
2.1 Branding retained: Powered by eZ Publish legacy (bold, orange text color). For more information see ezinfo/about. (linked)

3. Added full copy of current file, settings/dashboard.ini.append customized to remove the community_activity setting entry from loading a related template with excessive branding which eventually broke and no one bothered to fix it since the source of the community activity was discontinued silently.
3.1 Branding removed: share.ez.no community activity dashboard module/view template which had been abadoned. This leaves the administrator users with less distractions and runtime boot errors overall.


Usage
===========================

The complete extension usage documentation is included in the file doc/USAGE.


CREDITS
=======

See doc/CREDITS.md


Troubleshooting
===============

1. Read the FAQ
   ------------

   Some problems are more common than others. The most common ones
   are listed in the the doc/FAQ.

2. Support
   -------

   If you have find any problems not handled by this document or the FAQ you
   can contact Brookins Consulting through the support system:
   http://brookinsconsulting.com/contact