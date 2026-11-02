# Threads Desktop (Tauri 2 + WebView2)

Cara membangun installer:
1. Push folder ini ke repo GitHub (branch `main`).
2. Buka tab Actions, jalankan "Build Threads-Setup.exe" (atau tunggu otomatis setelah push).
3. Unduh artifact `Threads-Setup`, lalu double-click `Threads-Setup.exe`.

Build lokal di Windows: pasang Rust dan `cargo install tauri-cli --version "^2" --locked`,
lalu di folder `src-tauri` jalankan `cargo tauri icon app-icon.png` dan `cargo tauri build --bundles nsis`.
