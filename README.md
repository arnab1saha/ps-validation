# What is this?

This a js validation libray to validate input field data written in ECMA Script (ES6).

# Installation

`npm i ps-validation --save`

# Just import it and its ready to use

import 'ps-validation'

# Currently available classes

* Allow alpha character set only into the input field * 

ps-alpha
ps-alpha-u
ps-alpha-l

* Allow alpha character set and space only into the input field *

ps-alphaspace
ps-alphaspace-u
ps-alphaspace-l


* Allow alpha numecric character set only into the input field *

ps-alphanumeric
ps-alphanumeric-u
ps-alphanumeric-l

* Allow alpha numecric character set and space only into the input field *

ps-alphanumericspace
ps-alphanumericspace-u
ps-alphanumericspace-l

* Allow email character set Allowed Carecterset (alphanumeric and @._) only into the input field *

ps-email
ps-email-u
ps-email-l

* Allow specific character set generally used for addressAllowed Carecterset (alphanumeric space and &. ,()-/) into the input field *
ps-address
ps-address-u
ps-address-l

ps-integer

# Use postfix -u to convert input to upper case . And  use postfix -l to convert input to lower case .