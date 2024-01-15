{
  "spider": "https://mirror.ghproxy.com/https://github.com/FongMi/CatVodSpider/raw/main/jar/custom_spider.jar;md5;a81ee775ab56884c4f5cb932cbc2d1af",
  "wallpaper": "http://饭太硬.top/深色壁纸/api.php",
  "sites": [
    {
      "key": "泥巴",
      "name": "泥巴",
      "type": 3,
      "api": "csp_NiNi",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "星星",
      "name": "星星",
      "type": 3,
      "api": "csp_Star",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "玩偶",
      "name": "玩偶",
      "type": 3,
      "api": "csp_Wogg",
      "searchable": 1,
      "changeable": 0,
      "ext": {
        "token": "影視天下第一",
        "filter": "https://mirror.ghproxy.com/https://raw.githubusercontent.com/qlql765/FongMI-CatVodSpider/main1/json/wogg.json"
      }
    },
    {
      "key": "賤賤",
      "name": "賤賤",
      "type": 3,
      "api": "csp_Jianpian",
      "searchable": 1,
      "changeable": 1,
      "ext": "https://raw.githubusercontent.com/qlql765/FongMI-CatVodSpider/main1/json/jianpian.json"
    },
    {
      "key": "獨播",
      "name": "獨播",
      "type": 3,
      "api": "csp_XPathMacFilter",
      "searchable": 1,
      "changeable": 1,
      "ext": "https://raw.githubusercontent.com/qlql765/FongMI-CatVodSpider/main1/json/duboku.json"
    },
    {
      "key": "haiwaikan",
      "name": "海外看",
      "type": 1,
      "api": "https://haiwaikan.com/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1,
      "categories": [
        "日本动漫",
        "国产动漫",
        "欧美动漫",
        "国产剧",
        "韩剧",
        "日剧",
        "台剧",
        "泰剧",
        "港剧",
        "欧美剧",
        "动画电影",
        "韩国综艺",
        "国产综艺",
        "日本综艺",
        "欧美综艺",
        "冒险片",
        "剧情片",
        "动作片",
        "同性片",
        "喜剧片",
        "奇幻片",
        "恐怖片",
        "悬疑片",
        "惊悚片",
        "战争片",
        "歌舞片",
        "灾难片",
        "爱情片",
        "犯罪片",
        "科幻片",
        "纪录片",
        "经典片"
      ]
    },
    {
      "key": "996影院",
      "name": "996影院",
      "type": 3,
      "api": "csp_Cs1369",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "暴風",
      "name": "暴風",
      "type": 1,
      "api": "https://bfzyapi.com/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "索尼",
      "name": "索尼 ",
      "type": 1,
      "api": "https://suoniapi.com/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "快帆",
      "name": "快帆",
      "type": 1,
      "api": "https://api.kuaifan.tv/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "量子",
      "name": "量子",
      "type": 1,
      "api": "https://cj.lziapi.com/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "非凡",
      "name": "非凡",
      "type": 1,
      "api": "http://cj.ffzyapi.com/api.php/provide/vod",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "櫻花",
      "name": "櫻花",
      "type": 3,
      "api": "csp_Ying",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "巴士",
      "name": "巴士",
      "type": 3,
      "api": "csp_Dm84",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "異界",
      "name": "異界",
      "type": 3,
      "api": "csp_Ysj",
      "searchable": 1,
      "changeable": 1
    },
    {
      "key": "push_agent",
      "name": "推送",
      "type": 3,
      "api": "csp_Push",
      "searchable": 0,
      "changeable": 0,
      "timeout": 60
    }
  ],
  "doh": [
    {
      "name": "Google",
      "url": "https://dns.google/dns-query",
      "ips": [
        "8.8.4.4",
        "8.8.8.8"
      ]
    },
    {
      "name": "Cloudflare",
      "url": "https://cloudflare-dns.com/dns-query",
      "ips": [
        "1.1.1.1",
        "1.0.0.1",
        "2606:4700:4700::1111",
        "2606:4700:4700::1001"
      ]
    },
    {
      "name": "AdGuard",
      "url": "https://dns.adguard.com/dns-query",
      "ips": [
        "94.140.14.140",
        "94.140.14.141"
      ]
    },
    {
      "name": "DNSWatch",
      "url": "https://resolver2.dns.watch/dns-query",
      "ips": [
        "84.200.69.80",
        "84.200.70.40"
      ]
    },
    {
      "name": "Quad9",
      "url": "https://dns.quad9.net/dns-quer",
      "ips": [
        "9.9.9.9",
        "149.112.112.112"
      ]
    }
  ],
  "rules": [
    {
      "name": "proxy",
      "hosts": [
        "raw.githubusercontent.com",
        "googlevideo.com",
        "cdn.v82u1l.com",
        "cdn.iz8qkg.com",
        "cdn.kin6c1.com",
        "c.biggggg.com",
        "c.olddddd.com",
        "haiwaikan.com",
        "www.histar.tv",
        "youtube.com",
        "uhibo.com",
        ".*boku.*",
        ".*nivod.*",
        ".*ulivetv.*"
      ]
    },
    {
      "name": "海外看",
      "hosts": [
        "haiwaikan"
      ],
      "regex": [
        "10.0099",
        "10.3333",
        "16.0599",
        "8.1748",
        "12.33",
        "10.85"
      ]
    },
    {
      "name": "索尼",
      "hosts": [
        "suonizy"
      ],
      "regex": [
        "15.1666",
        "15.2666"
      ]
    },
    {
      "name": "暴風",
      "hosts": [
        "bfzy"
      ],
      "regex": [
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:3,[\\s\\S]*?#EXT-X-DISCONTINUITY"
      ]
    },
    {
      "name": "星星",
      "hosts": [
        "aws.ulivetv.net"
      ],
      "regex": [
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:8,[\\s\\S]*?#EXT-X-DISCONTINUITY"
      ]
    },
    {
      "name": "量子",
      "hosts": [
        "vip.lz",
        "hd.lz",
        "v.cdnlz"
      ],
      "regex": [
        "18.5333"
      ]
    },
    {
      "name": "非凡",
      "hosts": [
        "vip.ffzy",
        "hd.ffzy"
      ],
      "regex": [
        "25.0666",
        "25.08"
      ]
    },
    {
      "name": "火山嗅探",
      "hosts": [
        "huoshan.com"
      ],
      "regex": [
        "item_id="
      ]
    },
    {
      "name": "抖音嗅探",
      "hosts": [
        "douyin.com"
      ],
      "regex": [
        "is_play_url="
      ]
    },
    {
      "name": "農民嗅探",
      "hosts": [
        "toutiaovod.com"
      ],
      "regex": [
        "video/tos/cn"
      ]
    },
    {
      "name": "七新嗅探",
      "hosts": [
        "api.52wyb.com"
      ],
      "regex": [
        "m3u8?pt=m3u8"
      ]
    },
    {
      "name": "夜市",
      "hosts": [
        "yeslivetv.com"
      ],
      "script": [
        "document.getElementsByClassName('vjs-big-play-button')[0].click()"
      ]
    },
    {
      "name": "毛驢",
      "hosts": [
        "www.maolvys.com"
      ],
      "script": [
        "document.getElementsByClassName('swal-button swal-button--confirm')[0].click()"
      ]
    }
  ],
  "ads": [
    "mozai.4gtv.tv"
  ]
}
