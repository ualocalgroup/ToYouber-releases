# Third-party components

- youtubedl-android 0.18.1, GPL-3.0: https://github.com/yausername/youtubedl-android/tree/0.18.1
  Maven: io.github.junkfood02.youtubedl-android:library, common, ffmpeg.
  Includes Android-compatible Python, QuickJS and ffmpeg binaries and dependency archives. See upstream's corresponding build scripts and license notices before distributing modified binaries.
- yt-dlp zipapp, bundled from this project's vendor/bin/yt-dlp: https://github.com/yt-dlp/yt-dlp . License notices are embedded inside the zipapp.
- Python: https://docs.python.org/3/license.html
- FFmpeg: https://ffmpeg.org/legal.html ; build configuration determines LGPL/GPL coverage.
- AndroidX: Apache-2.0, https://android.googlesource.com/platform/frameworks/support/
- Kotlin: Apache-2.0, https://github.com/JetBrains/kotlin
- Apache Commons IO: Apache-2.0; Jackson: Apache-2.0.
- Gradle wrapper: Apache-2.0, https://github.com/gradle/gradle
- Roboto Flex: SIL Open Font License, https://github.com/google/fonts . Material Symbols / material-design-icons: Apache-2.0, https://github.com/google/material-design-icons . Font files and license texts are bundled locally under web/fonts (Android) and site/fonts (Netlify).
- Platform marks: Simple Icons, CC0, https://simpleicons.org . Supplied ToYouber images remain user-provided assets.

The source archive contains the application's build scripts, Java/Python code, frontend and exact Maven dependency versions. This personal test build is not an app-store release; review upstream license/source-distribution requirements before public redistribution.

- Deno (web Docker runtime): MIT, https://github.com/denoland/deno .


# Залежності Windows-збірки

- Python 3.13.13 Windows embeddable x64 — PSF; https://www.python.org/ftp/python/3.13.13/python-3.13.13-embeddable-amd64.zip. Ліцензія включена в `python/LICENSE.txt`.
- yt-dlp — Unlicense; zipapp із поточного `vendor/bin/yt-dlp`, https://github.com/yt-dlp/yt-dlp. Самооновлення використовує офіційні релізи.
- FFmpeg / FFprobe win64 GPL — збірка yt-dlp/FFmpeg-Builds, https://github.com/yt-dlp/FFmpeg-Builds/releases/tag/latest, з upstream https://github.com/BtbN/FFmpeg-Builds. Джерело й рецепти збірки: ці репозиторії та https://ffmpeg.org/download.html. Комплект містить `licenses/FFmpeg-LICENSE.txt` і документацію збірки. Фактичний архів зафіксовано SHA256.
- Deno 2.5.4 — MIT; https://github.com/denoland/deno/releases/tag/v2.5.4.
- .NET 8 — MIT та сторонні компоненти; https://github.com/dotnet/runtime. Self-contained publish включає `LICENSE.txt`, `ThirdPartyNotices.txt`.
- Microsoft.Web.WebView2 1.0.3537.50 — умови Microsoft; https://www.nuget.org/packages/Microsoft.Web.WebView2/1.0.3537.50. Runtime bootstrapper: https://go.microsoft.com/fwlink/p/?LinkId=2124703. Умови: https://developer.microsoft.com/microsoft-edge/webview2/.
- NSIS 3.13 — zlib/libpng та ліцензії компонентів; https://nsis.sourceforge.io/.
- Roboto Flex — OFL, Material Symbols — Apache 2.0. Файли ліцензій у `engine/web/fonts`.
- Логотип і головна ілюстрація — надані користувачем матеріали проєкту.
