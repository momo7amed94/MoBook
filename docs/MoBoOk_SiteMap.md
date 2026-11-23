# MoBoOk — خريطة التطبيق الكاملة (Site Map)

---

## ١. الشاشات الأساسية (Core Screens)

### المجموعة A: المصادقة والتسجيل (Auth)

```
┌─ Splash Screen
│  └─ التحميل الأولي
│
├─ Sign Up Screen
│  ├─ بريد إلكتروني
│  ├─ كلمة مرور
│  └─ قبول الشروط
│
├─ Sign In Screen
│  ├─ بريد إلكتروني
│  ├─ كلمة مرور
│  └─ نسيت كلمة المرور؟
│
├─ Forgot Password Screen
│  ├─ إدخال البريد
│  └─ إرسال رابط إعادة تعيين
│
└─ Email Verification Screen
   └─ تأكيد البريد (رمز التحقق)
```

### المجموعة B: المدينة الفاضلة (Main Feed)

```
┌─ Home / Feed Screen (المدينة الفاضلة)
│  ├─ Timeline (قائمة المنشورات)
│  │  ├─ Post Card
│  │  │  ├─ Voice #123
│  │  │  ├─ محتوى النص
│  │  │  ├─ الوقت
│  │  │  └─ Actions (💛 دعم، 💬 تعليقات)
│  │  │
│  │  └─ Pending Comments Notification (لصاحب المنشور فقط)
│  │
│  ├─ Floating Action Button (+ نشر)
│  ├─ Bottom Navigation
│  └─ Pull to Refresh
│
├─ Create Post Screen
│  ├─ نص المنشور (Text Editor)
│  ├─ اختيار وضع (draft/publish)
│  ├─ زر نشر
│  └─ حفظ كمسودة
│
├─ Post Detail Screen
│  ├─ المنشور الكامل
│  ├─ Approved Comments Section
│  ├─ Pending Comments Section (لصاحب المنشور)
│  │  ├─ Comment Card
│  │  ├─ زر Approve ✓
│  │  └─ زر Reject ✗
│  ├─ Comment Input (لكتابة تعليق)
│  └─ Post Actions (Edit, Delete)
│
└─ Comments Management Screen (لصاحب المنشور)
   ├─ Pending Comments Tab
   ├─ Approved Comments Tab
   ├─ Rejected Comments Tab
   ├─ Comment Card مع actions
   └─ Search/Filter Comments
```

### المجموعة C: الاقتران (Two-Person Connection)

```
┌─ Connection Suggestions Screen
│  ├─ Suggested Connections (بناءً على التفاعل المتبادل)
│  ├─ Connection Card
│  │  ├─ صوت #123
│  │  ├─ عدد التفاعلات المشتركة
│  │  ├─ متطلبات الاقتران (شيكات ✓)
│  │  └─ زر "وافق على الاقتران"
│  └─ Approved Connections List
│
├─ Coupling Detail Screen
│  ├─ الصوت الآخر (#305)
│  ├─ Trust Levels (المستويات الأربعة)
│  │  ├─ Level 1: اهتمامات عامة (مفتوح/مقفول)
│  │  ├─ Level 2: تجارب وقصص (مفتوح/مقفول)
│  │  ├─ Level 3: محادثة مباشرة (مفتوح/مقفول)
│  │  └─ Level 4: كشف الهوية (مفتوح/مقفول)
│  ├─ زر "فتح المستوى التالي"
│  ├─ زر "إنهاء الاقتران"
│  └─ Advanced Settings
│
├─ Trust Level Editor Screen
│  ├─ Level #N Details
│  ├─ محتوى مفصل لكل مستوى
│  ├─ سياسة الكشف
│  ├─ الإشعارات
│  └─ زر Save
│
└─ Direct Messages Screen (يظهر في المستوى ٣)
   ├─ Conversation List
   ├─ Chat Screen
   │  ├─ Message Bubbles (نصية/صوتية)
   │  ├─ Voice Messages Playback
   │  ├─ Read Receipts
   │  ├─ Message Input
   │  ├─ Attach Voice
   │  ├─ Delete Message
   │  └─ Report Conversation
   └─ Call Screen (مستقبلاً)
      ├─ Audio Call
      ├─ Video Call (اختياري)
      └─ Call History
```

### المجموعة D: يوتوبيا (Group Zones)

