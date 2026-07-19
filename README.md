<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click Pay Dashboard</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        :root { --bg: #0f172a; --card: #1e293b; --accent: #3b82f6; --gold: #fbbf24; --green: #10b981; }
        body { background: var(--bg); color: white; font-family: sans-serif; margin: 0; padding: 20px; }
        
        .header-text { text-align: center; margin-bottom: 20px; font-size: 1.5rem; font-weight: bold; }
        .greeting { text-align: center; margin-bottom: 10px; color: #94a3b8; }
        
        .balance-card { background: var(--card); padding: 30px 20px; border-radius: 20px; text-align: center; border: 2px solid var(--gold); margin-bottom: 20px; }
        .balance-label { margin-bottom: 10px; }
        .balance-val { font-size: 2.2rem; font-weight: bold; color: var(--gold); }
        
        .actions-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 30px; }
        .btn { padding: 15px; border: none; border-radius: 12px; font-weight: bold; cursor: pointer; color: white; }
        .btn-blue { background: var(--accent); }
        .btn-green { background: var(--green); }
        
        .section-title { font-size: 1.2rem; font-weight: bold; margin-bottom: 15px; }
        .task-card { background: var(--card); padding: 20px; border-radius: 15px; display: flex; justify-content: space-between; align-items: center; margin-bottom: 15px; }
        
        /* Modal Style */
        .modal { display: none; position: fixed; top:0; left:0; width:100%; height:100%; background: rgba(0,0,0,0.9); align-items: center; justify-content: center; z-index: 1000; }
        .modal-content { background: var(--card); padding: 25px; border-radius: 20px; width: 85%; }
    </style>
</head>
<body>

    <div class="header-text">Click Pay Dashboard</div>
    <div class="greeting">ሰላም, ተጠቃሚ</div>

    <div class="balance-card">
        <div class="balance-label">ጠቅላላ ቀሪ ሂሳብ</div>
        <div class="balance-val">1,500 Birr</div>
    </div>

    <div class="actions-grid">
        <button class="btn btn-blue" onclick="alert('How to Use clicked')">How to Use</button>
        <button class="btn btn-green" onclick="alert('Withdraw clicked')">Withdraw</button>
    </div>

    <div class="section-title">ተጨማሪ ስራዎች</div>
    
    <div class="task-card">
        <span>Watch Ads (Click Pay)</span>
        <button class="btn btn-blue" onclick="window.open('https://t.me/CLIKPAY_BOT', '_blank')">View</button>
    </div>
    
    <div class="task-card">
        <span>Follow Page (Zeri Plus)</span>
        <button class="btn btn-blue" onclick="window.open('https://t.me/ZERIPLUSFOR', '_blank')">Follow</button>
    </div>

</body>
</html>
