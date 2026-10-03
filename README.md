
.brand-text h1 {

    margin: 0;

    font-size: 19px;

    font-weight: 900;

}

.brand-text p {

    margin: 3px 0 0;

    font-size: 11px;

    color: #9b8d9f;

}

.header-bunny {

    font-size: 31px;

}


/* ==================================================
   今日粉絲天數
================================================== */

.day-card {

    position: relative;

    overflow: hidden;

    padding:
        19px
        19px
        18px;

    border-radius: 26px;

    background:
        linear-gradient(
            135deg,
            rgba(255,255,255,.95),
            rgba(255,238,247,.95)
        );

    box-shadow:
        0 12px 30px
        rgba(180,140,175,.16);

    border:
        1px solid
        rgba(255,255,255,.9);

}

.day-card::before {

    content: "";

    position: absolute;

    width: 130px;

    height: 130px;

    right: -45px;

    top: -50px;

    border-radius: 50%;

    background: #ffd5e6;

    opacity: .55;

}

.day-card::after {

    content: "";

    position: absolute;

    width: 90px;

    height: 90px;

    left: -45px;

    bottom: -45px;

    border-radius: 50%;

    background: #e5d9ff;

    opacity: .55;

}

.day-card-content {

    position: relative;

    z-index: 2;

}

.day-label {

    font-size: 12px;

    color: #94768a;

}

.day-number {

    margin-top: 2px;

    font-size: 47px;

    line-height: 1;

    font-weight: 900;

    letter-spacing: -2px;

    background:
        linear-gradient(
            135deg,
            #ed75a7,
            #9e70df
        );

    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;

}

.day-description {

    margin-top: 4px;

    font-size: 13px;

    font-weight: 700;

    color: #655768;

}

.start-date {

    margin-top: 7px;

    font-size: 11px;

    color: #a092a2;

    display: flex;

    align-items: center;

    gap: 5px;

}

.inline-icon {

    width: 18px;

    height: 18px;

    border-radius: 6px;

    object-fit: cover;

    vertical-align: middle;

    display: inline-block;

    box-shadow: 0 2px 4px rgba(0,0,0,0.1);

}


/* ==================================================
   下一個里程碑
================================================== */

.next-box {

    margin-top: 10px;

    padding:
        12px
        14px;

    border-radius: 17px;

    display: flex;

    align-items: center;

    justify-content: space-between;

    background:
        linear-gradient(
            135deg,
            #fff0f6,
            #f3edff
        );

}

.next-left {

    display: flex;

    align-items: center;

    gap: 9px;

}

.next-icon {

    width: 34px;

    height: 34px;

    border-radius: 12px;

    display: flex;

    align-items: center;

    justify-content: center;

    background: rgba(255,255,255,.8);

    font-size: 18px;

}

.next-label {

    font-size: 10px;

    color: #9d879a;

}

.next-title {

    margin-top: 2px;

    font-size: 14px;

    font-weight: 900;

    color: #a56c96;

}

.next-right {

    text-align: right;

}

.next-days {

    font-size: 17px;

    font-weight: 900;

    color: #b16fa2;

}

.next-days-label {

    font-size: 9px;

    color: #a193a4;

}


/* ==================================================
   月曆卡片
================================================== */

.calendar-card {

    margin-top: 12px;

    padding: 16px 13px 14px;

    border-radius: 26px;

    background:
        rgba(255,255,255,.92);

    box-shadow:
        0 12px 30px
        rgba(160,130,170,.13);

    border:
        1px solid
        rgba(255,255,255,.95);

}


/* ==================================================
   月份標題
================================================== */

.calendar-header {

    display: flex;

    align-items: center;

    justify-content: space-between;

    margin-bottom: 13px;

}

.month-title {

    text-align: center;

}

.month-main {

    font-size: 20px;

    font-weight: 900;

    color: #554957;

}

.month-sub {

    margin-top: 2px;

    font-size: 10px;

    color: #aaa0ad;

}

.month-btn {

    width: 38px;

    height: 38px;

    border: none;

    border-radius: 13px;

    background: #f8f1f8;

    color: #806f82;

    font-size: 22px;

    line-height: 1;

    cursor: pointer;

}

.month-btn:active {

    transform: scale(.93);

    background: #f1e7f2;

}


/* ==================================================
   星期
================================================== */

.weekdays {

    display: grid;

    grid-template-columns:
        repeat(7, 1fr);

    gap: 3px;

    margin-bottom: 4px;

}

.weekday {

    text-align: center;

    font-size: 10px;

    color: #a79ba9;

    padding-bottom: 3px;

}


/* ==================================================
   月曆
================================================== */

.calendar {

    display: grid;

    grid-template-columns:
        repeat(7, 1fr);

    gap: 4px;

}

.day {

    min-height: 54px;

    border-radius: 14px;

    position: relative;

    display: flex;

    flex-direction: column;

    align-items: center;

    justify-content: center;

    font-size: 13px;

    color: #554a58;

    transition:
        transform .15s ease,
        background .15s ease;

    cursor: pointer;

}

