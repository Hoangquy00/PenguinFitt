<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> V-Coach </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f3f4f6;
      margin: 0;
      padding: 0;
    }
    header {
      background: #1f2937;
      color: white;
      text-align: center;
      padding: 1rem 0;
    }
    main {
      max-width: 600px;
      margin: auto;
      padding: 1rem;
    }
    h2 {
      margin-top: 2rem;
      color: #111827;
    }
    .section {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      margin-bottom: 1rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .button {
      display: block;
      width: 100%;
      margin-top: 0.5rem;
      padding: 0.75rem;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .workout-btn { background-color: #34d399; color: white; }
    .check-btn   { background-color: #f59e0b; color: white; }
    .tip-btn     { background-color: #a78bfa; color: white; }
    .health-btn  { background-color: #f87171; color: white; }
    .history-btn { background-color: #9ca3af; color: white; }
    .option-btn {
      background-color: #60a5fa;
      color: white;
      font-size: 1.2rem;
    }
    .welcome-screen {
      text-align: center;
      padding: 2rem;
    }
    .form-input {
      margin: 0.5rem 0;
    }
    .form-input input {
      width: 100%;
      padding: 0.5rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
  </style>
  <script>
    let currentUserType = '';

    function showVideo(title, src) {
      document.getElementById('videoTitle').innerText = title;
      document.getElementById('workoutVideo').src = src;
      document.getElementById('videoSection').style.display = 'block';
    }

    function showTips() {
      let tips = '';
      if (currentUserType === 'elderly') {
        tips = 'Lời khuyên cho người già:\n1. Khởi động kỹ để tránh té ngã\n2. Tập nhẹ nhàng, đều đặn mỗi ngày\n3. Uống nước ấm trước khi tập\n4. Nghỉ khi thấy chóng mặt\n5. Luôn có người giám sát nếu cần';
      } else if (currentUserType === 'disabled') {
        tips = 'Lời khuyên cho người khuyết tật:\n1. Chọn bài tập phù hợp với tình trạng của bản thân\n2. Tập trung vào những phần cơ thể có thể vận động\n3. Luôn lắng nghe tình trạng của cơ thể\n4. Có thể tập ngồi hoặc sử dụng dụng cụ hỗ trợ \n5. Giữ tinh thần tích cực';
      } else if (currentUserType === 'student') {
        tips = 'Lời khuyên cho học sinh:\n1. Tập thể dục 30 phút mỗi ngày\n2. Giữ lưng thẳng khi ngồi học\n3. Nghỉ giải lao giữa giờ học\n4. Tránh ngồi nhiều trước màn hình\n5. Tăng cường vận động ngoài trời';
      } else {
        tips = 'Hãy chọn loại người dùng trước khi nhận lời khuyên.';
      }
      alert(tips);
    }

    function showHistory() {
      alert('Lịch sử kiểm tra hiện đang trống.');
    }

    function selectUserType(userType) {
      currentUserType = userType;
      document.getElementById('welcomeScreen').style.display = 'none';
      document.getElementById('mainContent').style.display = 'block';

      const workoutSection = document.querySelector('#mainContent .section');
      const title = document.getElementById('workoutTitle');

      const oldButtons = workoutSection.querySelectorAll('.workout-btn');
      oldButtons.forEach(btn => btn.remove());

      let workouts = [];
      if (userType === 'elderly') {
        title.innerText = 'Bài tập cho người già';
        workouts = [
          ['Xoay khớp tay', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Đứng lên ngồi xuống nhẹ', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Co duỗi chân tại chỗ', 'https://www.w3schools.com/html/mov_bbb.mp4']
        ];
      } else if (userType === 'disabled') {
        title.innerText = 'Bài tập cho người khuyết tật';
        workouts = [
          ['Giơ tay qua đầu (ngồi)', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Xoay cổ thư giãn', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Kéo tay ngang ngực', 'https://www.w3schools.com/html/mov_bbb.mp4']
        ];
      } else if (userType === 'student') {
        title.innerText = 'Bài tập cho học sinh';
        workouts = [
          ['Khởi động', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Bài tập cơ bụng', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Bài tập tay', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Bài tập chân', 'https://www.w3schools.com/html/mov_bbb.mp4'],
          ['Bài tập toàn thân', 'https://www.w3schools.com/html/mov_bbb.mp4']
        ];
      }

      workouts.forEach(([title, link]) => {
        const btn = document.createElement('button');
        btn.className = 'button workout-btn';
        btn.innerText = title;
        btn.onclick = () => showVideo(title, link);
        workoutSection.insertBefore(btn, document.getElementById('videoSection'));
      });

      document.getElementById('videoSection').style.display = 'none';
    }

    function evaluateBody() {
      const age = parseInt(document.getElementById('ageInput').value);
      const weight = parseFloat(document.getElementById('weightInput').value);
      const height = parseFloat(document.getElementById('heightInput').value) / 100;
      if (isNaN(age) || isNaN(weight) || isNaN(height)) {
        alert('Vui lòng nhập đầy đủ và đúng thông tin.');
        return;
      }
      const bmi = weight / (height * height);
      let status = '';
      if (bmi < 18.5) status = 'Gầy';
      else if (bmi < 25) status = 'Bình thường';
      else if (bmi < 30) status = 'Thừa cân';
      else status = 'Béo phì';
      alert(`Tuổi: ${age}\nBMI: ${bmi.toFixed(1)}\nTình trạng: ${status}`);
    }
  </script>
</head>
<body>
  <div id="welcomeScreen" class="welcome-screen">
    <h1>Chào mừng đến với V-Coach</h1>
    <p>Vui lòng chọn loại người dùng của bạn để nhận bài tập và lời khuyên phù hợp:</p>
    <button class="button option-btn" onclick="selectUserType('elderly')">Người già</button>
    <button class="button option-btn" onclick="selectUserType('disabled')">Người khuyết tật</button>
    <button class="button option-btn" onclick="selectUserType('student')">Học sinh</button>
  </div>

  <div id="mainContent" style="display: none;">
    <header>
      <h1>💪 PenguinFit</h1>
      <p>Huấn luyện viên ảo</p>
    </header>
    <main>
      <section class="section">
        <h2 id="workoutTitle">🎽 Danh sách bài tập</h2>
        <div class="video-container" id="videoSection">
          <h3 id="videoTitle"></h3>
          <video id="workoutVideo" width="100%" height="auto" controls></video>
        </div>
      </section>

      <section class="section">
        <h2>📝 Kiểm tra</h2>
        <button class="button check-btn" onclick="alert('Bắt đầu kiểm tra')">Bắt đầu kiểm tra</button>
      </section>

      <section class="section">
        <h2>📌 Lời khuyên dành cho bạn </h2>
        <button class="button tip-btn" onclick="showTips()">Xem lời khuyên </button>
      </section>

      <section class="section">
        <h2>🦥 Sức khỏe</h2>
        <button class="button health-btn">Nhịp tim: 00 BPM</button>
        <button class="button health-btn">SpO₂: 00%</button>
        <button class="button health-btn">Nhiệt độ cơ thể: 00°C</button>
        <button class="button health-btn">Đánh giá tổng thể: -- / 10</button>
      </section>

      <section class="section">
        <h2>🧳️ Đánh giá cơ thể</h2>
        <div class="form-input"><input id="ageInput" type="number" placeholder="Nhập tuổi"></div>
        <div class="form-input"><input id="weightInput" type="number" placeholder="Nhập cân nặng (kg)"></div>
        <div class="form-input"><input id="heightInput" type="number" placeholder="Nhập chiều cao (cm)"></div>
        <div class="form-input">
          <div class="form-input">
  <select id="genderInput" style="width: 100%; padding: 10px; border-radius: 8px; border: 1px solid #ccc; font-size: 16px;">
    <option value="">Chọn giới tính</option>
    <option value="male">Nam</option>
    <option value="female">Nữ</option>
  </select>
</div>

  <label for="activityLevel">Chọn thời gian hoạt động:</label>
  <select id="activityLevel">
    <option value="">-- Chọn mức độ --</option>
    <option value="low">Ít vận động (văn phòng)</option>
    <option value="light">Tập thể dục nhẹ (1–2 ngày/tuần)</option>
    <option value="moderate">Tập thể dục vừa phải (3–5 ngày/tuần)</option>
    <option value="intense">Tập thể dục nặng (6–7 ngày/tuần)</option>
    <option value="athlete">Vận động viên (2 lần mỗi ngày)</option>
  </select>
</div>
        <button class="button check-btn" onclick="evaluateBody()">Đánh giá</button>
      </section>

      <section class="section">
        <h2>📚 Lịch sử</h2>
        <button class="button history-btn" onclick="showHistory()">Xem lịch sử kiểm tra</button>
      </section>
    </main>
  </div>
</body>
</html>
