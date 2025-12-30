<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>幼儿拼音学习 - 声母与韵母</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f9f9f9;
            font-family: "Microsoft YaHei", sans-serif;
        }
        .pinyin-card {
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            padding: 1.5rem;
            text-align: center;
            margin-bottom: 1.5rem;
        }
        .pinyin-card:hover {
            transform: translateY(-5px);
        }
        .pinyin-large {
            font-size: 4rem;
            font-weight: bold;
            color: #333;
        }
        .pinyin-sound {
            font-size: 1.2rem;
            color: #666;
        }
        .video-container {
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            padding: 1rem;
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>
    <div class="container py-5">
        <h1 class="text-center mb-5">🎈 幼儿拼音学习乐园</h1>

        <!-- 视频区域 -->
        <div class="video-container">
            <h3 class="text-center mb-3">拼音儿歌视频</h3>
            <div class="ratio ratio-16x9">
                <!-- 这里可以换成你的视频链接 -->
                <video controls>
                    <source src="pinyin_song.mp4" type="video/mp4">
                    你的浏览器不支持 HTML5 视频播放，请升级浏览器。
                </video>
            </div>
        </div>

        <!-- 拼音卡片区域 -->
        <h3 class="text-center mb-4">声母卡片</h3>
        <div class="row">
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">b</div>
                    <div class="pinyin-sound">播 (bō)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">p</div>
                    <div class="pinyin-sound">坡 (pō)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">m</div>
                    <div class="pinyin-sound">摸 (mō)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">f</div>
                    <div class="pinyin-sound">佛 (fó)</div>
                </div>
            </div>
        </div>

        <h3 class="text-center my-4">韵母卡片</h3>
        <div class="row">
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">a</div>
                    <div class="pinyin-sound">啊 (ā)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">o</div>
                    <div class="pinyin-sound">喔 (ō)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">e</div>
                    <div class="pinyin-sound">鹅 (ē)</div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="pinyin-card">
                    <div class="pinyin-large">i</div>
                    <div class="pinyin-sound">衣 (ī)</div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
