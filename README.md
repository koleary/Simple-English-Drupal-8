# Simple-English-Drupal-8
A translation of the Drupal 8 user interface text into simple english.

##Rationale

Simple English for Drupal 8 has two goals:

1. To provide a simpler version of Drupal interface text that is more accessible to non-technical users, and users who do not speak English as a first language (like Simple English Wikipedia). 
2. To provide a test-bed for possible future global changes to Drupal interface test to make it more understandable to all users.

### To install simple english Drupal 8 interface translations:

1. Instal Drupal 8
2. Open the menu tab and select "extend"
3. Scroll to the bottom of the page and enable all of the Modules in the "Regional and language" group.
4. Save the page.
5. Go to the "configuration" tab
6. In the "Regional and languages" panel, click "Languages"
7. Click "Add language"
8. Click on "language name" and scroll all the way down the dropdown to "Custom language"
9. Under "language code" type "en-x-simple"
10. Under "Language name" type "Simple English"
6. Finish by clicking "Add custom language"

### To enable interface language detection and selection:

1. Go to configuration/langages
2. Enable "Customize Content language detection to differ from Interface text language detection settings"
3. in the "Interface text language detection" group click "selected language/settings" 
4. Set the default language to "Simple English" (Recommended since Simple English users will outnumber others and should therefore be a superset)
5. in the "Interface text language detection" group enable "Account administration pages". Now administrators who don't want Simple English can override Simple English by setting "English" in their own account pages. 
