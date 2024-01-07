# Sub-DingYue

合并多个相同格式的订阅为一个订阅地址

参数	值

PORT	设置端口，默认7860，报脸不能更改，其他容器可以改

TOK	设置隧道TOKEN

ARGO_DOMAIN	设置隧道域名

NEZHA_SERVER	哪吒服务器

NEZHA_KEY	哪吒密钥

NEZHA_PORT	哪吒端口，默认443

NEZHA_TLS	哪吒是否开启tls，默认开启，可设置为0关闭

TIME	订阅更新间隔，默认设置20,120

GH_PAT	GITHUB令牌

GH_REPO	GITHUB仓库链接，例如github.com/xx/xx.git， 仓库放2个文件：cfip.yaml：ip:8443，sub2.yaml：每行一个链接

SUB2	订阅地址或vl-ess节点链接，中间用;隔开

SUB3	订阅地址或vl-ess节点链接，中间用;隔开

SUB_NAME	本站节点名称

UUID	UUID

VPATH	路径，默认'vls'

