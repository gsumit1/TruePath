# TruePath

TruePath generates relative XPath on right click on web page. 

Once the web page is loaded, when a user right clicks on any web element on the web
page, it will dynamically create all the relative XPath associated with that
web element by scanning through its attributes and display all the XPath as
menu items. It then groups the XPath as Unique XPath or Non Unique XPath. Non Unique
XPath means multiple nodes are present in DOM for this XPath. Using index to
one can select the required node. Support for frames is not available now. 

The benefits of using this tool are:
•	 XPath are created dynamically and easy to use in automation code, so no need to create XPath manually.
•	 No additional permission is needed to install this tool as it is a Firefox extension and can be install easily.
•	 Support for the page object format i.e., @FindBy which can easily be copied and use in STAF framework.
•	Supports Firefox 52+, Firefox Quantum both 32 & 64 versions.

If you think you found a bug please create a new issue here: https://github.com/gsumit1/TruePath/issues
