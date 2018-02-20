# learn-sn


在 hybirdconnector.js 的 start()中,  gensocket()方法中, 使用了 emit 发送了一个 'connection' 事件，这个事件是在 components/connector.js 中的 afterStart()方法中监听的： 
    this.connector.on('connection', hostFilter.bind(this,bindEvents))
