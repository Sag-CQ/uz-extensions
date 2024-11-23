# 视频源扩展

1. 新增扩展时，请补充 vod.json
2. 请将 vod.json 复制到 uzAio.json 的 vod
3. json 样例
```
{
  "name": "名称",
  "codeID": "如果选择了加密请填写，由 uz 生成",
  "api": "扩展链接",
  "instance": "实例名称",
  "webSite": "视频站地址。当加载代码时会赋值给对象的 webSite 属性，用户可自行在 app 内修改",
  "remark": "备注",
  "noHistory": false, // *不开启*历史记录 默认false(即开启历史记录)，用户可自行在 app 内修改
  "userAgent": "", // 设置播放ua 优先级低于 getVideoPlayUrl 返回ua，用户可自行在 app 内修改
  "isLock": false, // 是否上锁 默认false(即不上锁)，用户可自行在 app 内修改
  "blockClassList": ["短剧"], // 屏蔽分类，用户可自行在 app 内修改
  "env":""//环境变量名称1##环境变量描述1&&环境变量名称2##环境变量描述2
}
```

# 订阅

https://ghproxy.cn/https://raw.githubusercontent.com/proversion2024/uz-extensions/refs/heads/master/vod/vod.json

# 添加方式

uz影视 -> 设置 -> 数据管理 -> 视频源 -> 小齿轮 -> 添加 -> 输入链接 -> 确定
