# 📚 Hướng Dẫn Nhanh Cho Sinh Viên

## 🚀 Bước 1: Setup Dự Án

```bash
# Clone repository
git clone https://github.com/letienhieu-lecturer/buoi11-mystudentlife.git
cd mystudentlife

# Mở với Android Studio
# File > Open > Chọn thư mục mystudentlife
```

## 📖 Bước 2: Đọc Tài Liệu

Trước khi bắt đầu code, vui lòng đọc:

1. **README.md** - Tổng quan dự án, cấu trúc, lộ trình
2. **CURRICULUM.md** - Chi tiết mỗi buổi học (30 buổi)
3. **TROUBLESHOOTING.md** - Giải quyết lỗi thường gặp

## 📅 Bước 3: Bắt Đầu Code

### Tuần 1 (Buổi 1-5)

**Buổi 1:** Kotlin Data Models
- Đọc: CURRICULUM.md → Buổi 1
- Tạo: `app/src/main/java/com/hltech/mystudentlife/week1/model/`
- File: `SinhVien.kt`, `MonHoc.kt`, `Constants.kt`

**Buổi 2:** Android Studio & Trang Chủ
- Tạo: `MainActivity.kt`
- File layout: `res/layout/activity_main.xml`

**Buổi 3-5:** Hoàn thiện Week 1
- Thêm Button, Intent, Profile activity
- Xem chi tiết trong CURRICULUM.md

### Tuần 2-6
- Tiếp tục theo folder tuần tương ứng
- Xem CURRICULUM.md cho hướng dẫn chi tiết

## 🐛 Bước 4: Debug

Nếu gặp lỗi:
1. Xem Logcat (Android Studio > View > Tool Windows > Logcat)
2. Tìm error message
3. Xem TROUBLESHOOTING.md
4. Google error message
5. Hỏi giảng viên nếu vẫn không fix được

## ✅ Bước 5: Test & Submit

- Test app trên Emulator hoặc Device
- Commit code: `git add . && git commit -m "Hoàn thành buổi X"`
- Push: `git push origin main`

## 📞 Liên Hệ

**Tác giả:** Lê Tiến Hiếu  
**Email:** letienhieu@vute.edu.vn  
**GitHub:** @letienhieu-lecturer

---

## 🗂️ Cấu Trúc Thư Mục Cơ Bản

```
mystudentlife/
├── app/src/main/
│   ├── java/com/hltech/mystudentlife/
│   │   ├── week1/        ← Tuần 1
│   │   ├── week2/        ← Tuần 2
│   │   ├── week3-6/      ← Tuần 3-6
│   │   └── ...
│   └── res/
│       ├── layout/       ← XML files
│       ├── values/       ← Strings, colors, themes
│       └── drawable/     ← Icons, images
├── README.md             ← Tổng quan
├── CURRICULUM.md         ← Chi tiết học tập
└── TROUBLESHOOTING.md    ← Debug tips
```

## 🔑 Quy Ước Đặt Tên

- **Activity:** `[Feature]Activity.kt` (VD: `MainActivity.kt`, `ProfileActivity.kt`)
- **Fragment:** `[Feature]Fragment.kt` (VD: `HomeFragment.kt`)
- **Adapter:** `[Item]Adapter.kt` (VD: `SubjectAdapter.kt`)
- **Layout:** `activity_[name].xml`, `item_[name].xml`, `fragment_[name].xml`
- **Model/Entity:** `[Model].kt`, `[Model]Entity.kt`

## 📝 Quy Trình Mỗi Buổi

1. Đọc CURRICULUM.md → Buổi X
2. Xem kiến thức cần học
3. Tạo các file cần thiết
4. Code theo hướng dẫn
5. Test app
6. Nếu lỗi → xem TROUBLESHOOTING.md
7. Commit & push code

## 🎯 Mục Tiêu Cuối Khóa

**Tuần 1-6:**
- ✅ MyStudentLife v6.0 hoàn chỉnh
- ✅ 6 phiên bản (v1.0 → v6.0)
- ✅ Sẵn sàng publish lên Play Store

**Tuần 7-8:**
- ✅ Dự án cá nhân hoàn thiện
- ✅ Demo trước lớp
- ✅ Nhận feedback

## 💡 Tips Học Hiệu Quả

1. **Đọc kỹ yêu cầu:** Mỗi buổi có rõ ràng file nào tạo
2. **Test thường xuyên:** Không code hết rồi test
3. **Commit thường:** Git commit mỗi buổi học
4. **Xem logcat:** Lỗi sẽ hiện trong Logcat
5. **Hỏi giảng viên:** Đừng chần chừ, email ngay

## 🚀 Bắt Đầu Ngay!

```bash
# 1. Clone
git clone https://github.com/letienhieu-lecturer/buoi11-mystudentlife.git

# 2. Mở Android Studio
# File > Open > Chọn thư mục

# 3. Đợi Gradle sync

# 4. Bắt đầu code Buổi 1!
```

---

**Chúc bạn học tập vui vẻ! 🎉**

Nếu có bất kỳ câu hỏi, vui lòng gửi email đến: **letienhieu@vute.edu.vn**

