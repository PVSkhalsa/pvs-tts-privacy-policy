# PVS TTS Privacy Policy

Effective date: 10 November 2026
App: PVS TTS (Android package com.pvs.tts)
Developer: PVS Khalsa

PVS TTS is an Android text-to-speech engine. It passes the text that other apps ask it to speak to the speech engines already installed on your phone. This page explains what the app does with information.

## Summary

- The developer does not collect, receive or store any data from the app.
- The app does not request the Android INTERNET permission.
- There are no accounts, no advertising, no analytics and no tracking code.
- Your settings are stored locally. Android automatic backup is disabled; device-maker transfer tools may behave differently.
- When a version installed from Google Play checks for updates, the Google Play Store app does that work (see "Update checks").

## What stays on your phone

PVS TTS saves your choices on your phone: the speaking mode, the language and voice chosen for each language, the list of speech engines found on your phone, and your settings for the call, battery and time announcements. It also keeps a short note about how the last request was routed, which holds counts and times and not the spoken text. The app opts out of Android's automatic backup (allowBackup is false in its manifest), so it does not ask Android to back this data up. Removing the app deletes this data. The Android setting "Clear storage" deletes it too. This page does not cover copies a phone maker's own transfer tool may make.

## Text you have spoken

When another app asks PVS TTS to speak, PVS TTS checks the writing system of the text and gives each part to the engine you chose for that language. This happens on your phone. PVS TTS does not store the text and does not send it to the developer.

The engines you choose are separate apps made by other companies. Some of them may send text to their own servers, especially for online voices. PVS TTS does not control or see that. Read the privacy policy of each engine you use.

## Permissions

The app declares exactly these permissions: POST_NOTIFICATIONS, FOREGROUND_SERVICE, FOREGROUND_SERVICE_SPECIAL_USE, READ_PHONE_STATE, SCHEDULE_EXACT_ALARM and RECEIVE_BOOT_COMPLETED. It does not declare INTERNET, WAKE_LOCK, QUERY_ALL_PACKAGES, call log, contacts, SMS, location, microphone or camera permissions.

- Notifications: shows a notice while speech or an announcement is running. You can refuse it.
- Phone state: used only if you turn on the incoming call announcement, to know that a call is ringing. The app says "Incoming call". It does not read the caller's number, your contacts or your call history.
- Exact alarms: used only if you turn on the time announcer and allow it, so announcements can run at clock times.
- Run at start-up: starts your turned-on announcements again after the phone restarts.
- Foreground service: keeps speech and announcements running while the app is closed.

All announcements are off until you turn them on.

## Other apps on your phone

To find your speech engines, PVS TTS asks Android which installed apps provide a text-to-speech service. It keeps the names and supported languages of those engines on your phone to show them in its lists. It does not read your other apps. The Settings screen has shortcuts that open Android's own battery and accessibility pages. They only open those pages and give the app no access to them.

## Update checks

A version of PVS TTS installed from Google Play asks Google Play whether a newer version is published, using Google's Play In-App Updates library. The Google Play Store app performs the check on your phone. According to Google's documentation, this processing uses device metadata, the app version, and a list of installed modules and asset packs to decide whether an update is available, and Google states that it is encrypted, not shared with third parties and deleted after a fixed retention period (source: https://developer.android.com/guide/playcore/in-app-updates, last updated 2026-01-30). The developer does not receive this information. Versions not installed from Google Play do not get update prompts.

## Children

The app does not knowingly collect personal information from anyone, including children.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date.

## Contact

For privacy questions, contact PVS Khalsa at paramveersinghkhalsa2003@gmail.com.
