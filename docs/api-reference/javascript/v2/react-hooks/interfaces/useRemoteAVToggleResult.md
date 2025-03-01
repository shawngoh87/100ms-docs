---
title: useRemoteAVToggleResult
nav: "5.2.11"
---

## Properties

### isAudioEnabled

• **isAudioEnabled**: `boolean`

true if unmuted and vice versa

___

### isVideoEnabled

• **isVideoEnabled**: `boolean`

___

### setVolume

• `Optional` **setVolume**: (`volume`: `number`) => `void`

#### Type declaration

▸ (`volume`): `void`

use this function to set the volume of peer's audio track for the local user, the function will
only be present if the remote peer has an audio track to change volume for

##### Parameters

| Name | Type |
| :------ | :------ |
| `volume` | `number` |

##### Returns

`void`

___

### toggleAudio

• `Optional` **toggleAudio**: () => `void`

#### Type declaration

▸ (): `void`

use this function to toggle audio state, the function will only be present if the user
has permission to mute/unmute remote audio

##### Returns

`void`

___

### toggleVideo

• `Optional` **toggleVideo**: () => `void`

#### Type declaration

▸ (): `void`

use this function to toggle video state, the function will only be present if the user
has permission to mute/unmute remote video

##### Returns

`void`

___

### volume

• `Optional` **volume**: `number`

current volume of the audio track
