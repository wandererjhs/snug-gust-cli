# snug-gust-cli

Turning coffee into commits since 2014.

日常脚本的集中地

## 用法

```bash
cat data.txt | go run main.go
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/snug-gust-cli.git
cd snug-gust-cli
go build ./...
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
