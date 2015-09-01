#CORS-pdf - continued

A continuation on the findings here: https://github.com/dxa4481/CORS-pdf
the vulnerability is demonstrated by keylogging cross origin PDFs in Chromium using simple javascript keypress events.

Input into PDF objects should be protected from javascript keypress events to mitigate this.


Check out the demo:

Here https://dustindecker.me/static/CORS-pdf-keylogging/

or here
http://sevoma.github.io/CORS-keylogging-a-pdf/

Tested on Chromium Version 44.0.2403.89