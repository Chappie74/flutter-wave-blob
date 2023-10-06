## Features

### Blob Wave Animation
This package provide a blob wave animation that can be customized to your needs. You can playing audio using **amplitude** of voice.

# Preview
<img src="example-1.gif" width=300 />

## Getting started

### Installing
1. Add dependencies to `pubspec.yaml`

```dependencies
dependencies:
    wave_blob: <latest-version>
```
2. Run pub get.
```
flutter pub get
```
3. Import package
```dart
import 'package:wave_blob/wave_blob.dart';
```

## Usage

#### Simple usage

1. Wrap Widget with **WaveBlob** and assign needed parameter.
'''dart
WaveBlob(
   height: MediaQuery.sizeOf(context).width * 0.8,
   width: MediaQuery.sizeOf(context).width * 0.8,
   centerCircle: true,
   child: const Icon(
       Icons.mic,
       color: Colors.white,
       size: 80.0,
   ),
)
'''

# Author
- **Hosein Nadalizadeh**
- [Telegram/BlobDrawable](https://github.com/DrKLO/Telegram/blob/master/TMessagesProj/src/main/java/org/telegram/ui/Components/BlobDrawable.java)

