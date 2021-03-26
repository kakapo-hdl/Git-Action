### 关于Git的代理
- 代理（proxy）
```
配置代理
git config --add remote.origin.proxy "http://127.0.0.1:port"
//重点
git config --global remote.origin.proxy http://127.0.0.1:10809
git config --global http.proxy "https://127.0.0.1:port"
```