.day:active {

    transform: scale(.94);

}

.day.empty {

    visibility: hidden;

}

.day.future {

    color: #cfc7d1;

}


/* ==================================================
   今天
================================================== */

.day.today {

    background: #fff0f6;

    box-shadow:
        inset 0 0 0 2px
        #f3a9c9;

    font-weight: 900;

}

.day.today::before {

    content: "今天";

    position: absolute;

    top: 3px;

    font-size: 7px;

    color: #cf739c;

}


/* ==================================================
   粉絲日與自訂紀念日樣式
================================================== */

.fan-day-number {

    margin-top: 2px;

    font-size: 8px;

    color: #aaa0ad;

    text-align: center;

    line-height: 1.1;

    word-break: break-all;

    max-width: 90%;

}

.day.future .fan-day-number {

    color: #d6d0d7;

}

.day.custom-event {

    background: linear-gradient(135deg, #e3f2fd, #f3e5f5);

    box-shadow: inset 0 0 0 2px #90caf9;

    font-weight: 900;

}

.day.custom-event .fan-day-number {

    color: #42a5f5;

    font-weight: 900;

}


/* ==================================================
   50天里程碑
================================================== */

.day.milestone {

    background:
        linear-gradient(
            135deg,
            #ffe0ec,
            #eee3ff
        );

    font-weight: 900;

}

.day.milestone .fan-day-number {

    color: #b56e98;

    font-weight: 900;

}

.day.milestone::after {

    content: "♥";

    position: absolute;

    right: 4px;

    top: 3px;

    font-size: 8px;

    color: #d48caf;

}


/* ==================================================
   週年與生日
================================================== */

.day.anniversary,
.day.birthday {

    background:
        linear-gradient(
            135deg,
            #ffe8a7,
            #ffd2e5
        );

    box-shadow:
        inset 0 0 0 2px
        #edb15e;

    font-weight: 900;

}

.day.anniversary .fan-day-number,
.day.birthday .fan-day-number {

    color: #a35e6f;

    font-weight: 900;

}


/* ==================================================
   圖例
================================================== */

.legend {

    display: flex;

    justify-content: center;

    gap: 13px;

    margin-top: 13px;

    font-size: 9px;

    color: #9b909f;

}

.legend-item {

    display: flex;

    align-items: center;

    gap: 4px;

}

.legend-dot {

    width: 9px;

    height: 9px;

    border-radius: 4px;

}

.legend-today {

    background: #fff0f6;

    border:
        1px solid
        #f3a9c9;

}

.legend-milestone {

    background:
        linear-gradient(
            135deg,
            #ffe0ec,
            #eee3ff
        );

}

.legend-year {

    background:
        linear-gradient(
            135deg,
            #ffe8a7,
            #ffd2e5
        );

}

.legend-custom {

    background: linear-gradient(135deg, #e3f2fd, #f3e5f5);

    border: 1px solid #90caf9;

}


/* ==================================================
   日期資訊
================================================== */

.selected-card {

    margin-top: 12px;

    padding: 15px;

    border-radius: 21px;

    background:
        linear-gradient(
            135deg,
            #fff7fb,
            #f5f0ff
        );

    text-align: center;

}

.selected-date {

    font-size: 11px;

    color: #9b8e9e;

}

.selected-main {

    margin-top: 4px;

    font-size: 17px;

    font-weight: 900;

    color: #76566f;

}

.selected-sub {

    margin-top: 4px;

    font-size: 11px;

    color: #9a8c9d;

}

.edit-event-btn {

    margin-top: 8px;

    padding: 5px 14px;

    border-radius: 12px;

    border: none;

    background: #ed75a7;

    color: white;

    font-size: 11px;

    font-weight: 700;

    cursor: pointer;

    box-shadow: 0 3px 8px rgba(237,117,167,0.3);

}

.edit-event-btn:active {

    transform: scale(0.95);

}


/* ==================================================
   里程碑小卡
================================================== */

.mini-milestones {

    display: grid;

    grid-template-columns:
        repeat(3, 1fr);

    gap: 7px;

    margin-top: 12px;

}

.mini-item {

    padding: 11px 5px;

    text-align: center;

    border-radius: 15px;

    background: #faf7fb;

}

.mini-icon {

    font-size: 17px;

}

.mini-number {

    margin-top: 2px;

    font-size: 12px;

    font-weight: 900;

    color: #ae709e;

}

.mini-label {

    margin-top: 2px;

    font-size: 8px;

    color: #a49aa7;

}


/* ==================================================
   新增/編輯紀念日 彈出視窗 (Modal)
================================================== */

.modal-overlay {

    position: fixed;

    top: 0; left: 0; right: 0; bottom: 0;

    background: rgba(0,0,0,0.4);

    display: flex;

    align-items: center;

    justify-content: center;

    z-index: 1000;

    opacity: 0;

    pointer-events: none;

    transition: opacity 0.2s ease;

}

.modal-overlay.active {

    opacity: 1;

    pointer-events: auto;

}

.modal {

    background: #ffffff;

    width: 88%;

    max-width: 380px;

    border-radius: 24px;

    padding: 20px;

    box-shadow: 0 10px 30px rgba(0,0,0,0.15);

    transform: scale(0.9);

    transition: transform 0.2s ease;

}

.modal-overlay.active .modal {

    transform: scale(1);

}

.modal-title {

    font-size: 16px;

    font-weight: 900;

    color: #554957;

    margin-bottom: 12px;

    text-align: center;

}

.modal-input-group {

    margin-bottom: 12px;

    text-align: left;

}

.modal-input-group label {

    font-size: 11px;

    color: #94768a;

    display: block;

    margin-bottom: 4px;

}

.modal-input {

    width: 100%;

    padding: 10px 12px;

    border-radius: 12px;

    border: 1px solid #e2d9e5;

    font-size: 13px;

    outline: none;

}

.modal-input:focus {

    border-color: #ed75a7;

}

.emoji-selector {

    display: flex;

    gap: 8px;

    overflow-x: auto;

    padding: 4px 0;

}

.emoji-option {

    font-size: 20px;

    padding: 6px;

    border-radius: 10px;

    cursor: pointer;

    background: #f8f1f8;

    border: 1px solid transparent;

}

.emoji-option.selected {

    background: #ffe0ec;

    border-color: #ed75a7;

}

.modal-buttons {

    display: flex;

    gap: 8px;

    margin-top: 18px;

}

.btn-modal {

    flex: 1;

    padding: 10px;

    border-radius: 12px;

    border: none;

    font-size: 12px;

    font-weight: 700;

    cursor: pointer;

}

.btn-primary {

    background: #ed75a7;

    color: white;

}

.btn-danger {

    background: #ff6b6b;

    color: white;

}

.btn-secondary {

    background: #efeaf1;

    color: #655768;

}


/* ==================================================
   底部
================================================== */

.footer {

    padding: 18px 0 0;

    text-align: center;

    color: #aaa0ad;

    font-size: 10px;

    display: flex;

    flex-direction: column;

    align-items: center;

    gap: 4px;

}

.footer-brand {

    display: flex;

    align-items: center;

    justify-content: center;

    gap: 5px;

}

.footer strong {

    color: #b2779e;

}


/* ==================================================
   飄愛心
================================================== */

.heart {

    position: fixed;

    pointer-events: none;

    z-index: 100;

    animation:

        floatUp 4s linear forwards;

}

@keyframes floatUp {

    0% {

        transform:

            translateY(0)

            scale(.8);

        opacity: 0;

    }

    15% {

        opacity: 1;

    }

    100% {

        transform:

            translateY(-180px)

            scale(1.25);

        opacity: 0;

    }

}


/* ==================================================
   iPhone 小螢幕
================================================== */

@media (max-width: 370px) {

    .app {

        padding-left: 10px;

        padding-right: 10px;

    }

    .day {

        min-height: 48px;

        border-radius: 12px;

    }

    .day-number {

        font-size: 43px;

    }

    .calendar-card {

        padding-left: 9px;

        padding-right: 9px;

    }

}


/* ==================================================
   橫向／大螢幕
================================================== */

@media (min-width: 600px) {

    body {

        padding-top: 20px;

    }

    .app {

        max-width: 560px;

    }

}

</style>

</head>


<body>


<div class="app">

    <!-- 隱藏的檔案選擇器 -->
    <input type="file" id="imageUploader" accept="image/*" style="display: none;">

    <!-- =========================================
         HEADER
    ========================================== -->

    <header class="header">

        <div class="brand">

            <div class="logo-container" onclick="triggerImageUpload()" title="點擊換照片">
                <div class="logo">
                    <img id="doubaoImg" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=300&q=80" alt="豆包">
                </div>
                <div class="camera-badge">📷</div>
            </div>

            <div class="brand-text">

                <h1>
                    豆包 × 兔飽飽
                </h1>

                <p>
                    我們一起走過的每一天 💗
                </p>

            </div>

        </div>

        <div class="header-bunny">
            🐰
        </div>

    </header>


    <!-- =========================================
         粉絲天數
    ========================================== -->

    <section class="day-card">

        <div class="day-card-content">

            <div class="day-label">
                🐰 兔飽飽粉絲日誌
            </div>

            <div
                class="day-number"
                id="fanDay">

                0

            </div>

            <div class="day-description">

                成為兔飽飽天數💕

            </div>

            <div class="start-date">

                <img id="inlineImg1" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=300&q=80" alt="豆包" class="inline-icon"> 始於 2026.08.05

            </div>

        </div>

    </section>


    <!-- =========================================
         下一個里程碑
    ========================================== -->

    <section class="next-box">

        <div class="next-left">