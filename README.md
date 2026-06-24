# HungNT 3rd-party: vHierarchy

Asset gốc: [vHierarchy (kubacho lab)](https://assetstore.unity.com/packages/tools/utilities/vhierarchy-249759)

## Cài đặt

Thêm vào `Packages/manifest.json`:

```json
"com.hungnt.thirdparty.vhierarchy": "https://github.com/HungNT-UPM/com.hungnt.thirdparty.vhierarchy.git"
```

Hoặc Package Manager → **Add package from git URL...**:

```
https://github.com/HungNT-UPM/com.hungnt.thirdparty.vhierarchy.git
```

## Note

- Giữ nguyên namespace gốc `VHierarchy` (và `VHierarchy.Libs`) — drop-in, dùng như asset gốc.
- Editor-only tool: sắp xếp/làm gọn cửa sổ Hierarchy. Sau khi cài, dùng menu **Tools → vHierarchy** để cấu hình; config lưu trong `vHierarchy Data.asset`.
- Đây là **vHierarchy 1**. Asset có sẵn `VHierarchy.asmdef` (Editor) — không cần thêm asmdef.
