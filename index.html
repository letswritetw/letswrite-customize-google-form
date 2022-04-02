<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>完全客製google表單，美化表單樣式 - August - Let's Write</title>
  <link rel="canonical" href="https://www.letswrite.tw/custom-google-form/">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/skeleton/2.0.4/skeleton.min.css">

  <!-- customized style -->
  <style>
    *, *::before, *::after {
      box-sizing: border-box;
      font-size: 16px;
    }
    html, body, .container, .row {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
    }
    .container {
      max-width: 100%;
    }
    button {
      font-size: 16px;
    }

    .half {
      position: fixed;
      margin: 0;
      width: 50% !important;
      height: 100%;
    }
    .bg {
      background: url('https://fakeimg.pl/1920x1024/?text=KV') center center;
      background-size: cover;
    }
    .form {
      left: 50%;
      overflow: auto;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
    }
    h1, form {
      width: 100%;
    }
    h1 {
      padding-top: 16px;
      text-align: center;
    }
    form {
      margin-right: auto;
      margin-left: auto;
      max-width: 400px;
    }
    .input-group {
      margin-bottom: 30px;
    }
    .radio-group label {
      display: inline-block;
    }
    textarea {
      min-height: 100px;
    }

    @media screen and (max-width: 1024px) {
      .half {
        position: static;
        width: 100% !important;
        height: auto;
      }
      .bg {
        height: 30vh;
      }
      form {
        padding-right: 12px;
        padding-left: 12px;
      }
    }
    

  </style>

  <link rel="shortcut icon" href="https://letswritetw.github.io/letswritetw/dist/img/logo_512.png"/>

  <!-- Google Tag Manager-->
  <script>
    (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-PGQ9WQT');
  </script>

</head>
<body>

  <!-- Google Tag Manager (noscript)-->
  <noscript>
    <iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PGQ9WQT" height="0" width="0" style="display:none;visibility:hidden"></iframe>
  </noscript>

  <div class="container">
    <main class="row">
      <!-- bg -->
      <section class="six columns half bg"></section>
      
      <!-- form -->
      <section class="six columns half form">
        <h1>Contact us</h1>
        <form>
          <!-- 姓名 -->
          <div class="input-group">
            <label for="demo_name">姓名</label>
            <input class="u-full-width" type="text" placeholder="test@mailbox.com" id="demo_name">
          </div>

          <!-- 性別 -->
          <div class="input-group">
            <label>姓別</label>
            <div class="radio-group row">
              <!-- 男性 -->
              <div class="four columns">
                <input type="radio" id="male" name="demo_radio" value="male" checked>
                <label for="male">男性</label>
              </div>

              <!-- 女性 -->
              <div class="four columns">
                <input type="radio" id="female" name="demo_radio" value="female">
                <label for="female">女性</label>
              </div>

              <!-- 法人 -->
              <div class="four columns">
                <input type="radio" id="legal" name="demo_radio" value="legal">
                <label for="legal">法人</label>
              </div>
            </div>
          </div>

          <!-- 詢問類別 -->
          <div class="input-group">
            <label for="demo_select">詢問類別</label>
            <select class="u-full-width" id="demo_select">
              <option value="0" value="0" selected disabled>請選擇</option>
              <option value="cat">貓類</option>
              <option value="dog">狗類</option>
              <option value="bear">熊類</option>
            </select>
          </div>

          <!-- 詢問內容 -->
          <div class="input-group">
            <label for="demo_textarea">詢問內容</label>
            <textarea class="u-full-width" id="demo_textarea"></textarea>
          </div>

          <button type="button" id="submit" class="button-primary u-full-width">確認送出</button>

        </form>
      </section>
    </main>
  </div>

  <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
  <script>
    $(function() {
      $('#submit').on('click', function() {
        
        // 姓名
        var name = $('#demo_name').val() || '未填寫';

        // 性別
        var sex = function() {
          var v;
          $('[name="demo_radio"]').each(function() {
            if($(this).prop('checked') === true) v = $(this).val();
          });
          return v;
        };

        // 類別
        var cat = $('#demo_select').val() || '未填寫';

        // 內容
        var msg = $('#demo_textarea').val() || '未填寫';

        // post
        var data = {
          'entry.248434920': name,
          'entry.1569038925': sex(),
          'entry.1509045370': cat,
          'entry.758411200': msg
        };
        $.ajax({
          type: 'POST',
          url: 'https://docs.google.com/forms/d/e/1FAIpQLSeTgHEpVpuV_OHakO-25X-O7I4T1tIzIAUqHWLRvUqG9e6TvQ/formResponse',
          data: data,
          contentType: 'application/json',
          dataType: 'jsonp',
          complete: function() {
            alert('資料已送出！');
          }
        });
        
      });
    });
  </script>
  
</body>
</html>
