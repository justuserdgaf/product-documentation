---
title: integrate-cdn-resource-with-craft
displayName: Craft
published: true
order: 50
toc:
---
# Integrate CDN resource with Craft

Before you take any steps please back up your files and database. The plugin works only with default CMS pattern. If you manually changed CMS patterns, the plugin might not help you.

Login to your Craft admin panel.

<img src="https://support.gcore.com/hc/ru/article_attachments/115000083605/1.JPG" alt="" width="50%">

Go to "Assets" by clicking on the arrow next to the gear in the top right corner of the control panel.

<img src="https://support.gcore.com/hc/ru/article_attachments/115000083625/22.JPG" alt="" width="70%">

Click **+New Source** to create a new folder for your static files.

<img src="https://support.gcore.com/hc/ru/article_attachments/115000083645/3.JPG" alt="" width="70%">

In the URL field type in the CNAME that you specified in the Gcore <a href="https://accounts.gcore.com/reports/dashboard" target="_blank">Control panel</a>. Ensure that your <a href="https://gcore.com/docs/cdn/cdn-resource-options/general/create-and-set-a-custom-domain-for-the-content-delivery-via-cdn" target="_blank">CNAME record has been configured</a> in a proper way before using it for integration (e.g., ```http://cdn.site.com/path/to/your/assets```).

<img src="https://support.gcore.com/hc/ru/article_attachments/115000083805/4.JPG" alt="" width="70%">

Go to the "Assets" tab, find previously created asset source and download your files.  

<img src="https://support.gcore.com/hc/ru/article_attachments/115000081769/5.JPG" alt="" width="70%">

Now you can use your asset at the website.

If you have already had created assets, edit them replacing URL with CNAME that you specified in the Gcore <a href="https://accounts.gcore.com/reports/dashboard" target="_blank">Control panel</a>.  

<img src="https://support.gcore.com/hc/ru/article_attachments/115000081889/6.JPG" alt="" width="70%">

Save changes.

Integration has been completed! We highly recommend you to check the HTML code of your web page to ensure that URLs have been rewritten properly from your original ones to CNAME from the control panel.

To do that press **F12** or open Developers Tools in your browser, choose the Network tab and refresh the page. All static files should have your CNAME in URLs.