# Open Source Licenses

**Last updated: October 25, 2026**

Chevin is made possible by the work of the open-source community and relies on the following third-party software and assets. We gratefully acknowledge the developers and organizations behind these projects.

### 1. Android Jetpack (AndroidX)
UI (Jetpack Compose, Material 3, Material Icons), navigation, lifecycle and ViewModel, local database (Room), preferences storage (DataStore), image metadata (ExifInterface) and core Android utilities.
* **Libraries used:** `androidx.compose` (ui, material3, material-icons), `androidx.activity`, `androidx.core`, `androidx.lifecycle`, `androidx.navigation`, `androidx.hilt:hilt-navigation-compose`, `androidx.room`, `androidx.datastore`, `androidx.exifinterface`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © The Android Open Source Project.

### 2. TensorFlow Lite
On-device machine learning inference (aesthetic scoring and feature extraction).
* **Libraries used:** `org.tensorflow:tensorflow-lite`, `tensorflow-lite-support`, `tensorflow-lite-gpu`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © The TensorFlow Authors.

### 3. Google ML Kit (Face Detection)
On-device face detection, so that portraits are analyzed correctly. Photos are never sent to Google; see the [Privacy Policy](privacy.html) for the technical diagnostic data ML Kit sends.
* **Libraries used:** `com.google.mlkit:face-detection`.
* **Terms:** [ML Kit Terms of Service](https://developers.google.com/ml-kit/terms) and [Google APIs Terms of Service](https://developers.google.com/terms).

### 4. OpenCV (Open Source Computer Vision Library)
Image processing: blur detection (Laplacian variance), exposure analysis and feature matching (ORB) for duplicate detection.
* **Library used:** OpenCV SDK for Android.
* **License:** [Apache License 2.0](https://opencv.org/license/)
* **Copyright:** © OpenCV team and contributors.

### 5. Dagger Hilt
Dependency injection.
* **Libraries used:** `com.google.dagger:hilt-android`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © The Dagger Authors.

### 6. Coil
Asynchronous image loading in Jetpack Compose.
* **Library used:** `io.coil-kt:coil-compose`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © Coil Contributors.

### 7. Kotlin and Kotlin Coroutines
Programming language and concurrency framework.
* **Libraries used:** Kotlin standard library, `kotlinx-coroutines` (including `kotlinx-coroutines-play-services`).
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © JetBrains s.r.o. and Kotlin Programming Language contributors.

### 8. NIMA aesthetic model
The aesthetic score is computed by a NIMA (Neural Image Assessment) model based on MobileNet, converted to TensorFlow Lite.
* **Source:** [idealo/image-quality-assessment](https://github.com/idealo/image-quality-assessment), pretrained aesthetic weights `weights_mobilenet_aesthetic_0.07.hdf5`, converted by us to TensorFlow Lite.
* **License:** [Apache License 2.0](https://github.com/idealo/image-quality-assessment/blob/master/LICENSE)
* **Copyright:** © idealo image-quality-assessment authors. Based on "NIMA: Neural Image Assessment" (Talebi & Milanfar, 2018) and the MobileNet architecture.

### 9. Plus Jakarta Sans (font)
The typeface used throughout the app.
* **License:** [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/)
* **Copyright:** © 2020 The Plus Jakarta Sans Project Authors ([github.com/tokotype/PlusJakartaSans](https://github.com/tokotype/PlusJakartaSans)).

### 10. Sound effects
Tap, pop and end-of-analysis sounds.
* **"Bubble Pop 06"** by Universfield, from [Pixabay](https://pixabay.com/sound-effects/search/univer%20buble%20pop/).
* **"UI Chime Success"** by Sound Shelf Studio, from [Pixabay](https://pixabay.com/sound-effects/search/sound%20shelf%20studio%20ui%20success/).
* **"Soft App Button Tap Sound 3"** by vadim_makes_sound, from [Pixabay](https://pixabay.com/sound-effects/search/vadim_makes_sound-soft-app-button-tap-sound-/).
* **License:** [Pixabay Content License](https://pixabay.com/service/license-summary/) (free to use in apps, no attribution required; credited here as thanks).

---

### Apache License 2.0
Libraries under the Apache License 2.0 are distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. The full text of the license is available at [apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0).
