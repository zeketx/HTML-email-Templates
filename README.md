# HTML email templates

Here are a few email templates that are responsive and simple. I attempted to create these templates only using a few media queries.

So far these templates have been tested with multiple clients and have good support.

## Contents

`template1.1.html` - Good for simple layouts such as confirmations and single column emails.

`template1.2.html` - Simplistic design for providing information (blog, alerts, news) in single column emails.

`template1.3.html` - Simplistic design for ecommerce campaings.

### Template1.1

[HTML source](https://github.com/zeketx/HTML-email-Templates/blob/master/template1.1.html) [CodeSandBox]()

### Template1.2

[HTML source](https://github.com/zeketx/HTML-email-Templates/blob/master/template1.2.html) [CodeSandBox]()

### Template1.3

[HTML source](https://github.com/zeketx/HTML-email-Templates/blob/master/template1.3.html) [CodeSandBox]()

### Code Formatting

Well commented and readable code.

```HTML
/* --       Client Specific Styles     -- */

.ReadMsgBody{width:100%;} .ExternalClass{width:100%;} /* Force Hotmail/Outlook.com to display emails at full width. */

.ExternalClass, .ExternalClass p, .ExternalClass span, .ExternalClass font, .ExternalClass td, .ExternalClass div{line-height:100%;} /* Force Hotmail/Outlook.com to display line heights normally. */

table, td{mso-table-lspace:0pt; mso-table-rspace:0pt;} /* Remove spacing between tables in Outlook 2007 and up. */

#outlook a{padding:0;} /* Force Outlook 2007++ to provide a "view in browser" message. */

img{-ms-interpolation-mode: bicubic;} /* Force IE to smoothly render resized images. */

body, table, td, p, a, li, blockquote{-ms-text-size-adjust:100%; -webkit-text-size-adjust:100%;} /* Prevent Windows- and Webkit-based mobile platforms from changing declared text sizes. */



/* --       General Styles      -- */

#welcome_title, #emailContainer,  #confirmation_btn, #welcomeMessage, #footer{font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif}

#emailContainer{line-height:60px}

#_confirmation{line-height:40px

```