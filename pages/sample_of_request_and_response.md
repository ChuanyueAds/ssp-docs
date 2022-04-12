# 广告请求和返回json示例

- [广告请求和返回json示例](#%E5%B9%BF%E5%91%8A%E8%AF%B7%E6%B1%82%E5%92%8C%E8%BF%94%E5%9B%9Ejson%E7%A4%BA%E4%BE%8B)
	- [banner](#banner)
		- [banner图片广告返回示例](#banner%E5%9B%BE%E7%89%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
			- [banner广告展示示例](#banner%E5%B9%BF%E5%91%8A%E5%B1%95%E7%A4%BA%E7%A4%BA%E4%BE%8B)
		- [banner图文广告返回示例](#banner%E5%9B%BE%E6%96%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
			- [测试返回广告示例](#%E6%B5%8B%E8%AF%95%E8%BF%94%E5%9B%9E%E5%B9%BF%E5%91%8A%E7%A4%BA%E4%BE%8B)
	- [插屏](#%E6%8F%92%E5%B1%8F)
		- [插屏图片广告返回示例](#%E6%8F%92%E5%B1%8F%E5%9B%BE%E7%89%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
			- [APP中插屏图片广告返回示例](#app%E4%B8%AD%E6%8F%92%E5%B1%8F%E5%9B%BE%E7%89%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
		- [插屏图文广告返回示例](#%E6%8F%92%E5%B1%8F%E5%9B%BE%E6%96%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
			- [插屏图文广告返回示例](#%E6%8F%92%E5%B1%8F%E5%9B%BE%E6%96%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
	- [开屏](#%E5%BC%80%E5%B1%8F)
		- [开屏图片广告返回示例](#%E5%BC%80%E5%B1%8F%E5%9B%BE%E7%89%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
		- [开屏图文广告返回示例](#%E5%BC%80%E5%B1%8F%E5%9B%BE%E6%96%87%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
	- [原生广告](#%E5%8E%9F%E7%94%9F%E5%B9%BF%E5%91%8A)
		- [原生广告返回示例](#%E5%8E%9F%E7%94%9F%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)
	- [视频广告](#%E8%A7%86%E9%A2%91%E5%B9%BF%E5%91%8A)
		- [视频广告返回示例](#%E8%A7%86%E9%A2%91%E5%B9%BF%E5%91%8A%E8%BF%94%E5%9B%9E%E7%A4%BA%E4%BE%8B)


## 请求示例

### GET 方法
```  
GET 方法
curl 'https://saad.ms.zhangyue.net/ads/client?ver=3.0&pid=10098&app_id=10019&app_name=%E5%BE%97%E9%97%B4%E5%85%8D%E8%B4%B9%E5%B0%8F%E8%AF%B4&app_package=com.chaozh.iReader.dj&app_ver=3.1.0&device_adid=c0a0da68fc1bccc8&device_brand=OPPO&device_brand_ver=OPPO&device_dpi=320&device_geo_lat=0&device_geo_lon=0&device_height=1424&device_imei=863575045314611&device_imsi=46000&device_model=PBAT00&device_network=2&device_os=Android&device_ppi=320&device_type=0&device_type_os=8.1.0&device_ua=Mozilla%2F5.0+%28Linux%3B+Android+8.1.0%3B+PBAT00+Build%2FOPM1.171019.026%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F62.0.3202.84+Mobile+Safari%2F537.36&device_width=720&device_carrier=46000'

```
### POST 方法
```  
POST 
curl -H 'Content-Type: application/x-www-form-urlencoded;charset=utf-8' -X POST -d 'ver=3.0&pid=10098&app_id=10019&app_name=%E5%BE%97%E9%97%B4%E5%85%8D%E8%B4%B9%E5%B0%8F%E8%AF%B4&app_package=com.chaozh.iReader.dj&app_ver=3.1.0&device_adid=c0a0da68fc1bccc8&device_brand=OPPO&device_brand_ver=OPPO&device_dpi=320&device_geo_lat=0&device_geo_lon=0&device_height=1424&device_imei=863575045314611&device_imsi=46000&device_model=PBAT00&device_network=2&device_os=Android&device_ppi=320&device_type=0&device_type_os=8.1.0&device_ua=Mozilla%2F5.0+%28Linux%3B+Android+8.1.0%3B+PBAT00+Build%2FOPM1.171019.026%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F62.0.3202.84+Mobile+Safari%2F537.36&device_width=720&device_carrier=46000'  'https://saad.ms.zhangyue.net/ads/client'

```


## banner

### banner图片广告返回示例

> 如果请求参数 pid 为Banner广告位

跳转类：

```json
{
    "code":0,
    "msg":"",
    "body":{
        "req_id":"1e7lEVmhm7maAXslLIjLBHo9TYu",
        "pid":"10001",
        "cid":"24051107",
        "ader_id":"23000514",
        "width":1280,
        "height":720,
        "target_type":0,
        "creative_type":1,
        "monitorUrl":[
            "http://rtb-track.mobgc.com/zydsp/imp?price=hq7Pzgw2uIux9y2cOAnU8g&cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
            "http://saad.ms.zhangyue.net/imp?cc=Nw==&rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk="
        ],
        "clickUrl":[
            "http://rtb-track.mobgc.com/zydsp/clk?cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
            "http://saad.ms.zhangyue.net/clk?rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&cdx=__DOWN_X__&cdy=__DOWN_Y__&cux=__UP_X__&cuy=__UP_Y__"
        ],
        "dUrl":[
            "https://h5.m.taobao.com/bcec/dahanghai-jump.html?spm=2014.ugdhh.3829674267.219400-7789-32768&bc_fl_src=growth_dhh_3829674267_219400-7789-32768"
        ],
        "srcUrls":[
            "http://cdn.image.vastboundless.com/ssp_images/202004/04/942694e0-7627-11ea-b767-e7144d0943e3.jpg"
        ],
        "deep_link":"tbopen://m.taobao.com/tbopen/index.html?source=auto&action=ali.open.nav&module=h5&bootImage=0&spm=2014.ugdhh.3829674267.219624-7789-32768&bc_fl_src=growth_dhh_3829674267_219624-7789-32768&materialid=219624&h5Url=https%3A%2F%2Fh5.m.taobao.com%2Fbcec%2Fdahanghai-jump.html%3Fspm%3D2014.ugdhh.3829674267.219624-7789-32768%26bc_fl_src%3Dgrowth_dhh_3829674267_219624-7789-32768",
        "title":"免费领取阅读币",
        "content":"正品家电热卖，免费领券",
        "from_logo":"http://cyad.d.zhangyue01.com/ssp/LOGO/20200219/传阅.png",
        "from":"Zhangyue",
        "app_name":"tbopen",
        "page_style":"1"
    }
}
```

安卓下载类：

```json
{
    "code":0,
    "msg":"",
    "body":{
        "req_id":"1e7lEa8M15hxT05FdyM0dgpuFJm",
        "pid":"10056",
        "cid":"4fbe3e5760b11cb79409f0ca1d84f3e6",
        "ader_id":"12345",
        "width":800,
        "height":1200,
        "target_type":1,
        "monitorUrl":[
            "https://dsp.quyuansu.com/api/adx/reader/report?impId=1&bidid=1e7lEa8M15hxT05FdyM0dgpuFJm&qamId=558&qasId=15&pkge=null&ip=117.179.139.137&model=KIW-TL00&manufacture=HUAWEI&imei=860708036919063&serialno=a15f56f55b3bfcc3&reqid=1e7lEa8M15hxT05FdyM0dgpuFJm&rc=1&uId=1&type=1&price=DdrG_Vk1bg8Yz7fBQFpwbw",
            "https://im-x.jd.com/dsp/np?log=82nbxqOHeMOPM8JuxBiPpOrp1omr-p5djjkV31wsILzClspIBbxXiUAOSCgkLruUQnJ8HeHP8dHYtarsnF2Epxjvq9geUo_s5OdD3QoXnMNc0W7e5HEboaJ1Qwto3rfH3uhyjwwRpsw_ZcbwIsI-SyTs5o_3Iq70QFGdwCGa4WbdFBscbBIfdM700abE_iCbb8Oqajr_WenFbhK-HyQb-pWfkz6oL7HogNItHbB_EUh0-VWSx5H62enQLFy7_jiok122BnAFNJxoCDXe_hBWQUtrRqG3FvWN1OO6bdZ6mwy2EEgRVZoUpWxf5euRbdw9SA_uU-BQ0xBHhHIz2CT5TTUQxl4SlYeubEB32vnG0MfynQOBo_ltIAiIilc_K3meNVIyA_ED3OcWIZ7xk_8Xzv-JvA4QmSNDDEpYDJdIo3r71OhBsRJt2e8y2uqNUrwmBqmUGSULXYtUcVoPvHEsK_6McnwKucJxg_2kRyGDiH7etD1hlL_Qd0r8E6jYrfeLss0Lp9Vn7b_zpn3w7fNyQSYHPgLCDcnQ7q9U-JAfHAGwDUm_QzOf1CQ0scpMZwpW6is8Cwg2VlpIueyqfGRwET_kG_Z49UMsvCQkqzMXueg&v=404&seq=1",
            "http://saad.ms.zhangyue.net/imp?cc=MjAx&rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk="
        ],
        "clickUrl":[
            "https://dsp.quyuansu.com/api/adx/reader/report?impId=1&bidid=1e7lEa8M15hxT05FdyM0dgpuFJm&qamId=558&qasId=15&pkge=null&ip=117.179.139.137&model=KIW-TL00&manufacture=HUAWEI&imei=860708036919063&serialno=a15f56f55b3bfcc3&reqid=1e7lEa8M15hxT05FdyM0dgpuFJm&rc=1&uId=1&type=2&price=%%PRICE%%",
            "http://saad.ms.zhangyue.net/clk?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&cdx=__DOWN_X__&cdy=__DOWN_Y__&cux=__UP_X__&cuy=__UP_Y__"
        ],
        "creative_type":1,
        "dUrl":[
            "https://ally.gdl.netease.com/g18_netease_sogou_cpc_dev_1.271.0_com.netease.my_20nrWeU.apk"
        ],
        "srcUrls":[
            "https://img1.360buyimg.com/pop/jfs/t1/119544/11/10030/87999/5efd5b9eEc049e995/cab301b0443a343f.jpg"
        ],
        "deep_link":"openapp.jdmobile://virtual?params=%7B%22SE%22%3A%22ADC_v7MPvh0th5Cq6%2FYEVQ1rSNPiyUBbE%2BGwo0a%2FBhmJExAVXMa1I6FNKYwPVONIHlCWZljKkkQuRd1Fx1SMgCR8l2uLDic9EBuDrwQJgSBUNsWTfbM5snI5jAr%2FOLwOL2aGx7PDGNHVlI%2BsG6PoRZOR0TsHQriF%2BCIhJhmM6rwNwrQ%3D%22%2C%22action%22%3A%22to%22%2C%22category%22%3A%22jump%22%2C%22des%22%3A%22getCoupon%22%2C%22ext%22%3A%22%7B%5C%22ad%5C%22%3A%5C%22%5C%22%2C%5C%22ch%5C%22%3A%5C%22%5C%22%2C%5C%22shop%5C%22%3A%5C%22%5C%22%2C%5C%22sku%5C%22%3A%5C%22%5C%22%2C%5C%22ts%5C%22%3A%5C%22%5C%22%2C%5C%22uniqid%5C%22%3A%5C%22%7B%5C%5C%5C%22material_id%5C%5C%5C%22%3A%5C%5C%5C%222320925769%5C%5C%5C%22%2C%5C%5C%5C%22pos_id%5C%5C%5C%22%3A%5C%5C%5C%225112%5C%5C%5C%22%2C%5C%5C%5C%22sid%5C%5C%5C%22%3A%5C%5C%5C%22344_19d81073175d4fcebe3c04ade7a9e829_1%5C%5C%5C%22%7D%5C%22%7D%22%2C%22kepler_param%22%3A%7B%22channel%22%3A%222e3b9ecfb3a1465badbbbeb48df4140c%22%2C%22source%22%3A%22kepler-open%22%7D%2C%22m_param%22%3A%7B%22jdv%22%3A%22238571484%7Cqujisuan%7Ct_1001802371_2320925769_5112%7Cadrealizable%7C_2_app_0_b610d03883e2410a815f6bd1c258c0f0-p_5112%22%7D%2C%22sourceType%22%3A%22adx%22%2C%22sourceValue%22%3A%22qujisuan_344%22%2C%22url%22%3A%22https%3A%2F%2Fccc-x.jd.com%2Fdsp%2Fnc%3Fext%3DaHR0cHM6Ly9pdGVtLm0uamQuY29tL3Byb2R1Y3QvNjM1NzUzMzU3NDIuaHRtbD9QVEFHPTE3MDUxLjkuMSZhZF9vZD0x%26log%3D82nbxqOHeMOPM8JuxBiPpOrp1omr-p5djjkV31wsILzClspIBbxXiUAOSCgkLruUQnJ8HeHP8dHYtarsnF2Epxjvq9geUo_s5OdD3QoXnMNc0W7e5HEboaJ1Qwto3rfH3uhyjwwRpsw_ZcbwIsI-SyTs5o_3Iq70QFGdwCGa4WahydH9J_KS34I_YUCeL6Vll3lslEH83xXuIRuvLW7txtxqKwNv6YMo0qfu-bl24Q1M7Xt40BeswX4BipeACNYzFA9rdoFgNlez9NCHWiA7nNI3rjuB4uK3MC-ZjNEt63CvK4TevoD-9kxoV0OGeb0MvtObU03mHeqcYWzaOxwtdSgqXGgpYejwZ9ayyltyftHfIf677v-K9o3bRYe1FKRlKkjkcHTXBFKDRj-80xjpwBUi71PtmOzKj3n7K52rSZyIoqCrrxyjh5IqAt4foRJZpYUwpgZ0gc7x2j_hJUAEA5ClsPbGnYV12Zrat3qhJi3C7eP7dXrRFCIgGsCIq0nvIBbu_0ml-oN0EXfLtWledu4C8iXql7sAI7-ZjdSg_2a9Hp97lRUJD07ZN6drkoCtn3zkhDVimcBsQ22BtbaGTdaRhd7e06esst96mhYfYAxhE9RwQFzCQ9xpFMtXcfdL%26v%3D404%26SE%3D1%22%7D%0A",
        "from":"Zhangyue",
        "page_style":"1",
        "has_ad_logo":"YES",
        "dlink_type":1,
        "dn_start":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=down&action=DownloadStart"
        ],
        "dn_succ":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=down&action=DownloadFinish"
        ],
        "dn_inst_start":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=down&action=ClickInstall"
        ],
        "dn_inst_succ":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=down&action=InstallFinish"
        ],
        "dn_active":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=down&action=DownloadActive"
        ],
        "deep_link_action":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=dlink&action=__DLINK__"
        ],
	"deeplink_trackers":[
            "http://saad.ms.zhangyue.net/track?rid=1e7lEa8M15hxT05FdyM0dgpuFJm&aid=10049&pid=10056&sid=101395&mid=10019&pri=2&advid=quyuansu&cid=4fbe3e5760b11cb79409f0ca1d84f3e6&at=1&st=3&as=10002&fi=0&pi=0&os=1&ip=117.179.139.137&usr=j17968017&did=860708036919063&idfa=&oaid=7fcddf92-b7cc-b8c0-3bff-d7cef9f6b0fc&imei=860708036919063&andid=a15f56f55b3bfcc3&mac=BC%3A75%3A74%3A50%3ABC%3A43&appid=10019&pkg=com.chaozh.iReader.dj&ua=Mozilla%2F5.0+%28Linux%3B+Android+6.0.1%3B+KIW-TL00+Build%2FHONORKIW-TL00%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F55.0.2883.91+Mobile+Safari%2F537.36&make=HUAWEI&model=KIW-TL00&carrier=0&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&etype=dlink&action=__DLINK__"
        ]
    }
}
```

#### banner广告展示示例

TODO

### banner图文广告返回示例

> 如果请求参数 pid 是原生图文广告，则传阅广告可以返回图文广告,图文广告返回的title和desc字段会有对应的标题和描述。

```json
	{
        "code":0,
        "msg":"",
        "body":{
            "req_id":"lLIjLBHo9TYu1e7lEVmhm7maAXs",
            "pid":"10001",
            "cid":"24051107",
            "ader_id":"23000514",
            "width":1280,
            "height":720,
            "target_type":0,
            "creative_type":1,
            "monitorUrl":[
                "http://rtb-track.mobgc.com/zydsp/imp?price=hq7Pzgw2uIux9y2cOAnU8g&cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
                "http://saad.ms.zhangyue.net/imp?cc=Nw==&rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk="
            ],
            "clickUrl":[
                "http://rtb-track.mobgc.com/zydsp/clk?cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
                "http://saad.ms.zhangyue.net/clk?rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&cdx=__DOWN_X__&cdy=__DOWN_Y__&cux=__UP_X__&cuy=__UP_Y__"
            ],
            "dUrl":[
                "https://h5.m.taobao.com/bcec/dahanghai-jump.html?spm=2014.ugdhh.3829674267.219400-7789-32768&bc_fl_src=growth_dhh_3829674267_219400-7789-32768"
            ],
            "srcUrls":[
                "http://cdn.image.vastboundless.com/ssp_images/202004/04/942694e0-7627-11ea-b767-e7144d0943e3.jpg"
            ],
            "deep_link":"tbopen://m.taobao.com/tbopen/index.html?source=auto&action=ali.open.nav&module=h5&bootImage=0&spm=2014.ugdhh.3829674267.219624-7789-32768&bc_fl_src=growth_dhh_3829674267_219624-7789-32768&materialid=219624&h5Url=https%3A%2F%2Fh5.m.taobao.com%2Fbcec%2Fdahanghai-jump.html%3Fspm%3D2014.ugdhh.3829674267.219624-7789-32768%26bc_fl_src%3Dgrowth_dhh_3829674267_219624-7789-32768",
            "title":"免费领取阅读币",
            "content":"正品家电热卖，免费领券",
            "from_logo":"http://cyad.d.zhangyue01.com/ssp/LOGO/20200219/传阅.png",
            "from":"Zhangyue",
            "app_name":"tbopen",
            "page_style":"1"
        }
    }
```

> 图文广告不能像图片广告一样，直接把图片展示出来，通常是将图片，标题，描述按照左图右文字（标题上，描述下或标题描述拼接在一起）组合拼装，如下面示例；媒体也可以根据自己的需求选择拼接的样式。

## 插屏

> 插屏广告响应同banner广告一样 


### 插屏图片广告返回示例

> 参考banner图片广告，展示返回广告中的 图片即可。

```json

```
 
## 开屏

### 开屏图片广告返回示例

> 参考banner图片广告，展示返回广告中的 图片即可。

 

## 原生广告
 
### 原生广告返回示例

```json
	{
            "code":0,
            "msg":"",
            "body":{
                "req_id":"lLIjLBHo9TYu1e7lEVmhm7maAXs",
                "pid":"10001",
                "cid":"24051107",
                "ader_id":"23000514",
                "width":1280,
                "height":720,
                "target_type":0,
                "creative_type":1,
                "monitorUrl":[
                    "http://rtb-track.mobgc.com/zydsp/imp?price=hq7Pzgw2uIux9y2cOAnU8g&cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
                    "http://saad.ms.zhangyue.net/imp?cc=Nw==&rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk="
                ],
                "clickUrl":[
                    "http://rtb-track.mobgc.com/zydsp/clk?cid=24051107&campaign=120&pid=10001&pmp_id=32eb8aa29&pmp_p=0&aid=c514ca4f7733a5e7",
                    "http://saad.ms.zhangyue.net/clk?rid=1e7lEVmhm7maAXslLIjLBHo9TYu&aid=10016&pid=10001&sid=100359&mid=10000&pri=3&advid=23000514&cid=24051107&at=1&st=3&as=10003&fi=100001&pi=73&os=1&ip=49.73.44.75&usr=i1412471795&did=99001021722550&idfa=&oaid=db32ce6f4cb2f964&imei=99001021722550&andid=c514ca4f7733a5e7&mac=D8%3A63%3A75%3AB1%3A31%3A69&appid=10000&pkg=com.chaozh.iReaderFree&ua=Mozilla%2F5.0+%28Linux%3B+Android+8.0.0%3B+MIX+2+Build%2FOPR1.170623.027%3B+wv%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Version%2F4.0+Chrome%2F71.0.3578.99+Mobile+Safari%2F537.36&make=Xiaomi&model=MIX+2&carrier=3&net=2&ts=193680400&codeid=&iv=&vc=&apf=&ov=&pn=&pv=&chid=&nk=&cdx=__DOWN_X__&cdy=__DOWN_Y__&cux=__UP_X__&cuy=__UP_Y__"
                ],
                "dUrl":[
                    "https://h5.m.taobao.com/bcec/dahanghai-jump.html?spm=2014.ugdhh.3829674267.219400-7789-32768&bc_fl_src=growth_dhh_3829674267_219400-7789-32768"
                ],
                "srcUrls":[
                    "http://cdn.image.vastboundless.com/ssp_images/202004/04/942694e0-7627-11ea-b767-e7144d0943e3.jpg"
                ],
                "deep_link":"tbopen://m.taobao.com/tbopen/index.html?source=auto&action=ali.open.nav&module=h5&bootImage=0&spm=2014.ugdhh.3829674267.219624-7789-32768&bc_fl_src=growth_dhh_3829674267_219624-7789-32768&materialid=219624&h5Url=https%3A%2F%2Fh5.m.taobao.com%2Fbcec%2Fdahanghai-jump.html%3Fspm%3D2014.ugdhh.3829674267.219624-7789-32768%26bc_fl_src%3Dgrowth_dhh_3829674267_219624-7789-32768",
                "title":"免费领取阅读币",
                "content":"正品家电热卖，免费领券",
                "from_logo":"http://cyad.d.zhangyue01.com/ssp/LOGO/20200219/传阅.png",
                "from":"Zhangyue",
                "app_name":"tbopen",
                "page_style":"1"
            }
        }
```

## 视频广告
 
### 视频广告返回示例

```json

```

 
