Installing ODK-X Basic Tools
================================

.. _basic-prereqs:

Prerequisites
-------------------

Before installing any of the ODK-X tools, you will need the following third party app:

  - `OI File Manager <https://github.com/openintents/filemanager/releases>`_

Required
~~~~~~~~~~~~~~~

There are no other ODK-X Android tools that are prerequisites to installing ODK-X Services. However, this tool is a prerequisite for all the other ODK-X Android tools.

Recommended
~~~~~~~~~~~~~~~

We also recommend installing both ODK-X Survey and ODK-X Tables. Having both is not required, but Tables and Survey are most versatile when used together. Tables offers a way to visualize, process, and modify data collected by Survey, all on the device.  Survey offers a simple, form based data collected workflow similar to ODK Collect that can be seamlessly integrated with Tables to create and modify records.

.. _services-install:


Installing Services
--------------------------------

  1. From your device's :guilabel:`Settings`, choose :menuselection:`Security`.

    - Make sure *Unknown Sources* is checked.
    - (On older versions of Android, this setting is in :menuselection:`Applications` rather than :menuselection:`Security`)

  2. Open a web browser on your phone.
  3. Navigate to https://github.com/odk-x/services/releases/latest and download the latest ODK-X Services APK.
  4. In the download window, you will see ODK_Services_vN.N.N.apk. - Select it to download the file.

   - On older devices, the APK will automatically install after you approve the security settings.
   - On newer devices, you must go to the download list, rename the file to restore the .apk extension (the extension will have been renamed to .man during the download process), then click on it to install it.

.. note::

  You can also `download the ODK-X Services APK <https://github.com/odk-x/services/releases/latest/>`_ to your computer and load it on your device via `adb <https://developer.android.com/studio/command-line/adb.html>`_ or another tool like `AirDroid <https://www.howtogeek.com/105813/control-your-android-from-a-browser-with-airdroid/>`_.

.. tip::

  You can also `install ODK-X Services on an Android emulator <https://github.com/odk-x/odk-x/wiki/DevEnv-Setup>`_. However, this can be slow and is only recommended for developers actively working on Services.

.. _survey-install:

Installing the ODK-X Survey App
-----------------------------------

  1. From your device's :guilabel:`Settings`, choose :menuselection:`Security`.

    - Make sure *Unknown Sources* is checked.
    - (On older versions of Android, this setting is in :menuselection:`Applications` rather than :menuselection:`Security`)

  2. Open a web browser on your phone.
  3. Navigate to https://github.com/odk-x/survey/releases/latest and download the latest ODK-X Survey APK.
  4. In the download window, you will see ODK_Survey.N.N.apk. - Select it to download the file.

   - On older devices, the APK will automatically install after you approve the security settings.
   - On newer devices, you must go to the download list, rename the file to restore the .apk extension (the extension will have been renamed to .man during the download process), then click on it to install it.

.. note::

  You can also `download the ODK-X Survey APK <https://github.com/odk-x/survey/releases/latest>`_ to your computer and load it on your device via `adb <https://developer.android.com/studio/command-line/adb.html>`_ or another tool like `AirDroid <https://www.howtogeek.com/105813/control-your-android-from-a-browser-with-airdroid/>`_.

.. tip::

  You can also `install ODK-X Survey on an Android emulator <https://github.com/odk-x/odk-x/wiki/DevEnv-Setup>`_. However, this can be slow and is only recommended for developers actively working on Survey.


.. _tables-install:

Installing the ODK-X Tables App
-----------------------------------


  1. From your device's :guilabel:`Settings`, choose :menuselection:`Security`.

    - Make sure *Unknown Sources* is checked.
    - (On older versions of Android, this setting is in :menuselection:`Applications` rather than :menuselection:`Security`)

  2. Open a web browser on your phone.
  3. Navigate to https://github.com/odk-x/tables/releases/latest and download the latest ODK-X Tables APK.
  4. In the download window, you will see ODK_Tables.N.N.apk. - Select it to download the file.

   - On older devices, the APK will automatically install after you approve the security settings.
   - On newer devices, you must go to the download list, rename the file to restore the .apk extension (the extension will have been renamed to .man during the download process), then click on it to install it.

.. note::

  You can also `download the ODK-X Tables APK <https://opendatakit-dev.cs.washington.edu/2_0_tools/download/>`_ to your computer and load it on your device via `adb <https://developer.android.com/studio/command-line/adb.html>`_ or another tool like `AirDroid <https://www.howtogeek.com/105813/control-your-android-from-a-browser-with-airdroid/>`_.

.. tip::

  You can also `install ODK-X Tables on an Android emulator <https://github.com/odk-x/odk-x/wiki/DevEnv-Setup>`_. However, this can be slow and is only recommended for developers actively working on Tables.
