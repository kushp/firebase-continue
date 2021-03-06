# Firebase Continue Samples - "Continote" Android App

This directory contains a sample Android app titled "Continote" which uses the
Firebase Continue for Android library.

Users can begin writing a note in this app and then continue writing in Chrome
from exactly where they are using the
[sample Chrome extension](../chrome-extension) and [sample web app](../web).

**Important Notice**: This is currently a work-in-progress.
Expect frequent updates as an initial, complete v0.1.0 is fleshed out.
See [Development Progress](#development-progress) for details.
This notice will be removed when v0.1.0 is officially ready and released
in the Releases page of this repo.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Compatibility](#compatibility)
5. [Dependencies](#dependencies)
6. [Disclaimer](#disclaimer)
7. [Development Progress](#development-progress)

## Prerequisites

Before proceeding to the [Setup section](#setup) below, you must
first follow the [main `samples` README](../) so that you have a properly
configured Firebase project for this and any other "Continote" samples
you run.

## Setup

After completing the following steps, you will have a properly configured instance of
this sample to build and install to try out:

1.  First, make sure you followed the [Prerequisites section](#prerequisites) above.

2.  **TODO**

**TODO**: Finish listing setup instructions here, including how to connect the app to
the developer's Firebase project.

## Usage

After this sample is properly set up and installed on your Android device or
simulator, open it.

From there, you will be asked to sign in to be able to add notes, delete notes, or
open to edit a note.

When editing a note, you will also have the option of "continuing" to write/edit the
note elsewhere (i.e. within Chrome). To make use of this, be sure to also install the
[sample Chrome extension](../chrome-extension).

## Compatibility

This sample app is compatible with the
[same versions of Android as the Firebase Continue library itself](../../android/#compatibility).

## Dependencies

This sample is dependent on the following libraries/SDKs:

### Firebase
- **TODO**

### Firebase Continue
- [Firebase Continue for Android v0.1.0+](../../android)

### FirebaseUI
- **TODO**

### Material Components
- **TODO**

## Disclaimer

The focus of this sample is to demonstrate Firebase Continue usage in a
somewhat realistic scenario. This sample can also act as a simple model of how
to use Firebase and FirebaseUI in an Android app.

The focus is *not*, however, to have a perfect user interface or user
experience. Please keep that in mind when trying out this sample.

## Development Progress

This section will be removed when each of the items below are complete for an
initial, released v0.1.0 of this sample.

### Major Features Completed
- [ ] User authentication (via Firebase Authentication and FirebaseUI)
- [ ] "My Notes" screen, allowing signed in users to view a list of their notes with
the option to add a note, delete a note, or open to edit a note
- [ ] "Edit Note" screen, allowing signed in users to edit a particular note with the
option to "Continue Writing Elsewhere" (made possible by Firebase Continue)
