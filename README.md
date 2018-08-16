# PrefSyncService
Xamarin C# implementation of https://github.com/StringMon/prefsyncservice.

Instructions
------------

1) Create an instance of PrefListener in OnCreate()

2) Resume Listener in OnResume() and pause in OnPause()

3) If necessary, subscribe to preference changes with ISharedPreferencesOnSharedPreferenceChangeListener


That's it!
