# qbitorrent-auto-reflush
使用 qb 的 api 自动刷新种子，解决 unresigered torrent


# 安装依赖
```bash
pip3 install qbittorrentapi
```

# 加入 crontab

```bash
*/1 * * * * python3.8 /root/qbit-unresigered-torrent-fix.py 
```
