#RSS2HTML
<p>PHP RAW фаилот е креиран за потребите на Македонски Медиа Сервис - https://mms.mk/test/rss за превземање и форматирање на widget за Wordpress на Македонски Медиа Сервис</p>

#Инсталација
1. Се превзема фаилот и се прикачува на сервер
2. Се модифицира фаилот на крајот со што се додава соодветниот RSS канал
  пр. [code]<?php
// output RSS feed to HTML
output_rss_feed('http://mms.mk/feed', 10, true, false, 200);
?>
[/code]
