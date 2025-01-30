# 听说你们还在维护Genisys？让我猜猜：

- 每次pull request都像在玩俄罗斯轮盘赌——五发子弹的那种
- 你们的事件监听器写的try-catch比业务逻辑还长吧？
- 当Block->getDamage()返回的是开发者的心理健康值
- 你们用AsyncTask的时候是不是还要同步烧香拜佛？
- 什么？你的插件兼容API2？请先定义"兼容"——是崩溃前能加载0.5秒的那种吗？
- 文档？什么文档？我们靠的是考古发掘commit message和民间传说
- 单元测试？当然有！每次启动服务端不就是一次完整的集成测试吗？
- 听说你们项目里的 `@deprecated` 标签其实是行为艺术——毕竟三年了还没人敢删
- 听说你们的崩溃报告系统很先进？指玩家在QQ群刷屏"又炸了"
- 你们处理bug的方式：在代码里写满 `//TODO: 下辈子一定修`

# TelemetryEventPacket

	public const TYPE_ACHIEVEMENT_AWARDED = 0;
	public const TYPE_ENTITY_INTERACT = 1;
	public const TYPE_PORTAL_BUILT = 2;
	public const TYPE_PORTAL_USED = 3;
	public const TYPE_MOB_KILLED = 4;
	public const TYPE_CAULDRON_USED = 5;

![image](https://github.com/user-attachments/assets/50fd6ed3-a228-490f-8c50-425de87c97e4)
