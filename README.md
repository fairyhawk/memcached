memcached
=========

memcached demo，可多台server,2个server配置备份，重试机制，防止意外

文件列表：
<pre><code>
MemCache.java
MemCacheService.java
MemCacheServiceImpl.java
PropertiesReader.java
PropertyUtil.java
</code></pre>
使用时：
<pre><code>
 MemCache memCache = MemCache.getInstance();
 memCache.set(...);
 memCache.get(...);
 memCache.remove(...);
</code></pre>
pom 中使用spymemcached :
<pre><code>
 <dependency>
	    <groupId>net.spy</groupId>
	    <artifactId>spymemcached</artifactId>
	    <version>2.10.3</version>
	</dependency>
</code></pre>


