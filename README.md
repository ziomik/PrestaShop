Copyright (C) 2012 by Kris

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
	Bitcoin payment via BIPS for PrestaShop.

Version 0.1
	
System Requirements:
	BIPS API key
	PrestaShop
	Curl PHP Extension
	JSON Encode
  
Configuration Instructions:
	1. Upload files to your PrestaShop installation.
	2. Go to your PrestaShop administration. Modules -> Payments & Gateways -> "BIPS" click [Install]
	3. Go to your PrestaShop administration. Modules -> Payments & Gateways -> "BIPS" click [Configure]
	4. In BIPS Merchant IPN Callback URL, enter the provided link from configure section of BIPS PrestaShop Payment Module. http://YOUR_PRESTASHOP_URL/modules/BIPS/ipn.php
	5. Enter a strong IPN secret just below.
	6. In module settings "API key" <- set your BIPS API key.
	7. In module settings "IPN secret" <- set your BIPS IPN secret.