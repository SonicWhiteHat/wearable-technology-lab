# 🖥️ تصميم لوحة التحكم (Dashboard Design)

## ✨ الوظائف الرئيسية
- عرض معدل نبض القلب ومستوى التوتر بشكل لحظي.
- توفير تنبيهات حية بناءً على البيانات المستلمة.
- تسجيل الأحداث المهمة وعرضها بطريقة منظمة.

---

## 🧑‍💻 التقنيات المستخدمة
- **ReactJS** مع **TailwindCSS** لبناء الواجهة.
- **WebSocket** لاستقبال البيانات الحية في الوقت الفعلي.

---

## 🛠️ مثال تطبيقي بسيط
مكون React بسيط لعرض معدل نبض القلب:

```jsx
function HeartRateCard({ heartRate }) {
  return (
    <div className="bg-white shadow-md p-6 rounded-2xl text-center">
      <h2 className="text-xl font-semibold mb-2">معدل نبض القلب</h2>
      <p className="text-3xl font-bold text-red-500">{heartRate} bpm</p>
    </div>
  );
}
