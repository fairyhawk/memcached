memcached
=========

memcached demo，可多台server,2个server配置备份，重试机制，防止意外

文件列表：
MemCache.java
MemCacheService.java
MemCacheServiceImpl.java
PropertiesReader.java
PropertyUtil.java

使用时：
<pre><code>
 MemCache memCache = MemCache.getInstance();
 memCache.set(...);
 memCache.get(...);
 memCache.remove(...);
</code></pre>

