# Jie Yang
<head>
  <style>
    /* 初始隐藏的CSS样式 */
    .watermark {
      display: none;
    }
  </style>
  <script>
    // 在DOM加载之前移除水印元素
    document.addEventListener("DOMContentLoaded", function() {
      var elements = document.getElementsByTagName('*');
      for (var i = 0; i < elements.length; i++) {
        if (elements[i].innerText && elements[i].innerText.includes("leoyang.github.io")) {
          elements[i].style.display = 'none';
        }
      }
    });
  </script>
</head>
<body>
  <div style="display: flex;">
    <div style="flex: 1; margin-right: 20px;">
      <p>Ph.D. in Computer Science and Technology. Computer Vision & Natural Language Processing Researcher.</p>
      <p>📍 Xiamen, China </p>
      <p>✉️ <a href="mailto:leoy220@gmail.com">Email</a></p>
      <p>📚 <a href="https://scholar.google.com/citations?user=your_google_scholar_id">Google Scholar</a></p>
    </div>
    <div style="flex: 3;">
      <h2>About Me</h2>
      <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&width=600&lines=I+Received+My+Ph.D.+Degree+in+CS%26T+from+XMU;+I+Received+My+M.S.+Degree+in+Telecom+from+UNSW;+My+Research+Interests+Include:;+Natural+Language+Processing,+Computer+Vision,+etc." alt="Typing SVG">
    </div>
  </div>

  ## My Location
  <div style="position: relative; width: 600px; height: 450px;">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d11153.316369043733!2d118.098501!3d24.439521!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjTCsDI2JzIyLjMiTiAxMTjCsDA1JzU0LjYiRQ!5e0!3m2!1sen!2s!4v1597822389101!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
    <div class="watermark" style="position: absolute; bottom: 10px; right: 10px; background-color: white; width: 120px; height: 30px;"></div>
  </div>
</body>
