1.模板上下文处理函数(@app.context_processor针对的是模板的渲染,所以在逻辑语句中仍需要写user=User.query.first()

2.delete方法的method请求只能是"POST",这是出于安全的考虑

3.增加,编辑,删除条目都要先有一个movie实例,而改名和登录需要在user实例上做文章