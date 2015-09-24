# MagentoBrowserNotice
Magento extension that informs users with outdated browsers
  
Instructions for installing this extension in 10 easy do-it-yourself steps.
1. Clone this repo (DUH!)  
2. Copy it’s contents to the root of your Magento installation. You can use FTP to do that. It’s the directory containing index.php [App] [Skin] [Media] among others  
3. Log in to your Magento backend  
4. Go to System -> Cache Management, select all options, and in the action dropdown select “Refresh”. Then click Submit.  
5. Log out/in to your backend  
6. Go to System -> Configuration -> Web and drop down the “Browser update notice” selection  
7. You can set you options here. If you set auto update, browser-udate.org will decide which browsers need to update. I recommend you to set this to No. This will give you the options to specify which browsers version you support. You can set “Always show this notice” to yes if you want to customize the notice appearance and set it back once you’re done.  
8. Set “Enable notice” to “Yes”  
9. Click save config.  
10. All done!  
  
More info: http://www.rapidcommerce.eu/en/blog/2012/10/magento-browser-update-notice/
Questions: https://www.facebook.com/RapidCommerce
