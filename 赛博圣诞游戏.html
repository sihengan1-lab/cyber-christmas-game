<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>高途赛博圣诞·暖冬行动</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Microsoft YaHei', sans-serif;
            background: linear-gradient(135deg, #0B0B45 0%, #1a1a5e 50%, #0B0B45 100%);
            color: #fff;
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* 背景动画效果 */
        .bg-animation {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
            overflow: hidden;
        }

        .snowflake {
            position: absolute;
            color: #39FF14;
            font-size: 1em;
            font-family: Arial;
            text-shadow: 0 0 5px #39FF14;
            animation: fall linear infinite;
            opacity: 0.6;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh) rotate(360deg);
            }
        }

        /* 网格背景 */
        .grid-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(57, 255, 20, 0.1) 1px, transparent 1px),
                linear-gradient(90deg, rgba(57, 255, 20, 0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: 0;
            opacity: 0.3;
        }

        .container {
            position: relative;
            z-index: 1;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        /* 启动页面 */
        .start-screen {
            text-align: center;
            animation: fadeIn 1s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .logo {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 20px;
            background: linear-gradient(90deg, #39FF14, #FF0055, #39FF14);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: gradient 3s linear infinite;
            text-shadow: 0 0 30px rgba(57, 255, 20, 0.5);
        }

        @keyframes gradient {
            to { background-position: 200% center; }
        }

        .subtitle {
            font-size: 1.2em;
            color: #39FF14;
            margin-bottom: 40px;
            text-shadow: 0 0 10px rgba(57, 255, 20, 0.5);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        .status-text {
            font-size: 1em;
            color: #FF0055;
            margin-bottom: 30px;
            font-family: 'Courier New', monospace;
            text-shadow: 0 0 10px rgba(255, 0, 85, 0.5);
        }

        .btn {
            background: linear-gradient(135deg, #39FF14 0%, #2ECC71 100%);
            border: 2px solid #39FF14;
            color: #0B0B45;
            padding: 15px 40px;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 0 20px rgba(57, 255, 20, 0.5);
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 0 30px rgba(57, 255, 20, 0.8);
        }

        .btn:active {
            transform: scale(0.98);
        }

        .btn-secondary {
            background: linear-gradient(135deg, #FF0055 0%, #FF3366 100%);
            border-color: #FF0055;
            box-shadow: 0 0 20px rgba(255, 0, 85, 0.5);
            margin-top: 15px;
        }

        .btn-secondary:hover {
            box-shadow: 0 0 30px rgba(255, 0, 85, 0.8);
        }

        /* 抽取动画页面 */
        .draw-screen {
            display: none;
            text-align: center;
        }

        .draw-screen.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        .scan-line {
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, transparent, #39FF14, transparent);
            position: absolute;
            top: 50%;
            left: 0;
            animation: scan 2s linear infinite;
            box-shadow: 0 0 20px #39FF14;
        }

        @keyframes scan {
            0% { top: 0; opacity: 1; }
            50% { opacity: 0.5; }
            100% { top: 100%; opacity: 1; }
        }

        .draw-text {
            font-size: 1.5em;
            color: #39FF14;
            margin: 40px 0;
            font-family: 'Courier New', monospace;
            text-shadow: 0 0 10px rgba(57, 255, 20, 0.5);
            animation: blink 1s linear infinite;
        }

        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0.3; }
        }

        .identity-preview {
            font-size: 2em;
            color: #FF0055;
            margin: 30px 0;
            min-height: 60px;
            text-shadow: 0 0 15px rgba(255, 0, 85, 0.5);
            font-weight: bold;
        }

        /* 结果页面 */
        .result-screen {
            display: none;
        }

        .result-screen.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        .card {
            background: linear-gradient(135deg, rgba(57, 255, 20, 0.1) 0%, rgba(255, 0, 85, 0.1) 100%);
            border: 2px solid #39FF14;
            border-radius: 20px;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 0 30px rgba(57, 255, 20, 0.3);
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(57, 255, 20, 0.1), transparent);
            animation: rotate 3s linear infinite;
        }

        @keyframes rotate {
            to { transform: rotate(360deg); }
        }

        .rarity-badge {
            display: inline-block;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .rarity-ssr {
            background: linear-gradient(135deg, #FFD700, #FFA500);
            color: #0B0B45;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.8);
            animation: glow 2s ease-in-out infinite;
        }

        .rarity-sr {
            background: linear-gradient(135deg, #FF0055, #FF3366);
            color: #fff;
            box-shadow: 0 0 20px rgba(255, 0, 85, 0.8);
        }

        .rarity-r {
            background: linear-gradient(135deg, #39FF14, #2ECC71);
            color: #0B0B45;
            box-shadow: 0 0 20px rgba(57, 255, 20, 0.8);
        }

        .rarity-n {
            background: linear-gradient(135deg, #888, #aaa);
            color: #fff;
        }

        @keyframes glow {
            0%, 100% { box-shadow: 0 0 20px rgba(255, 215, 0, 0.8); }
            50% { box-shadow: 0 0 40px rgba(255, 215, 0, 1); }
        }

        .identity-name {
            font-size: 1.8em;
            font-weight: bold;
            margin: 15px 0;
            color: #39FF14;
            text-shadow: 0 0 10px rgba(57, 255, 20, 0.5);
        }

        .identity-skill {
            font-size: 1em;
            color: #ccc;
            margin: 15px 0;
            font-style: italic;
        }

        .mission-card {
            background: linear-gradient(135deg, rgba(255, 0, 85, 0.1) 0%, rgba(57, 255, 20, 0.1) 100%);
            border: 2px solid #FF0055;
            border-radius: 15px;
            padding: 25px;
            margin: 20px 0;
            box-shadow: 0 0 30px rgba(255, 0, 85, 0.3);
        }

        .mission-title {
            font-size: 1.2em;
            color: #FF0055;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .mission-content {
            font-size: 1.1em;
            line-height: 1.6;
            margin: 15px 0;
        }

        .energy-reward {
            font-size: 1.3em;
            color: #39FF14;
            font-weight: bold;
            margin-top: 15px;
            text-shadow: 0 0 10px rgba(57, 255, 20, 0.5);
        }

        .action-buttons {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 30px;
        }

        .btn-share {
            background: linear-gradient(135deg, #FF0055 0%, #FF3366 100%);
            border-color: #FF0055;
            color: #fff;
        }

        .btn-complete {
            background: linear-gradient(135deg, #39FF14 0%, #2ECC71 100%);
            border-color: #39FF14;
            color: #0B0B45;
            margin-top: 10px;
        }

        .btn-complete:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        .mission-completed {
            border-color: #39FF14 !important;
            background: linear-gradient(135deg, rgba(57, 255, 20, 0.2) 0%, rgba(46, 204, 113, 0.2) 100%);
        }

        .mission-completed .mission-title::after {
            content: ' ✓';
            color: #39FF14;
        }

        .reroll-info {
            font-size: 0.9em;
            color: #888;
            margin-top: 10px;
            font-style: italic;
        }

        .snapshot-preview {
            margin: 20px 0;
            text-align: center;
        }

        .snapshot-canvas {
            max-width: 100%;
            border: 2px solid #39FF14;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(57, 255, 20, 0.5);
            background: #0B0B45;
        }

        .btn-download {
            background: linear-gradient(135deg, #39FF14 0%, #2ECC71 100%);
            border-color: #39FF14;
            color: #0B0B45;
            margin-top: 10px;
        }

        /* 排行榜页面 */
        .leaderboard-screen {
            display: none;
        }

        .leaderboard-screen.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        .leaderboard-header {
            text-align: center;
            margin-bottom: 30px;
        }

        .leaderboard-title {
            font-size: 2em;
            color: #39FF14;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(57, 255, 20, 0.5);
        }

        .player-info {
            background: rgba(57, 255, 20, 0.1);
            border: 1px solid #39FF14;
            border-radius: 10px;
            padding: 15px;
            margin: 10px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: all 0.3s;
        }

        .player-info:hover {
            background: rgba(57, 255, 20, 0.2);
            transform: translateX(5px);
        }

        .player-info.top3 {
            border-color: #FFD700;
            background: rgba(255, 215, 0, 0.2);
        }

        .rank-badge {
            font-size: 1.5em;
            font-weight: bold;
            min-width: 40px;
        }

        .rank-1 { color: #FFD700; }
        .rank-2 { color: #C0C0C0; }
        .rank-3 { color: #CD7F32; }

        .player-details {
            flex: 1;
            margin-left: 15px;
        }

        .player-id {
            font-size: 0.9em;
            color: #39FF14;
            font-family: 'Courier New', monospace;
        }

        .player-energy {
            font-size: 1.3em;
            font-weight: bold;
            color: #FF0055;
            text-shadow: 0 0 10px rgba(255, 0, 85, 0.5);
        }

        .my-id-display {
            background: rgba(255, 0, 85, 0.2);
            border: 2px solid #FF0055;
            border-radius: 10px;
            padding: 15px;
            margin: 20px 0;
            text-align: center;
        }

        .my-id-label {
            font-size: 0.9em;
            color: #888;
            margin-bottom: 5px;
        }

        .my-id-value {
            font-size: 1.5em;
            color: #FF0055;
            font-family: 'Courier New', monospace;
            font-weight: bold;
        }

        .celebration {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 2000;
            text-align: center;
            pointer-events: none;
            display: none;
        }

        .celebration.active {
            display: block;
            animation: celebrationPop 1s ease-out;
        }

        @keyframes celebrationPop {
            0% { transform: translate(-50%, -50%) scale(0); opacity: 0; }
            50% { transform: translate(-50%, -50%) scale(1.2); opacity: 1; }
            100% { transform: translate(-50%, -50%) scale(1); opacity: 0; }
        }

        .celebration-text {
            font-size: 3em;
            color: #39FF14;
            text-shadow: 0 0 30px rgba(57, 255, 20, 1);
            font-weight: bold;
        }

        .share-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }

        .share-modal.active {
            display: flex;
        }

        .share-content {
            background: linear-gradient(135deg, #0B0B45 0%, #1a1a5e 100%);
            border: 2px solid #39FF14;
            border-radius: 20px;
            padding: 30px;
            max-width: 90%;
            max-height: 80%;
            overflow-y: auto;
            box-shadow: 0 0 50px rgba(57, 255, 20, 0.5);
        }

        .share-text {
            background: rgba(0, 0, 0, 0.5);
            border: 1px solid #39FF14;
            border-radius: 10px;
            padding: 15px;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
            font-size: 0.9em;
            line-height: 1.6;
            word-break: break-all;
        }

        .btn-copy {
            background: linear-gradient(135deg, #39FF14 0%, #2ECC71 100%);
            border-color: #39FF14;
            color: #0B0B45;
            width: 100%;
            margin-top: 15px;
        }

        .close-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            background: transparent;
            border: none;
            color: #39FF14;
            font-size: 2em;
            cursor: pointer;
            width: 40px;
            height: 40px;
            line-height: 40px;
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .logo {
                font-size: 2em;
            }
            
            .subtitle {
                font-size: 1em;
            }
            
            .btn {
                padding: 12px 30px;
                font-size: 1em;
            }
            
            .identity-name {
                font-size: 1.5em;
            }
        }

        /* 特效文字 */
        .glitch {
            position: relative;
            animation: glitch 2s infinite;
        }

        @keyframes glitch {
            0%, 100% { transform: translate(0); }
            20% { transform: translate(-2px, 2px); }
            40% { transform: translate(-2px, -2px); }
            60% { transform: translate(2px, 2px); }
            80% { transform: translate(2px, -2px); }
        }
    </style>
</head>
<body>
    <div class="grid-bg"></div>
    <div class="bg-animation" id="snowContainer"></div>

    <div class="container">
        <!-- 启动页面 -->
        <div class="start-screen" id="startScreen">
            <div class="logo glitch">🎄 高途赛博圣诞</div>
            <div class="subtitle">暖冬行动 · 代号 2077</div>
            <div class="status-text">
                ⚠️ 警告：检测到情绪温度过低<br>
                正在寻找暖冬特工...
            </div>
            <button class="btn" onclick="startDraw()">⚡ 觉醒我的赛博身份</button>
            <div class="reroll-info" id="rerollInfo"></div>
            <div class="reroll-info" id="playerIdInfo" style="margin-top: 10px;"></div>
        </div>

        <!-- 抽取动画页面 -->
        <div class="draw-screen" id="drawScreen">
            <div class="scan-line"></div>
            <div class="draw-text">正在扫描身份数据库...</div>
            <div class="identity-preview" id="identityPreview"></div>
        </div>

        <!-- 结果页面 -->
        <div class="result-screen" id="resultScreen">
            <div class="card">
                <div class="rarity-badge" id="rarityBadge"></div>
                <div class="identity-name" id="identityName"></div>
                <div class="identity-skill" id="identitySkill"></div>
            </div>

            <div class="mission-card">
                <div class="mission-title">📋 任务指令</div>
                <div class="mission-content" id="missionContent"></div>
                <div class="energy-reward" id="energyReward"></div>
            </div>

            <div class="action-buttons">
                <button class="btn btn-complete" onclick="completeMission()" id="completeBtn">✅ 确认完成任务</button>
                <button class="btn btn-share" onclick="showShare()">📤 分享我的特工执照</button>
                <button class="btn btn-secondary" onclick="reroll()" id="rerollBtn">🔄 重置系统</button>
                <button class="btn btn-secondary" onclick="showLeaderboard()">🏆 能量排行榜</button>
            </div>
        </div>

        <!-- 排行榜页面 -->
        <div class="leaderboard-screen" id="leaderboardScreen">
            <div class="leaderboard-header">
                <div class="leaderboard-title">🏆 能量排行榜</div>
                <div class="my-id-display">
                    <div class="my-id-label">我的特工ID</div>
                    <div class="my-id-value" id="myIdDisplay"></div>
                </div>
            </div>
            <div id="leaderboardList"></div>
            <div class="action-buttons">
                <button class="btn btn-secondary" onclick="backToGame()">← 返回游戏</button>
            </div>
        </div>
    </div>

    <!-- 庆祝动画 -->
    <div class="celebration" id="celebration">
        <div class="celebration-text">+能量获得！</div>
    </div>

    <!-- 分享弹窗 -->
    <div class="share-modal" id="shareModal">
        <div class="share-content">
            <button class="close-btn" onclick="closeShare()">×</button>
            <h2 style="color: #39FF14; margin-bottom: 20px;">📤 分享你的特工执照</h2>
            <div class="share-text" id="shareText"></div>
            <button class="btn btn-copy" onclick="copyShare()">📋 复制分享文案</button>
        </div>
    </div>

    <script>
        // 身份池数据
        const identities = {
            SSR: [
                { name: '时空圣诞老人', skill: '技能：在这个时间线直接发放双倍年终奖...的运气' },
                { name: '首席情绪架构师', skill: '技能：重构团队emo代码，一键部署快乐' },
                { name: '全栈愿望实现官', skill: '技能：后端处理压力，前端展示奇迹' }
            ],
            SR: [
                { name: '光速派送圣诞快递员', skill: '技能：DDL前必达，无视物理延迟' },
                { name: '银河雪花设计师', skill: '技能：将枯燥的数据渲染成浪漫雪景' },
                { name: '赛博驯鹿领航员', skill: '技能：在复杂的职场迷宫中永不迷路' },
                { name: 'AI情绪修复师', skill: '技能：精准识别并消除同事的"班味儿"' },
                { name: '跨维度祝福搬运工', skill: '技能：将i人的内心戏转化为e人的祝福语' }
            ],
            R: [
                { name: '数据雪橇驾驶员', skill: '技能：驾驭数据洪流，精准送达目标' },
                { name: '未来城市氛围点亮员', skill: '技能：一键点亮工区的节日氛围' },
                { name: '圣诞能量收集官', skill: '技能：收集散落的快乐能量碎片' },
                { name: '赛博铃铛调音师', skill: '技能：调谐团队协作的频率' },
                { name: '暖心模块安装技师', skill: '技能：为同事安装暖心补丁' },
                { name: '情绪能量加速器实习生', skill: '技能：加速团队情绪恢复速度' },
                { name: '星河庆典主持人', skill: '技能：主持跨部门庆典活动' },
                { name: '暗夜彩灯点亮专家', skill: '技能：在加班夜点亮希望之光' },
                { name: '冬夜反卷保障员', skill: '技能：保障团队准时下班权益' },
                { name: '团队士气加热官', skill: '技能：提升团队整体士气温度' }
            ],
            N: [
                { name: '平安夜秩序维护者', skill: '技能：维护办公室节日秩序' },
                { name: '雪景渲染算法优化师', skill: '技能：优化节日氛围渲染效率' },
                { name: '未来都市红丝带布置员', skill: '技能：布置工区节日装饰' },
                { name: '加班氛围驯化助理', skill: '技能：驯化过度加班氛围' },
                { name: '圣诞暖场体验官', skill: '技能：体验并优化暖场活动' },
                { name: '节日能量派送忍者', skill: '技能：悄无声息传递节日祝福' },
                { name: 'AI温度调和工程师', skill: '技能：调节团队工作温度' },
                { name: '数智化快乐生成器', skill: '技能：生成数字化快乐体验' },
                { name: '同事情绪舒缓顾问', skill: '技能：舒缓同事工作压力' },
                { name: '星际派对预热师', skill: '技能：预热团队派对氛围' },
                { name: '未来城市打工侠', skill: '技能：守护打工人权益' },
                { name: '空间动效点亮师', skill: '技能：点亮办公空间动效' }
            ]
        };

        // 任务池数据
        const missions = {
            Level1: [
                '今天夸奖一个同事，让TA获得 +10 温暖值',
                '给团队群发一个「圣诞祝福」贴纸',
                '给昨天帮助过你的人发一句"谢谢"',
                '夸自己一句，今天也要发光',
                '给最累的同事发一个暖心表情包',
                '桌面整理 1 分钟提升幸运值',
                '下午三点喝一杯水',
                '深呼吸 5 秒恢复精神能量',
                '给自己买杯奶茶',
                '随机夸一个同组伙伴'
            ],
            Level2: [
                '给组员发一个"今日好运buff"红包（哪怕只有1分钱）',
                '向团队推荐一个提高效率的 AI 工具',
                '拒绝无效内卷，今天准时下班一次',
                '给同事发送定制的圣诞头像框/表情包',
                '分享今天学到的一个冷知识',
                '帮同事解决一个小bug或问题',
                '在群里发一句鼓励大家的话',
                '给你平时不常说话的同事送一句祝福',
                '给领导发一句"圣诞快乐"，打破次元壁',
                '邀请同事一起"摸鱼"去楼下便利店'
            ],
            Level3: [
                '帮别人倒一杯热水并送到工位',
                '用 AI 生成一句藏头诗祝福并发送给特定人',
                '拍摄一张工区最有圣诞氛围的照片分享到朋友圈',
                '给团队每个人都准备一个小零食',
                '组织一次 5 分钟的工位伸展操',
                '帮 review 文档/代码 5 分钟并给出真诚赞美',
                '分享你的"赛博身份"到大群，并寻找同类',
                '面对面微笑对 3 位同事说"圣诞快乐"',
                '假装自己是圣诞老人，匿名送出一份小礼物',
                '制定明年的一个Flag并公开立誓'
            ]
        };

        let currentIdentity = null;
        let currentMission = null;
        let currentRarity = null;
        let playerId = null;
        let missionCompleted = false;

        // 生成或获取玩家ID
        function getOrCreatePlayerId() {
            let id = localStorage.getItem('playerId');
            if (!id) {
                // 生成一个6位随机ID
                id = 'GT' + Math.random().toString(36).substr(2, 6).toUpperCase();
                localStorage.setItem('playerId', id);
            }
            return id;
        }

        // 获取玩家数据
        function getPlayerData() {
            const id = getOrCreatePlayerId();
            const stored = localStorage.getItem('playerData_' + id);
            return stored ? JSON.parse(stored) : { id: id, energy: 0, completedMissions: [] };
        }

        // 保存玩家数据
        function savePlayerData(data) {
            localStorage.setItem('playerData_' + data.id, JSON.stringify(data));
            // 更新排行榜数据
            updateLeaderboardData(data);
        }

        // 更新排行榜数据（存储所有玩家）
        function updateLeaderboardData(playerData) {
            let leaderboard = JSON.parse(localStorage.getItem('leaderboard') || '[]');
            const index = leaderboard.findIndex(p => p.id === playerData.id);
            if (index >= 0) {
                leaderboard[index] = playerData;
            } else {
                leaderboard.push(playerData);
            }
            // 按能量排序
            leaderboard.sort((a, b) => b.energy - a.energy);
            localStorage.setItem('leaderboard', JSON.stringify(leaderboard));
        }

        // 获取排行榜数据（仅展示能量最高的前 25 个 ID）
        function getLeaderboardData() {
            const data = JSON.parse(localStorage.getItem('leaderboard') || '[]');
            // 此处 data 已在 updateLeaderboardData 中按能量倒序排好
            return data.slice(0, 25);
        }

        // 初始化雪花
        function initSnow() {
            const container = document.getElementById('snowContainer');
            const symbols = ['❄', '✦', '✧', '✩', '✪'];
            for (let i = 0; i < 30; i++) {
                const snowflake = document.createElement('div');
                snowflake.className = 'snowflake';
                snowflake.textContent = symbols[Math.floor(Math.random() * symbols.length)];
                snowflake.style.left = Math.random() * 100 + '%';
                snowflake.style.animationDuration = (Math.random() * 3 + 2) + 's';
                snowflake.style.animationDelay = Math.random() * 2 + 's';
                container.appendChild(snowflake);
            }
        }

        // 检查重新抽取次数
        function checkRerollLimit() {
            const today = new Date().toDateString();
            const stored = localStorage.getItem('rerollData');
            let rerollData = stored ? JSON.parse(stored) : { date: today, count: 0 };
            
            if (rerollData.date !== today) {
                rerollData = { date: today, count: 0 };
            }
            
            localStorage.setItem('rerollData', JSON.stringify(rerollData));
            return rerollData;
        }

        // 更新重新抽取信息
        function updateRerollInfo() {
            const rerollData = checkRerollLimit();
            const remaining = 3 - rerollData.count;
            const infoEl = document.getElementById('rerollInfo');
            if (remaining > 0) {
                infoEl.textContent = `今日剩余重置次数：${remaining}/3`;
            } else {
                infoEl.textContent = '今日重置次数已用完，明天再来吧！';
                infoEl.style.color = '#FF0055';
            }
        }

        // 开始抽取
        function startDraw() {
            const startScreen = document.getElementById('startScreen');
            const drawScreen = document.getElementById('drawScreen');
            const resultScreen = document.getElementById('resultScreen');
            
            startScreen.style.display = 'none';
            drawScreen.classList.add('active');
            
            // 检查时间彩蛋（12:25分必出SSR）
            const now = new Date();
            const isSpecialTime = now.getHours() === 12 && now.getMinutes() === 25;
            
            // 抽取身份
            setTimeout(() => {
                drawIdentity(isSpecialTime);
            }, 1500);
            
            // 显示抽取动画
            const previewEl = document.getElementById('identityPreview');
            const allIdentities = [...identities.SSR, ...identities.SR, ...identities.R, ...identities.N];
            let index = 0;
            const interval = setInterval(() => {
                const random = allIdentities[Math.floor(Math.random() * allIdentities.length)];
                previewEl.textContent = random.name;
                index++;
                if (index > 20) {
                    clearInterval(interval);
                }
            }, 100);
        }

        // 抽取身份
        function drawIdentity(forceSSR = false) {
            let rarity, identity;
            
            if (forceSSR) {
                // 彩蛋：12:25分必出SSR
                rarity = 'SSR';
                identity = identities.SSR[Math.floor(Math.random() * identities.SSR.length)];
            } else {
                // 正常概率抽取
                const rand = Math.random();
                if (rand < 0.05) {
                    rarity = 'SSR';
                    identity = identities.SSR[Math.floor(Math.random() * identities.SSR.length)];
                } else if (rand < 0.20) {
                    rarity = 'SR';
                    identity = identities.SR[Math.floor(Math.random() * identities.SR.length)];
                } else if (rand < 0.50) {
                    rarity = 'R';
                    identity = identities.R[Math.floor(Math.random() * identities.R.length)];
                } else {
                    rarity = 'N';
                    identity = identities.N[Math.floor(Math.random() * identities.N.length)];
                }
            }
            
            currentIdentity = identity;
            currentRarity = rarity;
            
            // 抽取任务
            const missionLevel = rarity === 'SSR' || rarity === 'SR' ? 'Level3' : 
                                rarity === 'R' ? 'Level2' : 'Level1';
            const missionPool = missions[missionLevel];
            currentMission = {
                content: missionPool[Math.floor(Math.random() * missionPool.length)],
                level: missionLevel,
                energy: missionLevel === 'Level1' ? 100 : missionLevel === 'Level2' ? 200 : 500
            };
            
            // 显示结果
            setTimeout(() => {
                showResult();
            }, 500);
        }

        // 显示结果
        function showResult() {
            const drawScreen = document.getElementById('drawScreen');
            const resultScreen = document.getElementById('resultScreen');
            
            drawScreen.classList.remove('active');
            resultScreen.classList.add('active');
            
            // 设置身份信息
            document.getElementById('rarityBadge').textContent = currentRarity;
            document.getElementById('rarityBadge').className = 'rarity-badge rarity-' + currentRarity.toLowerCase();
            document.getElementById('identityName').textContent = currentIdentity.name;
            document.getElementById('identitySkill').textContent = currentIdentity.skill;
            
            // 设置任务信息
            document.getElementById('missionContent').textContent = currentMission.content;
            document.getElementById('energyReward').textContent = `⚡ 完成奖励：+${currentMission.energy} 暖心能量`;
            
            // 重置任务完成状态
            missionCompleted = false;
            const missionCard = document.querySelector('.mission-card');
            missionCard.classList.remove('mission-completed');
            const completeBtn = document.getElementById('completeBtn');
            completeBtn.disabled = false;
            completeBtn.textContent = '✅ 确认完成任务';

            updateRerollInfo();
        }

        // 生成特工快照
        function generateSnapshot() {
            const canvas = document.createElement('canvas');
            canvas.width = 600;
            canvas.height = 800;
            const ctx = canvas.getContext('2d');
            
            // 背景渐变
            const bgGradient = ctx.createLinearGradient(0, 0, 600, 800);
            bgGradient.addColorStop(0, '#0B0B45');
            bgGradient.addColorStop(0.5, '#1a1a5e');
            bgGradient.addColorStop(1, '#0B0B45');
            ctx.fillStyle = bgGradient;
            ctx.fillRect(0, 0, 600, 800);
            
            // 网格背景
            ctx.strokeStyle = 'rgba(57, 255, 20, 0.2)';
            ctx.lineWidth = 1;
            for (let i = 0; i < 600; i += 30) {
                ctx.beginPath();
                ctx.moveTo(i, 0);
                ctx.lineTo(i, 800);
                ctx.stroke();
            }
            for (let i = 0; i < 800; i += 30) {
                ctx.beginPath();
                ctx.moveTo(0, i);
                ctx.lineTo(600, i);
                ctx.stroke();
            }
            
            // 标题
            ctx.fillStyle = '#39FF14';
            ctx.font = 'bold 36px "Microsoft YaHei", Arial, sans-serif';
            ctx.textAlign = 'center';
            ctx.textBaseline = 'top';
            ctx.fillText('🎄 高途赛博圣诞', 300, 40);
            ctx.font = '24px "Microsoft YaHei", Arial, sans-serif';
            ctx.fillText('暖冬行动 · 特工快照', 300, 85);
            
            // 稀有度标签背景
            const rarityColors = {
                'SSR': '#FFD700',
                'SR': '#FF0055',
                'R': '#39FF14',
                'N': '#888'
            };
            const rarityBg = rarityColors[currentRarity] || '#888';
            ctx.fillStyle = rarityBg + '40';
            ctx.fillRect(200, 120, 200, 40);
            ctx.strokeStyle = rarityBg;
            ctx.lineWidth = 2;
            ctx.strokeRect(200, 120, 200, 40);
            ctx.fillStyle = rarityBg;
            ctx.font = 'bold 28px "Microsoft YaHei", Arial, sans-serif';
            ctx.fillText(currentRarity, 300, 130);
            
            // 身份名称
            ctx.fillStyle = '#39FF14';
            ctx.font = 'bold 32px "Microsoft YaHei", Arial, sans-serif';
            ctx.fillText(currentIdentity.name, 300, 190);
            
            // 技能描述
            ctx.fillStyle = '#ccc';
            ctx.font = '18px "Microsoft YaHei", Arial, sans-serif';
            const skillLines = wrapText(ctx, currentIdentity.skill, 500);
            let yPos = 250;
            skillLines.forEach(line => {
                ctx.fillText(line, 300, yPos);
                yPos += 28;
            });
            
            // 分割线
            ctx.strokeStyle = '#FF0055';
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.moveTo(50, 330);
            ctx.lineTo(550, 330);
            ctx.stroke();
            
            // 任务标题
            ctx.fillStyle = '#FF0055';
            ctx.font = 'bold 24px "Microsoft YaHei", Arial, sans-serif';
            ctx.fillText('📋 任务指令', 300, 370);
            
            // 任务内容
            ctx.fillStyle = '#fff';
            ctx.font = '20px "Microsoft YaHei", Arial, sans-serif';
            const missionLines = wrapText(ctx, currentMission.content, 500);
            yPos = 420;
            missionLines.forEach(line => {
                ctx.fillText(line, 300, yPos);
                yPos += 32;
            });
            
            // 能量奖励
            ctx.fillStyle = '#39FF14';
            ctx.font = 'bold 28px "Microsoft YaHei", Arial, sans-serif';
            ctx.fillText(`⚡ +${currentMission.energy} 暖心能量`, 300, 580);
            
            // 玩家ID和能量
            const playerData = getPlayerData();
            ctx.fillStyle = '#888';
            ctx.font = '16px "Courier New", monospace';
            ctx.fillText(`ID: ${playerId}`, 300, 720);
            ctx.fillText(`总能量: ${playerData.energy}`, 300, 750);
            
            // 装饰边框
            ctx.strokeStyle = '#39FF14';
            ctx.lineWidth = 4;
            ctx.strokeRect(20, 20, 560, 760);
            
            // 显示画布
            const preview = document.getElementById('snapshotPreview');
            preview.innerHTML = '';
            canvas.className = 'snapshot-canvas';
            preview.appendChild(canvas);
            
            // 添加下载按钮
            const downloadBtn = document.createElement('button');
            downloadBtn.className = 'btn btn-download';
            downloadBtn.textContent = '📥 下载特工快照';
            downloadBtn.onclick = () => {
                const link = document.createElement('a');
                link.download = `特工快照_${currentIdentity.name}_${Date.now()}.png`;
                link.href = canvas.toDataURL('image/png');
                link.click();
            };
            preview.appendChild(downloadBtn);
        }

        // 文本换行辅助函数
        function wrapText(ctx, text, maxWidth) {
            const lines = [];
            let currentLine = '';
            
            // 按字符分割（处理中文）
            const chars = text.split('');
            
            for (let i = 0; i < chars.length; i++) {
                const testLine = currentLine + chars[i];
                const metrics = ctx.measureText(testLine);
                
                if (metrics.width > maxWidth && currentLine !== '') {
                    lines.push(currentLine);
                    currentLine = chars[i];
                } else {
                    currentLine = testLine;
                }
            }
            
            if (currentLine) {
                lines.push(currentLine);
            }
            
            return lines.length > 0 ? lines : [text];
        }

        // 确认完成任务
        function completeMission() {
            if (missionCompleted) {
                alert('任务已完成！');
                return;
            }
            
            const playerData = getPlayerData();
            const missionId = currentIdentity.name + '_' + currentMission.content;
            
            // 检查是否已完成过此任务
            if (playerData.completedMissions.includes(missionId)) {
                alert('此任务已完成，无法重复获得能量！');
                return;
            }
            
            // 添加能量
            playerData.energy += currentMission.energy;
            playerData.completedMissions.push(missionId);
            savePlayerData(playerData);
            
            // 更新UI
            missionCompleted = true;
            const missionCard = document.querySelector('.mission-card');
            missionCard.classList.add('mission-completed');
            const completeBtn = document.getElementById('completeBtn');
            completeBtn.disabled = true;
            completeBtn.textContent = '✓ 任务已完成';
            
            // 显示庆祝动画
            showCelebration(currentMission.energy);
            
            alert(`🎉 任务完成！获得 +${currentMission.energy} 暖心能量！\n当前总能量：${playerData.energy}`);
        }

        // 显示庆祝动画
        function showCelebration(energy) {
            const celebration = document.getElementById('celebration');
            const text = celebration.querySelector('.celebration-text');
            text.textContent = `+${energy} 能量获得！`;
            celebration.classList.add('active');
            setTimeout(() => {
                celebration.classList.remove('active');
            }, 1000);
        }

        // 显示排行榜
        function showLeaderboard() {
            const resultScreen = document.getElementById('resultScreen');
            const leaderboardScreen = document.getElementById('leaderboardScreen');
            
            resultScreen.classList.remove('active');
            leaderboardScreen.classList.add('active');
            
            // 显示我的ID
            document.getElementById('myIdDisplay').textContent = playerId;
            
            // 加载排行榜数据
            const leaderboard = getLeaderboardData();
            const listEl = document.getElementById('leaderboardList');
            listEl.innerHTML = '';
            
            if (leaderboard.length === 0) {
                listEl.innerHTML = '<div style="text-align: center; color: #888; padding: 40px;">暂无排行榜数据</div>';
                return;
            }
            
            leaderboard.forEach((player, index) => {
                const item = document.createElement('div');
                item.className = 'player-info' + (index < 3 ? ' top3' : '');
                
                let rankBadge = '';
                if (index === 0) {
                    rankBadge = '<span class="rank-badge rank-1">🥇</span>';
                } else if (index === 1) {
                    rankBadge = '<span class="rank-badge rank-2">🥈</span>';
                } else if (index === 2) {
                    rankBadge = '<span class="rank-badge rank-3">🥉</span>';
                } else {
                    rankBadge = `<span class="rank-badge">#${index + 1}</span>`;
                }
                
                item.innerHTML = `
                    ${rankBadge}
                    <div class="player-details">
                        <div class="player-id">${player.id}</div>
                    </div>
                    <div class="player-energy">⚡ ${player.energy}</div>
                `;
                
                listEl.appendChild(item);
            });
        }

        // 返回游戏
        function backToGame() {
            const leaderboardScreen = document.getElementById('leaderboardScreen');
            const resultScreen = document.getElementById('resultScreen');
            
            leaderboardScreen.classList.remove('active');
            resultScreen.classList.add('active');
        }

        // 重新抽取
        function reroll() {
            const rerollData = checkRerollLimit();
            if (rerollData.count >= 3) {
                alert('今日重置次数已用完，明天再来吧！');
                return;
            }
            
            if (confirm('确定要重置系统吗？这将消耗一次重置机会。')) {
                rerollData.count++;
                localStorage.setItem('rerollData', JSON.stringify(rerollData));
                
                const resultScreen = document.getElementById('resultScreen');
                const drawScreen = document.getElementById('drawScreen');
                
                resultScreen.classList.remove('active');
                drawScreen.classList.add('active');
                
                setTimeout(() => {
                    drawIdentity();
                }, 1500);
            }
        }

        // 显示分享
        function showShare() {
            const modal = document.getElementById('shareModal');
            const shareText = document.getElementById('shareText');
            
            const playerData = getPlayerData();
            const completedStatus = missionCompleted ? '✅ 已完成' : '⏳ 进行中';
            
            const shareContent = `🎄 高途赛博圣诞·暖冬行动 🎄

✨ 我的赛博身份：${currentIdentity.name}
🏷️ 稀有度：${currentRarity}
💡 ${currentIdentity.skill}

📋 我的任务：${currentMission.content}
⚡ 完成奖励：+${currentMission.energy} 暖心能量
📊 任务状态：${completedStatus}

🎯 我的特工ID：${playerId}
⚡ 当前总能量：${playerData.energy}

🎯 2077年，高途未来城遭遇「情绪寒流」
🔥 每一位伙伴都是「暖冬特工」
💪 让我们一起收集暖心能量，点亮数据圣诞树！

快来抽取你的赛博身份吧！
🔗 ${window.location.href}`;
            
            shareText.textContent = shareContent;
            modal.classList.add('active');
        }

        // 关闭分享
        function closeShare() {
            document.getElementById('shareModal').classList.remove('active');
        }

        // 复制分享
        function copyShare() {
            const shareText = document.getElementById('shareText').textContent;
            navigator.clipboard.writeText(shareText).then(() => {
                alert('✅ 分享文案已复制到剪贴板！');
            }).catch(() => {
                // 降级方案
                const textarea = document.createElement('textarea');
                textarea.value = shareText;
                document.body.appendChild(textarea);
                textarea.select();
                document.execCommand('copy');
                document.body.removeChild(textarea);
                alert('✅ 分享文案已复制到剪贴板！');
            });
        }

        // 初始化
        window.onload = function() {
            initSnow();
            updateRerollInfo();
            // 初始化玩家ID
            playerId = getOrCreatePlayerId();
            // 确保玩家数据存在
            const playerData = getPlayerData();
            savePlayerData(playerData);
            // 显示玩家ID
            const playerIdInfo = document.getElementById('playerIdInfo');
            if (playerIdInfo) {
                playerIdInfo.textContent = `特工ID: ${playerId} | 当前能量: ${playerData.energy}`;
                playerIdInfo.style.color = '#39FF14';
            }
        };
    </script>
</body>
</html>
