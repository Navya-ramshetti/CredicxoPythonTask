# Bypass captcha 
how to bypass captchas such as reCaptcha and hCaptcha programmatically using Python or JavaScript. This is demonstrated on Discord, using their registration process. It can be applied to any website using captchas, since they all make use of the site-key that you send over to 2captcha. You can create a Discord account generator / creator using this method.

import bypass 

from hcapbypass import bypass
import sys

captcha_solved = bypass(sys.argv[1], 'google.com', True)
print(captcha_solved)

