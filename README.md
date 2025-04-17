# Esign
E-sign Module Ported to Backdrop CMS

CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ
 * Maintainers

INTRODUCTION
------------

This module allows for integration of Signature Pad, an electronic-signing
script, into Backdrop for both nodes (content) and the Field API (FAPI).

REQUIREMENTS
------------

This module requires the following module:

 * Libraries (https://backdropcms.org/project/libraries) 
 * Field API (core)

It also requires the following third-party library:

 * Signature Pad 1.6+ (https://github.com/szimek/signature_pad)


INSTALLATION
------------

 * Install as you would normally install a contributed Backdrop module.

 * Download and extract the Signature Pad library into the libraries directory
   (usually "libraries").

CONFIGURATION
-------------

 * For content, you can change the options within the field settings.
   - For FAPI, you can change the field options by setting the '#esign_options'
     parameter, and using the following keys in an associative array:

   - dotSize (default: 1)

   - minWidth (default: 0.5)

   - maxWidth (default: 2.5)

   - backgroundColor (default: 'rgba(0,0,0,0)')

   - penColor (default: 'rgba(0,0,0,1)')

   - velocityFilterWeight (default: 0.7)

-----------------------------------------------------------------------------
CREDIT
-----------------------------------------------------------------------------
Ported to Backdrop CMS by - [Adeel Ahmed](https://github.com/adeel4zia)

Github:   [Adeel4zia](https://github.com/adeel4zia)

Twitter|X: [Adeel Ahmed](https://x.com/adeel4zia)

Linkedin:  [Adeel Ahmed](https://www.linkedin.com/in/adeel4zia)

Original:  [Drupal 7 module](https://www.drupal.org/project/esign)
 
For professional support and development services contact adeel4zia@gmail.com.


