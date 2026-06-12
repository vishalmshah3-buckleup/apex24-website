<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Download BuckleUp</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #f9f6f2;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 24px;
    }
    .card {
      background: #fff;
      border-radius: 20px;
      padding: 40px 32px;
      max-width: 360px;
      width: 100%;
      text-align: center;
      box-shadow: 0 4px 24px rgba(0,0,0,0.08);
    }
    .logo {
      width: 72px;
      height: 72px;
      border-radius: 18px;
      background: #ff6b35;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 20px;
      font-size: 32px;
    }
    h1 { font-size: 22px; font-weight: 700; color: #1a1a1a; margin-bottom: 8px; }
    p  { font-size: 14px; color: #666; margin-bottom: 28px; line-height: 1.5; }
    .spinner {
      width: 32px; height: 32px;
      border: 3px solid #f0ede8;
      border-top-color: #ff6b35;
      border-radius: 50%;
      animation: spin 0.8s linear infinite;
      margin: 0 auto 16px;
    }
    @keyframes spin { to { transform: rotate(360deg); } }
    .status { font-size: 13px; color: #999; margin-bottom: 28px; }
    .btn {
      display: block;
      width: 100%;
      padding: 14px;
      border-radius: 12px;
      font-size: 15px;
      font-weight: 600;
      text-decoration: none;
      margin-bottom: 10px;
      transition: opacity 0.2s;
    }
    .btn:hover { opacity: 0.85; }
    .btn-android { background: #34a853; color: #fff; }
    .btn-ios     { background: #1a1a1a; color: #fff; }
    .btn-web     { background: #f0ede8; color: #555; }
    .manual { display: none; }
  </style>
</head>
<body>
  <div class="card">
    <div class="logo">🎒</div>
    <h1>BuckleUp</h1>
    <p>Discover the best activities for your child</p>

    <!-- Auto-redirect state (shown by default) -->
    <div id="auto-state">
      <div class="spinner"></div>
      <div class="status" id="status-text">Detecting your device…</div>
    </div>

    <!-- Manual fallback (shown if JS redirect fails or desktop) -->
    <div class="manual" id="manual-state">
      <a class="btn btn-android"
         href="https://play.google.com/store/apps/details?id=com.buckleup.app&hl=en_IN">
        ▶ &nbsp;Download on Google Play
      </a>
      <a class="btn btn-ios"
         href="https://apps.apple.com/in/app/buckleup-parent-teacher-app/id6775865530">
        &#63743; &nbsp;Download on App Store
      </a>
      <a class="btn btn-web" href="https://buckleupnow.in/">
        Open website instead
      </a>
    </div>
  </div>

  <script>
    const ANDROID = "https://play.google.com/store/apps/details?id=com.buckleup.app&hl=en_IN";
    const IOS     = "https://apps.apple.com/in/app/buckleup-parent-teacher-app/id6775865530";
    const WEB     = "https://buckleupnow.in/";

    const ua = navigator.userAgent.toLowerCase();
    const statusEl = document.getElementById("status-text");

    function redirect(url, label) {
      statusEl.textContent = "Taking you to the " + label + "…";
      setTimeout(function() {
        window.location.replace(url);
        // If redirect doesn't fire in 2s, show manual buttons
        setTimeout(showManual, 2000);
      }, 600);
    }

    function showManual() {
      document.getElementById("auto-state").style.display = "none";
      document.getElementById("manual-state").style.display = "block";
    }

    if (/android/.test(ua)) {
      redirect(ANDROID, "Play Store");
    } else if (/iphone|ipad|ipod/.test(ua)) {
      redirect(IOS, "App Store");
    } else {
      // Desktop or unknown — skip spinner, show buttons directly
      document.getElementById("auto-state").style.display = "none";
      document.getElementById("manual-state").style.display = "block";
    }
  </script>
</body>
</html>
