# Local Manifest for MistOs

Konfigurasi `local_manifest` untuk build ROM pada branch **mist**.

## Step 1: Clone Manifest
Klik tombol copy di bawah ini untuk clone manifest:

```bash
git clone https://github.com/Mendokoe/local_manifest.git -b mist .repo/local_manifests
```

## Step 2: Sync Source
Setelah clone selesai, jalankan perintah ini untuk sinkronisasi:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

---
**Maintainer:** [Mendokoe](https://github.com/Mendokoe)
