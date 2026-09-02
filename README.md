<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes" />
    <title>🛡️ Shamshir Ali – Report Violating Channel</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600;700;800&display=swap');

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Inter', 'Segoe UI', sans-serif;
            background: #0a0a0f;
            color: #e0e0e0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 16px;
            background-image: radial-gradient(ellipse at 10% 20%, rgba(200, 0, 255, 0.03) 0%, transparent 50%),
                              radial-gradient(ellipse at 90% 80%, rgba(255, 0, 200, 0.03) 0%, transparent 50%);
        }

        .container {
            max-width: 860px;
            width: 100%;
            background: rgba(16, 16, 24, 0.92);
            backdrop-filter: blur(16px);
            border-radius: 36px;
            padding: 44px 38px;
            border: 1px solid rgba(200, 0, 255, 0.15);
            box-shadow: 0 30px 70px rgba(0, 0, 0, 0.85), 0 0 0 1px rgba(200, 0, 255, 0.05) inset;
        }

        .header { text-align: center; margin-bottom: 28px; }
        .badge {
            display: inline-block;
            background: rgba(200, 0, 255, 0.12);
            border: 1px solid rgba(200, 0, 255, 0.25);
            border-radius: 100px;
            padding: 6px 22px;
            font-size: 11px;
            letter-spacing: 2.5px;
            color: #c084fc;
            text-transform: uppercase;
            font-weight: 700;
            margin-bottom: 12px;
        }
        .title {
            font-family: 'Orbitron', monospace;
            font-size: 38px;
            font-weight: 700;
            background: linear-gradient(135deg, #c084fc, #f472b6, #c084fc);
            background-size: 200% 200%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 4s ease-in-out infinite;
            letter-spacing: 1px;
        }
        @keyframes shimmer {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .sub { color: #8892b0; font-size: 15px; margin-top: 8px; font-weight: 300; }
        .glow-line {
            width: 70px;
            height: 2px;
            background: linear-gradient(90deg, transparent, #c084fc, transparent);
            margin: 18px auto;
            border-radius: 2px;
            opacity: 0.4;
        }

        .info-box {
            background: rgba(200, 0, 255, 0.05);
            border-radius: 16px;
            padding: 16px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(200, 0, 255, 0.08);
            font-size: 14px;
        }
        .info-box strong { color: #c084fc; }

        .to-box {
            background: rgba(200, 0, 255, 0.05);
            border-radius: 16px;
            padding: 14px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(200, 0, 255, 0.08);
            font-size: 13.5px;
            color: #8892b0;
            text-align: center;
        }
        .to-box .addr {
            color: #f472b6;
            font-weight: 600;
            direction: ltr;
            display: inline-block;
            margin: 0 4px;
        }

        .id-box {
            background: rgba(200, 0, 255, 0.06);
            border-radius: 12px;
            padding: 10px 18px;
            border: 1px solid rgba(200, 0, 255, 0.12);
            font-size: 14px;
            text-align: center;
            margin-bottom: 14px;
            color: #c084fc;
        }
        .id-box strong { color: #fff; }

        .email-selector {
            margin: 15px 0;
            padding: 12px;
            background: rgba(200, 0, 255, 0.04);
            border-radius: 12px;
            border: 1px solid rgba(200, 0, 255, 0.08);
            max-height: 200px;
            overflow-y: auto;
        }
        .email-selector::-webkit-scrollbar { width: 4px; }
        .email-selector::-webkit-scrollbar-track { background: rgba(200,0,255,0.02); border-radius: 10px; }
        .email-selector::-webkit-scrollbar-thumb { background: #c084fc; border-radius: 10px; }

        .email-selector label {
            display: block;
            padding: 6px 10px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 12px;
            color: #8892b0;
            transition: 0.2s;
            border-left: 2px solid transparent;
        }
        .email-selector label:hover { background: rgba(200,0,255,0.06); color: #e0e0e0; }
        .email-selector label.selected {
            background: rgba(200,0,255,0.08);
            color: #c084fc;
            border-left-color: #c084fc;
        }
        .email-selector input[type="radio"] {
            margin-left: 10px;
            accent-color: #c084fc;
            transform: scale(1.1);
        }

        .email-card {
            background: rgba(255,255,255,0.02);
            border-radius: 18px;
            padding: 24px 26px;
            border: 1px solid rgba(200,0,255,0.08);
            transition: all 0.3s ease;
            margin-top: 10px;
        }
        .email-card:hover {
            border-color: rgba(200,0,255,0.2);
            background: rgba(200,0,255,0.04);
            box-shadow: 0 8px 35px rgba(0,0,0,0.4);
        }
        .email-card .subject {
            color: #e6f1ff;
            font-weight: 700;
            font-size: 16px;
            margin-bottom: 10px;
            text-align: center;
        }

        .email-card .body-preview {
            color: #c9d1d9;
            font-size: 13px;
            direction: ltr;
            text-align: left;
            font-family: 'Courier New', monospace;
            white-space: pre-wrap;
            word-break: break-word;
            line-height: 1.9;
            max-height: 320px;
            overflow-y: auto;
            padding: 16px 18px;
            background: rgba(0,0,0,0.35);
            border-radius: 12px;
            margin-bottom: 12px;
            border: 1px solid rgba(200,0,255,0.06);
        }
        .email-card .body-preview::-webkit-scrollbar { width: 4px; }
        .email-card .body-preview::-webkit-scrollbar-track { background: rgba(200,0,255,0.02); border-radius: 10px; }
        .email-card .body-preview::-webkit-scrollbar-thumb { background: #c084fc; border-radius: 10px; }

        .email-card .links {
            font-size: 12px;
            color: #f472b6;
            margin: 12px 0 8px;
            direction: ltr;
            text-align: left;
        }
        .email-card .links a { color: #f472b6; text-decoration: none; transition: color 0.2s; }
        .email-card .links a:hover { color: #ec4899; text-decoration: underline; }

        .btn-group {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 18px;
        }
        .btn-email {
            background: linear-gradient(135deg, #6366f1, #4f46e5);
            color: #fff;
            padding: 14px 36px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: all 0.25s ease;
            font-family: 'Inter', sans-serif;
            box-shadow: 0 0 30px rgba(99,102,241,0.15);
            width: 100%;
            justify-content: center;
        }
        .btn-email:hover { transform: scale(0.97); box-shadow: 0 0 50px rgba(99,102,241,0.3); }

        .btn-gmail {
            background: linear-gradient(135deg, #c084fc, #a855f7);
            color: #fff;
            padding: 14px 36px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: all 0.25s ease;
            font-family: 'Inter', sans-serif;
            box-shadow: 0 0 30px rgba(192,132,252,0.15);
            width: 100%;
            justify-content: center;
        }
        .btn-gmail:hover { transform: scale(0.97); box-shadow: 0 0 50px rgba(192,132,252,0.3); }

        .btn-copy {
            background: linear-gradient(135deg, #f472b6, #ec4899);
            color: #fff;
            padding: 14px 36px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: all 0.25s ease;
            font-family: 'Inter', sans-serif;
            box-shadow: 0 0 30px rgba(244,114,182,0.15);
            width: 100%;
            justify-content: center;
        }
        .btn-copy:hover { transform: scale(0.97); box-shadow: 0 0 50px rgba(244,114,182,0.3); }

        .status-msg { text-align: center; font-size: 13px; color: #8892b0; margin-top: 10px; min-height: 22px; }

        .footer {
            text-align: center;
            font-size: 12px;
            color: #495670;
            margin-top: 28px;
            border-top: 1px solid rgba(200,0,255,0.06);
            padding-top: 22px;
        }
        .footer a { color: #8892b0; text-decoration: none; transition: color 0.3s; }
        .footer a:hover { color: #c084fc; }
        .footer-links { display: flex; justify-content: center; gap: 24px; flex-wrap: wrap; margin-top: 10px; }

        .badge-count { text-align: center; font-size: 12px; color: #495670; margin: 4px 0 8px 0; }

        .btn-group { flex-direction: column; gap: 12px; }
        .email-card .body-preview { font-size: 15px; max-height: 400px; padding: 18px 20px; line-height: 2; }
        .email-card .subject { font-size: 18px; }
        .to-box .addr { font-size: 16px; }
        .info-box { font-size: 16px; padding: 18px 22px; }
        .id-box { font-size: 16px; padding: 14px 20px; }
        .email-selector label { font-size: 14px; padding: 10px 14px; }
        .badge-count { font-size: 14px; }

        @media (max-width: 640px) {
            .container { padding: 20px 16px; }
            .title { font-size: 28px; }
            .email-card { padding: 16px; }
            .email-card .body-preview { font-size: 14px; padding: 14px; max-height: 350px; }
            .btn-email, .btn-gmail, .btn-copy { font-size: 17px; padding: 14px; }
            .to-box { font-size: 14px; }
            .info-box { font-size: 14px; }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <div class="badge">⚡ Security Reporting System</div>
        <h1 class="title">🛡️ Shamshir Ali</h1>
        <p class="sub">Report Violating News Channel – DAYA NEWS</p>
        <div class="glow-line"></div>
    </div>

    <div class="info-box">
        <strong>📌 Violating Channel Info:</strong><br />
        <span class="label">Channel Name:</span> <strong>DAYA NEWS</strong><br />
        <span class="label">Username:</span> <strong>@daya_finance</strong>
    </div>

    <div class="id-box">
        🆔 <strong>Channel:</strong> @daya_finance
    </div>

    <div class="to-box">
        <strong>📨 Send to ALL Telegram emails:</strong><br />
        <span class="addr">abuse@telegram.org</span> &nbsp;|&nbsp;
        <span class="addr">dmca@telegram.org</span> &nbsp;|&nbsp;
        <span class="addr">security@telegram.org</span> &nbsp;|&nbsp;
        <span class="addr">grievance-in@telegram.org</span> &nbsp;|&nbsp;
        <span class="addr">support@telegram.org</span> &nbsp;|&nbsp;
        <span class="addr">legal@telegram.org</span>
    </div>

    <div class="badge-count">📝 Select one of <strong>100 unique</strong> email templates</div>
    <div class="email-selector" id="emailSelector"></div>

    <div class="email-card">
        <div class="subject" id="emailSubject">Loading...</div>
        <div class="body-preview" id="emailBody">Loading...</div>

        <div class="links">
            🔗 <strong>Violating Links (15 from report):</strong><br />
            <a href="https://t.me/daya_finance/11488" target="_blank">11488</a> ·
            <a href="https://t.me/daya_finance/11408" target="_blank">11408</a> ·
            <a href="https://t.me/daya_finance/11397" target="_blank">11397</a> ·
            <a href="https://t.me/daya_finance/11360" target="_blank">11360</a> ·
            <a href="https://t.me/daya_finance/11358" target="_blank">11358</a> ·
            <a href="https://t.me/daya_finance/11158" target="_blank">11158</a> ·
            <a href="https://t.me/daya_finance/11092" target="_blank">11092</a> ·
            <a href="https://t.me/daya_finance/11074" target="_blank">11074</a> ·
            <a href="https://t.me/daya_finance/11069" target="_blank">11069</a> ·
            <a href="https://t.me/daya_finance/11052" target="_blank">11052</a> ·
            <a href="https://t.me/daya_finance/11045" target="_blank">11045</a> ·
            <a href="https://t.me/daya_finance/11031" target="_blank">11031</a> ·
            <a href="https://t.me/daya_finance/11008" target="_blank">11008</a> ·
            <a href="https://t.me/daya_finance/10978" target="_blank">10978</a> ·
            <a href="https://t.me/daya_finance/10871" target="_blank">10871</a>
        </div>

        <div class="btn-group">
            <a href="#" class="btn-email" onclick="sendEmail()">📧 Send via Email</a>
            <a href="#" class="btn-gmail" onclick="sendGmail()">📧 Send via Gmail</a>
            <button class="btn-copy" onclick="copyEmail()">📋 Copy Text</button>
        </div>
        <div class="status-msg" id="statusMsg"></div>
    </div>

    <div class="footer">
        📨 Send to: abuse@telegram.org | dmca@telegram.org | security@telegram.org | grievance-in@telegram.org | support@telegram.org | legal@telegram.org
        <div class="footer-links">
            <span>© 2026 Shamshir Ali</span>
            <a href="https://github.com/cyberzxr" target="_blank">🐙 GitHub</a>
            <a href="https://t.me/ShamshirAliBot" target="_blank">🤖 Telegram Bot</a>
        </div>
    </div>
</div>

<script>
// ============================================================
// CONFIGURATION
// ============================================================
const TO_EMAILS = [
    "abuse@telegram.org",
    "dmca@telegram.org",
    "security@telegram.org",
    "grievance-in@telegram.org",
    "support@telegram.org",
    "legal@telegram.org"
];

const CHANNEL_USERNAME = "@daya_finance";
const CHANNEL_NAME = "DAYA NEWS";

const ALL_LINKS = [
    "https://t.me/daya_finance/11488",
    "https://t.me/daya_finance/11408",
    "https://t.me/daya_finance/11397",
    "https://t.me/daya_finance/11360",
    "https://t.me/daya_finance/11358",
    "https://t.me/daya_finance/11158",
    "https://t.me/daya_finance/11092",
    "https://t.me/daya_finance/11074",
    "https://t.me/daya_finance/11069",
    "https://t.me/daya_finance/11052",
    "https://t.me/daya_finance/11045",
    "https://t.me/daya_finance/11031",
    "https://t.me/daya_finance/11008",
    "https://t.me/daya_finance/10978",
    "https://t.me/daya_finance/10871"
];

// ============================================================
// 100 UNIQUE EMAIL TEMPLATES
// ============================================================
const templates = [];

const identities = [
    "a human rights activist", "a journalist", "a lawyer", "a concerned citizen",
    "a teacher", "a doctor", "a student", "a researcher", "a writer",
    "a community leader", "a refugee", "a peace activist", "a humanitarian",
    "a psychologist", "a social worker", "a volunteer", "a nurse", "a counselor",
    "a mentor", "a guide", "a helper", "a friend", "a neighbor", "a colleague",
    "a partner", "a teammate", "a classmate", "a roommate", "a citizen of the world",
    "a believer in justice", "a seeker of truth", "a defender of freedom",
    "a protector of the vulnerable", "a voice for the voiceless", "a fighter for rights",
    "a lover of peace", "a hater of oppression", "a dreamer of a better world",
    "an artist", "a musician", "a scientist", "a philosopher", "a historian"
];

const intros = [
    "I am writing to urgently report a news channel that is spreading misinformation and illegal content.",
    "I am deeply concerned about the harmful activities of a channel that poses as a news source but spreads fake news and illegal content.",
    "This is an urgent report regarding a channel that is violating Telegram's policies and spreading dangerous misinformation.",
    "I am reporting a so-called 'news' channel that is being used as a tool for spreading propaganda and illegal content.",
    "The following channel is systematically sharing fake news, drugs-related content, and NSFW material.",
    "I have documented serious violations by a channel that pretends to be a legitimate news source.",
    "This channel is causing real-world harm by spreading misinformation and must be investigated immediately.",
    "I am a concerned user and I want to report dangerous behavior on a channel that claims to be news.",
    "The channel I am reporting is actively spreading fake news and illegal content to its followers.",
    "I have evidence of a channel that is violating Telegram's Terms of Service while pretending to be a news source.",
    "This channel is a direct threat to public safety by spreading harmful misinformation.",
    "I am submitting this report to protect innocent people from being misled by this channel.",
    "The content on this channel includes fake news, copyright violations, and drug-related material.",
    "I have collected substantial evidence of rule-breaking activities by this so-called news channel.",
    "This channel poses a significant risk to public safety by spreading fake news and illegal content."
];

const bodies = [
    "They are spreading fake news and misinformation about political events, which can cause real-world harm and panic.",
    "The channel is publishing copyrighted content without permission, including videos and images from various sources.",
    "They are sharing drug-related content, including advertisements for illegal substances.",
    "The channel is posting NSFW (Not Safe For Work) content that is inappropriate for a news platform.",
    "They are sharing private information and personal data of individuals without consent.",
    "The channel is promoting hate speech and violence against certain groups.",
    "They are encouraging illegal activities through their content and advertisements.",
    "The channel is using Telegram to spread propaganda and false information.",
    "They are manipulating public opinion through fake news and misleading headlines.",
    "The channel is violating copyright laws by sharing pirated content and media.",
    "They are promoting drug use and illegal substances through their posts.",
    "The channel is sharing explicit and inappropriate content that violates Telegram's policies.",
    "They are spreading conspiracy theories and misinformation that can cause panic.",
    "The channel is being used as a platform for illegal activities and harassment.",
    "They are enabling the spread of harmful information that can cause real-world consequences."
];

const closings = [
    "I urge you to investigate and block this channel immediately.",
    "Please take immediate action to remove this channel and protect users.",
    "This channel must be shut down to prevent further harm.",
    "I request that you take this report seriously and block the channel.",
    "Please investigate and take appropriate action against this channel.",
    "This is a serious violation that requires immediate attention.",
    "I hope you will act swiftly to remove this dangerous channel.",
    "Please protect Telegram users by blocking this channel.",
    "This channel is a threat to safety and must be removed.",
    "I trust you will take the necessary action to stop this harmful activity.",
    "The world is watching, please take action against this illegal channel.",
    "This channel is causing real harm to real people right now.",
    "Failure to act would put more innocent lives at risk.",
    "I expect Telegram to uphold its own policies and remove this channel.",
    "Your swift action will save lives and protect human rights."
];

for (let i = 0; i < 100; i++) {
    const identity = identities[i % identities.length];
    const intro = intros[i % intros.length];
    const body = bodies[i % bodies.length];
    const closing = closings[i % closings.length];
    const num = i + 1;

    const subject = `🚨 URGENT: Report Violating News Channel ${CHANNEL_USERNAME} (Report #${num})`;

    const emailBody = `Dear Telegram Trust & Safety Team,

${intro}

The channel is called ${CHANNEL_NAME} (${CHANNEL_USERNAME}) and has been active for a long time, posing as a legitimate news source.

${body}

I have documented multiple examples of this harmful activity. Here are the links to the posts:

${ALL_LINKS.join('\n')}

${closing}

Thank you for your attention to this serious matter.

Sincerely,
${identity.charAt(0).toUpperCase() + identity.slice(1)}

Channel: ${CHANNEL_NAME} (${CHANNEL_USERNAME})
Links: ${ALL_LINKS.join(', ')}`;

    templates.push({ subject, body: emailBody });
}

// ============================================================
// RENDER
// ============================================================
let selectedIndex = 0;

function renderSelector() {
    const container = document.getElementById('emailSelector');
    let html = '';
    templates.forEach((t, i) => {
        const isSelected = i === selectedIndex;
        html += `
            <label class="${isSelected ? 'selected' : ''}" onclick="selectTemplate(${i})">
                <input type="radio" name="template" value="${i}" ${isSelected ? 'checked' : ''}>
                #${i+1}: ${t.subject.substring(0, 55)}${t.subject.length > 55 ? '...' : ''}
            </label>
        `;
    });
    container.innerHTML = html;
}

function selectTemplate(index) {
    selectedIndex = index;
    renderSelector();
    updateDisplay();
}

function updateDisplay() {
    const t = templates[selectedIndex];
    document.getElementById('emailSubject').textContent = t.subject;
    document.getElementById('emailBody').textContent = t.body;
}

// ============================================================
// ACTIONS
// ============================================================
function getCurrentTemplate() {
    return templates[selectedIndex];
}

function sendEmail() {
    event.preventDefault();
    const t = getCurrentTemplate();
    const to = TO_EMAILS.join(',');
    const subject = encodeURIComponent(t.subject);
    const body = encodeURIComponent(t.body);
    window.location.href = `mailto:${to}?subject=${subject}&body=${body}`;
    showStatus('📨 Opening email client...');
}

function sendGmail() {
    event.preventDefault();
    const t = getCurrentTemplate();
    const to = TO_EMAILS.join(',');
    const subject = encodeURIComponent(t.subject);
    const body = encodeURIComponent(t.body);
    const gmailWeb = `https://mail.google.com/mail/?view=cm&fs=1&to=${to}&su=${subject}&body=${body}`;
    window.open(gmailWeb, '_blank');
    showStatus('📨 Opening Gmail...');
}

function copyEmail() {
    const t = getCurrentTemplate();
    const text = `Subject: ${t.subject}\n\n${t.body}`;
    navigator.clipboard.writeText(text)
        .then(() => showStatus('✅ Copied to clipboard!', '#c084fc'))
        .catch(() => showStatus('❌ Failed to copy', '#f85149'));
}

function showStatus(msg, color = '#8892b0') {
    const el = document.getElementById('statusMsg');
    el.textContent = msg;
    el.style.color = color;
    setTimeout(() => { el.textContent = ''; }, 3500);
}

// ============================================================
// INIT
// ============================================================
renderSelector();
updateDisplay();
</script>

</body>
</html>
