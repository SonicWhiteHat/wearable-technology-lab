
---

# 📄 docs/dashboard-design/README.md

```markdown
# 🖥️ Dashboard Design

## ✨ وظيفة الواجهة
- عرض نبض القلب ومستوى التوتر.
- تنبيهات حية.
- سجل للأحداث.

---

## 🧑‍💻 التكنولوجيا المستخدمة
- ReactJS + TailwindCSS
- WebSocket للبيانات الحية

---

## 🛠️ مثال تطبيقي بسيط:
إنشاء بطاقة صغيرة في React تعرض معدل نبض القلب:

```jsx
function HeartRateCard({ heartRate }) {
  return (
    <div className="bg-white shadow p-4 rounded-xl">
      <h2 className="text-xl font-bold">نبض القلب:</h2>
      <p className="text-2xl">{heartRate} bpm</p>
    </div>
  );
}