```
┌─ Utopia Suggestions Screen
│  ├─ Suggested Groups (بناءً على تفاعل ٣+)
│  ├─ Group Card
│  │  ├─ Members (Avatar + Voice #)
│  │  ├─ متطلبات التشكيل (شيكات ✓)
│  │  └─ زر "وافق على التشكيل"
│  └─ Active Utopias List
│
├─ Utopia Detail Screen
│  ├─ Members List
│  ├─ Group Rules
│  ├─ Group Chat / Timeline
│  ├─ Member Settings (إضافة/إزالة)
│  ├─ Leave Group
│  └─ Advanced Settings
│
├─ Group Chat Screen
│  ├─ Messages Timeline
│  ├─ Message Input
│  ├─ File Sharing (audio)
│  ├─ Member Activity
│  └─ Call Members (مستقبلاً)
│
└─ Group Settings Screen
   ├─ Group Name/Description
   ├─ Privacy Settings
   ├─ Member Permissions
   ├─ Leave Group
   └─ Delete Group (Owner only)
```

### المجموعة E: الملف الشخصي والإعدادات (Profile & Settings)

```
┌─ Profile Screen
│  ├─ Avatar Frame (الشكل الدائري للصوت)
│  ├─ Voice ID (#123)
│  ├─ Stats
│  │  ├─ عدد المنشورات
│  │  ├─ عدد الأصوات المتصلة
│  │  ├─ عدد المجموعات
│  │  └─ نسبة القبول على التعليقات
│  ├─ Trust Score (Reputation)
│  ├─ Privacy Settings Button
│  ├─ View My Posts
│  ├─ View My Connections
│  ├─ View My Groups
│  └─ Settings Button
│
├─ Settings Screen
│  ├─ Account Settings
│  │  ├─ تغيير البريد الإلكتروني
│  │  ├─ تغيير كلمة المرور
│  │  ├─ حذف الحساب
│  │  └─ Logout
│  ├─ Privacy Settings
│  │  ├─ من يقدر يطلب اقتران
│  │  ├─ من يقدر يرى منشوراتي
│  │  ├─ كشف الهوية (عام/خاص)
│  │  └─ السماح بالعثور عليّ
│  ├─ Notification Settings
│  │  ├─ تعليقات معلقة
│  │  ├─ اقتران جديد
│  │  ├─ رسائل مباشرة
│  │  └─ طلب دخول مستوى
│  ├─ Blocking & Reporting
│  │  ├─ Blocked Users
│  │  └─ Reported Users
│  ├─ Appearance
│  │  ├─ Dark/Light Mode
│  │  └─ Language (AR/EN)
│  └─ About
│     ├─ App Version
│     ├─ Terms of Service
│     ├─ Privacy Policy
│     └─ Community Guidelines
│
├─ Privacy Settings Detail Screen
│  └─ (شرح مفصل لكل خيار)
│
└─ Help & Support Screen
   ├─ FAQ
   ├─ Contact Us
   ├─ Bug Report
   └─ Feature Request
```

---

## ٢. الشاشات الإضافية (Secondary Screens)

### المجموعة F: البحث والاستكشاف

```
┌─ Search Screen
│  ├─ Search Bar (ابحث عن Voices)
│  ├─ Recent Searches
│  ├─ Popular Voices
│  ├─ Search Results
│  │  ├─ Voice Card
│  │  ├─ Voice Stats
│  │  └─ Action Button (Follow/Connect)
│  └─ Advanced Filters (مستقبلاً)
│
├─ Explore Screen (مستقبلاً)
│  ├─ Trending Topics
│  ├─ Suggested Voices
│  ├─ Community Highlights
│  └─ Recent Activities
│
└─ Voice Profile Screen (لصوت آخر)
   ├─ Voice #305
   ├─ Bio (اختياري)
   ├─ Trust Level (مع الصوت الحالي)
   ├─ Posts (الموافق عليها فقط)
   ├─ Connection Status
   └─ Actions (Connect/Block/Report)
```

### المجموعة G: الإخطارات والأنشطة

```
┌─ Notifications Screen
│  ├─ Pending Comments Alert
│  ├─ New Connection Request
│  ├─ Level Unlock Request
│  ├─ New Message
│  ├─ New Group Invitation
│  ├─ Support Received
│  └─ Clear All
│
└─ Activity Feed (مستقبلاً)
   ├─ Your Posts Activity
   │  ├─ Support Count
   │  ├─ Comment Count
   │  └─ Share Count
   └─ Your Connections Activity
      ├─ New Posts
      ├─ New Messages
      └─ Group Updates
```

### المجموعة H: الأمان والحماية

```
┌─ Report Screen
│  ├─ Report Type (Spam/Harassment/Hate Speech/etc)
│  ├─ Report Reason
│  ├─ Evidence Upload
│  ├─ Submit Report
│  └─ Confirmation
│
├─ Block User Screen
│  ├─ Block Voice #123
│  ├─ Reason (optional)
│  ├─ Confirm Block
│  └─ Unblock Option
│
└─ Safety Center Screen
   ├─ Blocked Users List
   ├─ Reports History
   ├─ Safety Tips
   └─ Contact Moderators
```

---

## ٣. الملاحة (Navigation Structure)

