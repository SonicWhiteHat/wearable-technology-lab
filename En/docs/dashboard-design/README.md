# 🖥️ Dashboard Design

## ✨ Main Features
- Real-time display of heart rate and stress levels.
- Live alerts based on incoming data.
- Event logging and organized history display.

---

## 🧑‍💻 Technologies Used
- **ReactJS** with **TailwindCSS** for the frontend.
- **WebSocket** for real-time data streaming.

---

## 🛠️ Simple Implementation Example
A basic React component to display heart rate:

```jsx
function HeartRateCard({ heartRate }) {
  return (
    <div className="bg-white shadow-md p-6 rounded-2xl text-center">
      <h2 className="text-xl font-semibold mb-2">Heart Rate</h2>
      <p className="text-3xl font-bold text-red-500">{heartRate} bpm</p>
    </div>
  );
}
