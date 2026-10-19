# Open Source Licenses

**Last updated: October 2026**

Chevin is made possible by the incredible work of the open-source community and relies on the following third-party libraries. We gratefully acknowledge the developers and organizations behind these projects.

### 1. Android Open Source Project (AOSP) & Jetpack
The foundational architecture, UI components (Jetpack Compose), navigation, local database (Room), and background work management are provided by Google via the Android Open Source Project and AndroidX.
* **Libraries used:** `androidx.compose`, `androidx.room`, `androidx.lifecycle`, `androidx.datastore`, `androidx.core`, `androidx.activity`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

### 2. TensorFlow Lite
Used for local on-device machine learning inference (aesthetic scoring and feature extraction).
* **Libraries used:** `org.tensorflow:tensorflow-lite`, `tensorflow-lite-support`, `tensorflow-lite-gpu`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © Google LLC.

### 3. Google ML Kit (Face Detection)
Used locally to detect faces within photos, ensuring portraits are analyzed correctly without transmitting biometric data externally.
* **Libraries used:** `com.google.mlkit:face-detection`.
* **Terms of Service:** Governed by the [Google APIs Terms of Service](https://developers.google.com/terms) and [ML Kit Terms of Service](https://developers.google.com/ml-kit/terms).

### 4. OpenCV (Open Source Computer Vision Library)
Used for advanced image processing, matrix manipulation, Laplacian variance (blur detection), and feature matching (ORB).
* **Library used:** OpenCV SDK for Android.
* **License:** [Apache License 2.0](https://opencv.org/license/)

### 5. Dagger Hilt
Used for Dependency Injection.
* **Libraries used:** `com.google.dagger:hilt-android`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © The Dagger Authors.

### 6. Coil (Coroutine Image Loader)
Used for fast, lightweight asynchronous image loading and caching within Jetpack Compose.
* **Library used:** `io.coil-kt:coil-compose`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

### 7. Kotlin & Coroutines
The core programming language and concurrency framework.
* **Libraries used:** `org.jetbrains.kotlin`, `kotlinx-coroutines`.
* **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
* **Copyright:** © JetBrains s.r.o.

---

### Standard Apache 2.0 License Text
*Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.*
