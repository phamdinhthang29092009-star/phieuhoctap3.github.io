
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bài tập Đúng – Sai theo cấp độ</title>
<style>
  body {font-family: Arial, sans-serif; background: #f4f6fa; margin: 20px;}
  h2 {text-align: center; color: #2c3e50;}
  .question {background: #fff; padding: 15px; margin-bottom: 15px; border-radius: 10px; box-shadow: 0 0 5px #ccc;}
  .statement {margin: 8px 0;}
  button {background: #2ecc71; color: white; padding: 10px 15px; border: none; border-radius: 5px; cursor: pointer;}
  button:hover {background: #27ae60;}
  .result {margin-top: 10px; font-weight: bold;}
  .correct {color: green;}
  .incorrect {color: red;}
</style>
</head>
<body>
<h2>BÀI TẬP ĐÚNG – SAI (TỪ DỄ → KHÓ)</h2>

<div id="quiz">

  <!-- DỄ -->
  <div class="question" data-answer="T,F,T,F">
    <p><b>Câu 1 (Dễ):</b> Hàm số y = sin(x).</p>
    <div class="statement">A. sin(0) = 0 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. sin(π/2) = 0 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. sin(π/2) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. sin(π) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <div class="question" data-answer="T,T,F,F">
    <p><b>Câu 2 (Dễ):</b> Hàm số y = cos(x).</p>
    <div class="statement">A. cos(0) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. cos(π) = -1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. cos(π/2) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. cos(3π/2) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <!-- TRUNG BÌNH -->
  <div class="question" data-answer="F,T,F,T">
    <p><b>Câu 3 (Trung bình):</b> Giá trị tan và cot đặc biệt.</p>
    <div class="statement">A. tan(π/4) = 0 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. tan(π/4) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. cot(π/4) = 0 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. cot(π/4) = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <div class="question" data-answer="T,F,T,F">
    <p><b>Câu 4 (Trung bình):</b> Công thức cơ bản lượng giác.</p>
    <div class="statement">A. sin²x + cos²x = 1 → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. tanx = sinx / cos²x → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. tanx = sinx / cosx → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. cotx = sinx / cosx → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <!-- KHÓ -->
  <div class="question" data-answer="T,F,T,F">
    <p><b>Câu 5 (Khó):</b> Các công thức biến đổi tổng – hiệu.</p>
    <div class="statement">A. sin(a + b) = sin a cos b + cos a sin b → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. cos(a + b) = sin a sin b – cos a cos b → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. sin(a – b) = sin a cos b – cos a sin b → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. cos(a – b) = cos a cos b + sin a sin b → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <div class="question" data-answer="F,T,F,T">
    <p><b>Câu 6 (Khó):</b> Các công thức nhân đôi, nhân ba góc.</p>
    <div class="statement">A. sin(2x) = 2sin²x → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. sin(2x) = 2sinxcosx → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. cos(3x) = 3cosx – 4cos²x → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. sin(3x) = 3sinx – 4sin³x → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <div class="question" data-answer="T,F,F,T">
    <p><b>Câu 7 (Khó hơn):</b> Liên hệ các hàm đối và hàm chẵn – lẻ.</p>
    <div class="statement">A. sin(-x) = -sin(x) → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. cos(-x) = -cos(x) → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. tan(-x) = tan(x) → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. cot(-x) = -cot(x) → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

  <div class="question" data-answer="F,T,F,T">
    <p><b>Câu 8 (Vận dụng cao):</b> Ứng dụng lượng giác vào hình học thực tế.</p>
    <div class="statement">A. Góc nâng càng lớn thì chiều cao càng giảm → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">B. Dùng tan để tính chiều cao cột cờ → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">C. Dùng sin để tính bán kính mặt cầu → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="statement">D. Dùng cos để xác định độ dốc mái nhà → <select><option value="">--Chọn--</option><option value="T">Đúng</option><option value="F">Sai</option></select></div>
    <div class="result"></div>
  </div>

</div>

<div style="text-align:center;">
  <button onclick="checkAnswers()">Kiểm tra kết quả</button>
  <button onclick="resetQuiz()">Làm lại</button>
</div>

<script>
function checkAnswers() {
  const questions = document.querySelectorAll('.question');
  let totalCorrect = 0, total = 0;

  questions.forEach(q => {
    const correct = q.dataset.answer.split(',');
    const selects = q.querySelectorAll('select');
    let html = '';
    selects.forEach((sel, j) => {
      total++;
      if (sel.value === correct[j]) {
        totalCorrect++;
        html += <p class='correct'>${String.fromCharCode(65+j)}: Đúng</p>;
      } else {
        html += <p class='incorrect'>${String.fromCharCode(65+j)}: Sai (Đáp án: ${correct[j]=='T'?'Đúng':'Sai'})</p>;
      }
    });
    q.querySelector('.result').innerHTML = html;
  });

  alert(Bạn trả lời đúng ${totalCorrect}/${total} mệnh đề.);
}

function resetQuiz() {
  document.querySelectorAll('select').forEach(s => s.value = '');
  document.querySelectorAll('.result').forEach(r => r.innerHTML = '');
}
</script>
</body>
</html>
