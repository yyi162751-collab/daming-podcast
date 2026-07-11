# 大明有料 - 播客托管

GitHub Pages 播客托管仓库，用于小宇宙等播客平台 RSS 订阅。

## 结构

```
podcast-hosting/
├── index.html        # 播客介绍页（可在线收听）
├── podcast.xml       # RSS Feed（小宇宙订阅地址）
├── audio/            # 播客音频文件
│   └── ep001-*.mp3
├── publish_podcast.py # 自动发布脚本
└── README.md
```

## 使用

### 发布新单集
```bash
python3 publish_podcast.py "音频文件.mp3" "EP002 - 标题" "单集描述"
```

### RSS 订阅地址
```
https://yyi162751-collab.github.io/daming-podcast/podcast.xml
```

## 配置

GitHub Pages 开启后，小宇宙会自动同步新单集。
