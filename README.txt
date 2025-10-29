<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>Strongly Typed 日本語版</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="assets/css/main.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

  <!-- ヘッダー -->
  <header id="header">
    <h1>Strongly Typed</h1>
    <p>ミニマルでレトロな雰囲気のレスポンシブサイト</p>
  </header>

  <!-- ナビゲーション -->
  <nav id="nav">
    <ul>
      <li><a href="#intro">紹介</a></li>
      <li><a href="#features">特徴</a></li>
      <li><a href="#contact">お問い合わせ</a></li>
    </ul>
  </nav>

  <!-- 紹介セクション -->
  <section id="intro" class="main">
    <div class="content">
      <header>
        <h2>ようこそ！</h2>
      </header>
      <p>
        このテンプレートは、古い取扱説明書にインスパイアされたデザインで、タイポグラフィに重点を置いています。
        HTML5とCSS3で構築されており、すべての基本要素にスタイルが適用されています。
      </p>
    </div>
  </section>

  <!-- 特徴セクション -->
  <section id="features" class="main">
    <div class="content">
      <header>
        <h2>主な特徴</h2>
      </header>
      <ul>
        <li>📱 完全レスポンシブデザイン</li>
        <li>🧾 シンプルで読みやすいレイアウト</li>
        <li>🎨 タイポグラフィ重視のスタイル</li>
        <li>🔧 HTML5/CSS3ベース</li>
      </ul>
    </div>
  </section>

  <!-- お問い合わせセクション -->
  <section id="contact" class="main">
    <div class="content">
      <header>
        <h2>お問い合わせ</h2>
      </header>
      <form method="post" action="https://formspree.io/f/your-form-id">
        <div class="fields">
          <div class="field">
            <label for="name">お名前</label>
            <input type="text" name="name" id="name" required>
          </div>
          <div class="field">
            <label for="email">メールアドレス</label>
            <input type="email" name="email" id="email" required>
          </div>
          <div class="field">
            <label for="message">メッセージ</label>
            <textarea name="message" id="message" rows="5" required></textarea>
          </div>
        </div>
        <ul class="actions">
          <li><input type="submit" value="送信" class="button"></li>
        </ul>
      </form>
    </div>
  </section>

  <!-- フッター -->
  <footer id="footer">
    <p>&copy; Strongly Typed 日本語版 | デザイン: HTML5 UP | 写真: regularjane</p>
  </footer>

</body>
</html>
