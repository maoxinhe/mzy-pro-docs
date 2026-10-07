---
layout: splash
title: 新手导航
---

<!--{% comment %}-->
> [!NOTE]
> <!--{% endcomment %}-->
> <!----{{ '>' }} **Notice** <br> {{ '<' }}!---->
> The articles were written in Simplified Chinese. If you want to help translate them, please send a pull request to [mzy-pro-docs/pulls](https://github.com/maoxinhe/mzy-pro-docs/pulls). Or you can enable your translation tool to read.\
> If you encounter a BUG, please send feedback in time to [CMY/issues](https://github.com/maoxinhe/mzy-pro-source/issues).\
> You can also submit your suggestions here.
<!----{{ '>' }}
{: .notice--info }
<!---->

> [!NOTE]
> 如果您遇到 BUG，请及时在 [CMY/issues](https://github.com/maoxinhe/mzy-pro-source/issues) 发送反馈。\
> 您也可以在这里提交您的建议。

这里是CMY的官方帮助文档。如欲了解CMY的使用方法、解决常见问题，请翻阅下方目录。如欲咨询崩溃原因，可前往[QQ群](https://docs.camzy.tech/groups.html)或[QQ群](https://qun.qq.com/universal-share/share?ac=1&authKey=izNwNGOSgy7S0f7IUvQSYrklF5Ae7nnFTp%2BphwU0w2paGJbtXfRY1qng7V88AKiP&busi_data=eyJncm91cENvZGUiOiIxMTAzMzg0MzA0IiwidG9rZW4iOiJlRlJUTEx4QU5OVDlxSkg3a3NDeFBrTWRueWVHcmNWYUN4eUtNTjFpdi9vZ0FhMlR1TzNEMlRIeWtFMW5yMkkvIiwidWluIjoiMTA5NjU1MDU5OCJ9&data=XhJzrl_mq0gpfvwn2zON0cU8Hc82MJlwBBGNYLK7-GibowMSukjVmaiGayg1OZ6YsR-OP3ilMcWw55BjloH53g&svctype=4&tempid=h5_group_info)寻求帮助。

{% include toc %}

{% for group in site.data.navigation.docs -%}
## {{ group.title }}
{% for item in group.children -%}
1. [{{ item.title }}]({{ item.url }})
{%- if item.description %}\
   {{ item.description }}
{%- endif %}
{% endfor %}
{% endfor %}