### Main Navigation (Bottom Navigation Bar)
```
┌──────────────────────────────────────┐
│  🏠        💬        👥        ⚙️     │
│ Home    Messages  Connections  More  │
└──────────────────────────────────────┘
```

### "More" Submenu (Drawer/Tab)
```
├─ Profile
├─ Search
├─ Notifications
├─ Settings
├─ Help & Support
└─ Logout
```

### Tab Navigation (في بعض الشاشات)
```
├─ All Comments / Pending Comments / Approved Comments
├─ My Posts / Connections / Groups
├─ Account / Privacy / Notifications / Appearance
```

---

## ٤. Modal/Dialog Screens

```
┌─ Confirm Connection Dialog
│  ├─ "هل تريد الاقتران مع صوت #305؟"
│  ├─ عرض التفاصيل
│  ├─ Cancel / Confirm
│
├─ Confirm Utopia Creation Dialog
│  ├─ "جميع الأعضاء وافقوا!"
│  ├─ عرض الأعضاء
│  └─ Cancel / Create
│
├─ Report Confirmation Dialog
│  ├─ "تم إرسال التقرير"
│  ├─ معرّف التقرير
│  └─ OK
│
├─ Delete Post Confirmation
│  ├─ "حذف هذا المنشور؟"
│  ├─ تحذير (التعليقات ستُحذف)
│  └─ Cancel / Delete
│
├─ Unlock Level Dialog
│  ├─ "طلب فتح المستوى #2"
│  ├─ وصف المستوى
│  └─ Cancel / Request
│
└─ Voice Message Permission Dialog
   ├─ "اسمح بالوصول للميكروفون"
   └─ Cancel / Allow
```

---

## ٥. تدفقات المستخدم (User Flows)

### Flow 1: مستخدم جديد
```
Splash → Sign Up → Email Verification → Onboarding → Home (Feed)
```

### Flow 2: نشر منشور
```
Home → (+ Button) → Create Post → Write Content → Publish → Home
```

### Flow 3: التفاعل مع التعليقات
```
Home → View Post → See Comments → (if owner) Pending Comments 
→ Review → Approve/Reject → Updated Feed
```

### Flow 4: بناء علاقة (Coupling)
```
Home → Interact (posts + comments) → Auto-Suggestion → 
Coupling Detail → Accept → Chat → Level Unlock → Direct Message
```

### Flow 5: إنشاء مجموعة (Utopia)
```
Connections → Select 2+ Voices → Create Utopia → Invite → 
Wait for Approvals → Group Created → Group Chat
```

---

## ٦. شاشات Onboarding (أول مرة)

```
┌─ Welcome Screen
│  └─ شرح MoBoOk (٣٠ ثانية)
│
├─ How It Works Screen #1
│  └─ المدينة الفاضلة (الفيد العام)
│
├─ How It Works Screen #2
│  └─ نظام التعليقات (الفرز)
│
├─ How It Works Screen #3
│  └─ الاقتران والمستويات
│
├─ How It Works Screen #4
│  └─ يوتوبيا (المجموعات)
│
└─ Ready to Start
   └─ (زر البدء → Home)
```

---

## ٧. الشاشات الخاصة بالخطأ

```
├─ 404 Not Found
├─ Connection Lost
├─ Server Error
├─ Unauthorized Access
├─ Account Suspended
└─ Maintenance Mode
```

---

## ٨. ملخص إجمالي للشاشات

| الفئة | العدد | الشاشات |
|---|---|---|
| Auth | 5 | Sign Up, Sign In, Forgot Password, Verify Email, Splash |
| Feed | 4 | Home, Create Post, Post Detail, Comments Mgmt |
| Coupling | 4 | Suggestions, Detail, Trust Levels, Direct Messages |
| Utopia | 4 | Suggestions, Detail, Group Chat, Settings |
| Profile | 4 | Profile, Settings, Privacy, Help & Support |
| Search | 3 | Search, Explore, Voice Profile |
| Notifications | 2 | Notifications, Activity |
| Safety | 3 | Report, Block, Safety Center |
| Onboarding | 6 | Welcome + 4 How-to + Ready |
| Error | 6 | Various Error States |
| **المجموع** | **41** | **شاشة رئيسية** |

---

## ٩. نقاط مهمة في التصميم

✓ **Consistency** — نفس الألوان والـ Typography في كل مكان
✓ **Accessibility** — text contrast، touch targets، readable fonts
✓ **Performance** — lazy loading للمنشورات، pagination للتعليقات
✓ **Offline Support** — cached data يظهر بدون internet
✓ **Responsive Design** — يشتغل على أحجام شاشات مختلفة
✓ **Error Handling** — رسائل خطأ واضحة وقابلة للتصحيح
✓ **Deep Linking** — يقدر تشارك link من أي شاشة
