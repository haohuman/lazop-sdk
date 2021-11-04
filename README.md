# lazop-sdk
Lazada Open API PHP SDK

## sample

```php
$c = new LazopClient($url,$appkey,$appSecret);
$request = new LazopRequest('/marketing/rta/adrequest');
$request->addApiParam('gaid_sha256','70574fa9c8f498a7b2e5c8712b1126de7b1406fd02fdc591821c5bd33092fd1c');
$request->addApiParam('oaid','c14e7fb1-4475-4b21-ba18-063c354c0a3c');
$request->addApiParam('gaid','c14e7fb1-4475-4b21-ba18-063c354c0a3c');
$request->addApiParam('city','Jakarta');
$request->addApiParam('channel_retargeting','true');
$request->addApiParam('app_domain','mygame.foo.com');
$request->addApiParam('site_category','Humor');
$request->addApiParam('store_url','https://aaa');
$request->addApiParam('model','iPhone');
$request->addApiParam('client_ip','202.221.221.10');
$request->addApiParam('member_id','1234567');
$request->addApiParam('make','Apple');
$request->addApiParam('user_agent','Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36');
$request->addApiParam('referer_url','http://www.google.com');
$request->addApiParam('test','0');
$request->addApiParam('os','Android');
$request->addApiParam('site_domain','google.com');
$request->addApiParam('idfa_sha256','70574fa9c8f498a7b2e5c8712b1126de7b1406fd02fdc591821c5bd33092fd1c');
$request->addApiParam('idfa','9C287922-EE26-4501-94B5-DDE6F83E1475');
$request->addApiParam('os_version','1.0.0');
$request->addApiParam('page_category','humor');
$request->addApiParam('site_name','BBC');
$request->addApiParam('app_name','app_name');
$request->addApiParam('limited_ad_tracking','true');
$request->addApiParam('site_url','http://www.aaa.com/index.htm');
$request->addApiParam('bundle_id','com.company.appName');
$request->addApiParam('imei','123456-12-123456-4');
$request->addApiParam('ad_request_id','11111111111111');
$request->addApiParam('sub_channel_id','subchannel1');
$request->addApiParam('app_category','humor');
$request->addApiParam('campaign_id_list','[\"123456789012\",\"1234567890\"]');
$request->addApiParam('country','ID');
var_dump($c->execute($request));
```
