## Buffon
> 布冯一个伟大的守门员

整个类的核心

```
set_exception_handler(array($this, 'handleException'));//截获未捕获的异常
set_error_handler(array($this, 'handleError'));//截获各种错误 此处切不可掉换位置
register_shutdown_function(array($this, 'handleFatalError'));//截获致命性错误

```
