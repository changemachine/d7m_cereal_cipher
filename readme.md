# CEREAL CIPHER! #

The Cereal Cipher module allows you to encode text using the shift-cipher (AKA Caesar cipher) method of encryption.  This is very low-level encryption, and is about as secure as pig-latin.

## Installation ##
(Requires [Drupal](https://www.drupal.org/) running in MAMP/LAMP/XAMP)

1. Clone the cereal_cipher folder into the appropriate modules folder of your site (ie, /sites/all/modules/gathercontent/).
2. Enable the module in Drupal's Modules menu


## Support ##
This module is unsupported, and may break everything it touches, or fall apart in soft breezes. [james@changemachine.org](mailto:james@changemachine.org).




3 INPUTS.
-  shift value (cycles back to a after z & vice-versa)
-  Shift-direction (r = +, l = -)
-  phrase: a-z, A-Z, 0-9, spaces and punctuation.


Then redirect to results page (encoded phrase).



- Be sure to validate all input before calculating the result. Here are the validation rules:

Any spaces or punctuation in the input phrase should be ignored and reproduced in the final result without being shifted.

Final result should be in all lowercase.

Create a site, add this as a git submodule, enable it and submit the base repository link. Don't forget to commit the DB.

DB name: james_cipher.
User/PW: epicodus.
