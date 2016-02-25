Foundation 6 theme for ExpressionEngine Wiki

##To load the theme:
-Copy the contents of <code>/foundation/</code> directory to <code>/themes/wiki_themes/foundation</code>.
-Navigate to <code>/system/user/templates/default_site/site.group/index.php</code> and declare <code>theme="foundation"</code> in your <code>exp:wiki</code> tag. 
-You can copy and paste the following line if needed. Just change <code>wiki="YOUR_TITLE"</code> to the title of your wiki page.
{exp:wiki base_path='wiki/index' wiki="YOUR TITLE" theme="foundation"}

Note: The page wrapper for the Wiki theme is wiki_page.html. Some of the links in the main nav from the original Wiki template have been removed for personal use, but they can be replaced by copy &amp; pasting from the original template.
