# Go-Lang Moodules
- Sebelum ada GoModules, untuk menggunakan library atau dependecy external, harus copy dependecy project lain ke project saat ini.
- GoModules digunakan untuk melakukan manajemen dependency atau library di GoLang.
- GoModules mulai ada sejak GoLang versi 1.11 dan 1.12.

## Membuat Module Baru (atau project baru)
- Menggunakan perintah `go mod init nama-module`. Nama module biasanya disamakan dengan nama folder.
- Akan berisi informasi nama module dan versi GoLang yg digunakan.

## Rilis Module
- Membuat project dengan nama module sesuai repo github, contoh `go mod init github.com/dirasanjayawardana/golang_dasar_contoh_module`
- Untuk merilis module, hanya perlu membuat Tag Git dengan `git tag v1.0.0` (contoh untuk merilis module versi 1.0.0)
- Kemudian push module ke github, contoh `git push origin v1.0.0`