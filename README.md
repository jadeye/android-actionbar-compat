android-actionbar-compat
========================

This compatibility library makes the ActionBar API available to Froyo+ devices. It provides the same functionality as the AOSP ActionBarCompat and TabCompat sample projects.

In addition, you can define the state of the home icon as a navigation item programmatically. You can use ActionBar tabs and the new support NavigationDrawer.


Usage
-----

Let your activity extend one of the base activities,

- ActionBarActivity,
- ActionBarFragmentActivity (supports fragments),
- ActionBarTabActivity (supports fragments and tabs),
- ActionBarPreferenceActivity (extends PreferenceActivity),
- ActionBarAuthenticatorActivity (extends AuthenticatorActivity).

Your activity must implement ActionBarConfigurator by providing a boolean method that returns the desired behaviour of the home icon.
