# TruePath

 TruePath is a web extension that dynamically generates relative XPath on right click on a web page and display all the XPath as menu items

 # For Chrome & Firefox version < 56 : It then group the XPath as follows
  
  1. XPath with id, href, src: This group will list all XPath which has id, href, src or any http\ https as attribute. 
  2. XPath with class, name, title: This group will list all XPath except those containing id, href, src or any http\ https.
  3. XPath with index: As name suggest this group will contain all indexed XPath.
  
  # For Firefox version > 55: It then group the XPath as follows
  
  1. Green thumbs up: This group will list all XPath except those containing id, href, src or any http\ https.
  2. Yellow thumbs up: This group will list all XPath which has id, href, src or any http\ https as attribute.
  3. Red thumbs up: This group will contain all indexed XPath.

# The benefits of using this tool are:

•XPath are created dynamically and easy to use in automation code, so no need to create XPath manually

•No additional permission is needed to install this tool as it is a Firefox extension and can be install easily

•Support for the page object format i.e., @FindBy which can easily be copied and use in STAF framework

•Supports Firefox 52+, Firefox Quantum both 32 & 64 versions

If you think you found a bug please create a new issue here: https://github.com/gsumit1/TruePath/issues
