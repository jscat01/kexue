优化了openclash科学上网域名规则列表
删除了重复的域名，常用的Ａpple和微软设置成当独规则
可以根据自己的实际需要进行修改

self_proxy: { <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/proxy_main.list"}
  private_domain: { <<: *domain, url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/private.mrs"}
  cn_domain: { <<: *domain, url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/cn.mrs"}
  ai_domain: {  <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/ai_domain.list" }
  youtube_domain: {  <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/youtube_domain.list" }
  block_domain: {  <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/block_domain.list" }
  ip_global: {  <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/ip_global.list" }
  fishing_domain: { <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/fishing_domain.list"}
  global_domain: { <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/global_domain.list"}
  microsoft_domain: { <<: *class, url: "https://raw.githubusercontent.com/jscat01/kexue/refs/heads/main/rules/microsoft_domain.list"}
