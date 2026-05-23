<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kalem Test</title>
</head>
<body>
<div id="app" style="padding:20px;font-family:sans-serif">
  <h2 style="color:#1B4332">Kalem đang load...</h2>
</div>
<script>
// Test cơ bản
try {
  document.getElementById('app').innerHTML = '<h2 style="color:#1B4332">✓ JavaScript chạy OK</h2><p>localStorage: ' + (typeof localStorage !== 'undefined' ? 'OK' : 'FAIL') + '</p>';
} catch(e) {
  document.getElementById('app').innerHTML = 'Lỗi: ' + e.message;
}
</script>
</body>
</html>
