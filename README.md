body {
  background-color: #222;
  color: #fff;
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.traffic-light {
  width: 100px;
  background: #111;
  padding: 20px;
  border-radius: 20px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-bottom: 20px;
}

.light-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.light {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: #555;
  transition: background-color 0.3s;
}

.red.active { background-color: red; }
.yellow.active { background-color: yellow; }
.green.active { background-color: green; }

.timer {
  margin-top: 5px;
  font-size: 14px;
  height: 18px;
}

.controls {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  justify-content: center;
}

button {
  padding: 10px 15px;
  font-size: 16px;
  cursor: pointer;
  border: none;
  border-radius: 8px;
  transition: background 0.3s;
}

.red-btn { background-color: red; color: white; }
.yellow-btn { background-color: orange; color: white; }
.green-btn { background-color: green; color: white; }
.auto-btn { background-color: #007bff; color: white; }
.manual-btn { background-color: #f39c12; color: white; }

