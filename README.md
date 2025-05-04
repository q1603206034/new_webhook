# new_webhook




app:
  description: ''
  icon: "\U0001F4DD"
  icon_background: '#D1E9FF'
  mode: workflow
  name: RSS Summary Workflow - export
workflow:
  features:
    file_upload:
      image:
        enabled: false
        number_limits: 3
        transfer_methods:
        - local_file
        - remote_url
    opening_statement: ''
    retriever_resource:
      enabled: true
    sensitive_word_avoidance:
      enabled: false
    speech_to_text:
      enabled: false
    suggested_questions: []
    suggested_questions_after_answer:
      enabled: false
    text_to_speech:
      enabled: false
      language: ''
      voice: ''
  graph:
    edges:
    - data:
        isInIteration: false
        sourceType: start
        targetType: tool
      id: 1720615783929-source-1720672602189-target
      selected: false
      source: '1720615783929'
      sourceHandle: source
      target: '1720672602189'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: tool
        targetType: code
      id: 1720710334132-source-1720712509002-target
      selected: false
      source: '1720710334132'
      sourceHandle: source
      target: '1720712509002'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: if-else
      id: 1720712509002-source-1720713040995-target
      selected: false
      source: '1720712509002'
      sourceHandle: source
      target: '1720713040995'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: http-request
        targetType: code
      id: 1720718089436-source-1720718390681-target
      selected: false
      source: '1720718089436'
      sourceHandle: source
      target: '1720718390681'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: template-transform
      id: 1720719111245-source-1720721997007-target
      selected: false
      source: '1720719111245'
      sourceHandle: source
      target: '1720721997007'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: if-else
        targetType: code
      id: 1720713040995-true-1720719111245-target
      selected: false
      source: '1720713040995'
      sourceHandle: 'true'
      target: '1720719111245'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: template-transform
        targetType: code
      id: 1720721997007-source-1720724507619-target
      selected: false
      source: '1720721997007'
      sourceHandle: source
      target: '1720724507619'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: code
      id: 1720724507619-source-1720769965637-target
      selected: false
      source: '1720724507619'
      sourceHandle: source
      target: '1720769965637'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: tool
      id: 1720769965637-source-1720713091793-target
      selected: false
      source: '1720769965637'
      sourceHandle: source
      target: '1720713091793'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: template-transform
        targetType: template-transform
      id: 1720672659201-source-17207717259350-target
      selected: false
      source: '1720672659201'
      sourceHandle: source
      target: '17207717259350'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: template-transform
        targetType: code
      id: 17207717259350-source-17207717498450-target
      selected: false
      source: '17207717259350'
      sourceHandle: source
      target: '17207717498450'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: code
      id: 17207717498450-source-17207718235970-target
      selected: false
      source: '17207717498450'
      sourceHandle: source
      target: '17207718235970'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: tool
      id: 17207718235970-source-1720715845564-target
      selected: false
      source: '17207718235970'
      sourceHandle: source
      target: '1720715845564'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: tool
        targetType: end
      id: 1720713091793-source-1720621700028-target
      selected: false
      source: '1720713091793'
      sourceHandle: source
      target: '1720621700028'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: tool
        targetType: end
      id: 1720715845564-source-1720774741080-target
      selected: false
      source: '1720715845564'
      sourceHandle: source
      target: '1720774741080'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: if-else
        targetType: code
      id: 1720713040995-false-1720787293636-target
      selected: false
      source: '1720713040995'
      sourceHandle: 'false'
      target: '1720787293636'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: template-transform
      id: 1720787293636-source-1720787662754-target
      selected: false
      source: '1720787293636'
      sourceHandle: source
      target: '1720787662754'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: template-transform
        targetType: template-transform
      id: 1720787662754-source-1720672659201-target
      selected: false
      source: '1720787662754'
      sourceHandle: source
      target: '1720672659201'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: tool
        targetType: code
      id: 1720672602189-source-1720863643271-target
      selected: false
      source: '1720672602189'
      sourceHandle: source
      target: '1720863643271'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: http-request
      id: 1720863643271-source-1720718089436-target
      selected: false
      source: '1720863643271'
      sourceHandle: source
      target: '1720718089436'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: llm
        targetType: tool
      id: 1720621617132-source-1720710334132-target
      source: '1720621617132'
      sourceHandle: source
      target: '1720710334132'
      targetHandle: target
      type: custom
      zIndex: 0
    - data:
        isInIteration: false
        sourceType: code
        targetType: llm
      id: 1720718390681-source-1720621617132-target
      selected: false
      source: '1720718390681'
      sourceHandle: source
      target: '1720621617132'
      targetHandle: target
      type: custom
      zIndex: 0
    nodes:
    - data:
        desc: ''
        selected: false
        title: "\u5F00\u59CB"
        type: start
        variables:
        - label: link
          max_length: 33024
          options: []
          required: true
          type: paragraph
          variable: link
      height: 90
      id: '1720615783929'
      position:
        x: -536.8981081466043
        y: 331.52901327685925
      positionAbsolute:
        x: -536.8981081466043
        y: 331.52901327685925
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        provider_id: jina
        provider_name: jina
        provider_type: builtin
        selected: false
        title: JinaReader
        tool_configurations:
          gather_all_images_at_the_end: 0
          gather_all_links_at_the_end: 1
          image_caption: 1
          no_cache: 0
          proxy_server: null
          summary: 0
          target_selector: null
          wait_for_selector: null
        tool_label: JinaReader
        tool_name: jina_reader
        tool_parameters:
          url:
            type: mixed
            value: '{{#1720615783929.link#}}'
        type: tool
      height: 272
      id: '1720672602189'
      position:
        x: -244.50360799073
        y: 331.52901327685925
      positionAbsolute:
        x: -244.50360799073
        y: 331.52901327685925
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        context:
          enabled: false
          variable_selector: []
        desc: ''
        model:
          completion_params:
            temperature: 0.5
          mode: chat
          name: moonshot-v1-32k
          provider: moonshot
        prompt_template:
        - id: b3259906-b3fd-420f-ba87-f75c50f60c7d
          role: system
          text: "{{#1720672602189.text#}}\n---\n\u5047\u8BBE\u4F60\u662F\u4E00\u4F4D\
            \u8D44\u6DF1\u7684\u8BED\u6587\u8001\u5E08\uFF0C\u5584\u4E8E\u7528\u7CBE\
            \u5999\u7684\u8BED\u8A00\u5C06\u590D\u6742\u7684\u79D1\u6280\u5185\u5BB9\
            \u5A13\u5A13\u9053\u6765\u3002\u8BF7\u4E3A\u4E00\u7BC7\u79D1\u6280\u7C7B\
            \u6587\u7AE0\u5199\u4E00\u4E2A\u8BE6\u7EC6\u7684\u6458\u8981\uFF0C\u8981\
            \u6C42\u5185\u5BB9\u7CBE\u51C6\uFF0C\u8BED\u8A00\u98CE\u683C\u5BCC\u6709\
            \u6291\u626C\u987F\u632B\uFF0C\u80FD\u591F\u5728\u4E0D\u540C\u7684\u8868\
            \u8FBE\u65B9\u5F0F\u4E2D\u81EA\u7136\u5207\u6362\u3002\u6458\u8981\u4E0D\
            \u5E94\u663E\u5F97\u50CF\u8425\u9500\u6587\u6848\uFF0C\u800C\u662F\u50CF\
            \u4E00\u4F4D\u8BED\u6587\u8001\u5E08\u7684\u7B14\u6CD5\uFF0C\u7CBE\u51C6\
            \u4E14\u5BCC\u6709\u6587\u91C7\u3002\uFF08\u8FD9\u90E8\u5206\u4E0D\u9700\
            \u8981 html \u683C\u5F0F\uFF09"
        selected: false
        title: "\u6458\u8981"
        type: llm
        variables: []
        vision:
          enabled: false
      height: 98
      id: '1720621617132'
      position:
        x: 372.6720045745774
        y: 330.26771456262816
      positionAbsolute:
        x: 372.6720045745774
        y: 330.26771456262816
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        outputs: []
        selected: false
        title: "\u7ED3\u675F"
        type: end
      height: 54
      id: '1720621700028'
      position:
        x: 2459.7671189728358
        y: 328.9250750349567
      positionAbsolute:
        x: 2459.7671189728358
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        selected: false
        template: "<!DOCTYPE html>\n<html lang=\"en\">\n<head>\n    <meta charset=\"\
          UTF-8\">\n    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\"\
          >\n    <title>\U0001F48C Daily Newsletter</title>\n    <style>\n       \
          \ body {\n            font-family: Arial, sans-serif;\n            color:\
          \ #fff;\n            background-color: #000;\n            margin: 0;\n \
          \           padding: 0;\n        }\n        .container {\n            width:\
          \ 100%;\n            max-width: 600px;\n            margin: 0 auto;\n  \
          \          padding: 20px;\n            box-sizing: border-box;\n       \
          \ }\n        .content-wrapper {\n            padding: 0 20px;\n        }\n\
          \        .header-image {\n            width: 100%;\n            max-width:\
          \ 600px;\n            height: auto;\n            border-radius: 12px;\n\
          \            margin-bottom: 10px;\n        }\n        .section {\n     \
          \       margin: 32px 0;\n        }\n        .section-title {\n         \
          \   font-size: 24px;\n            font-weight: bold;\n            margin:\
          \ 0 0 10px;\n            word-wrap: break-word;\n            color: #ff0000\n\
          \        }\n        .section-content {\n            font-size: 16px;\n \
          \           line-height: 1.5;\n            margin: 0 0 10px;\n         \
          \   word-wrap: break-word;\n        }\n        .divider {\n            border-bottom:\
          \ 1px solid #ff0000;\n            margin: 20px 0;\n        }\n        .email-date\
          \ {\n            text-align: center;\n            color: #888888;\n    \
          \        font-size: 14px;\n            margin-bottom: 20px;\n          \
          \  margin-top: 20px;\n        }\n        .email-title {\n            text-align:\
          \ center;\n            font-size: 24px;\n            font-weight: bold;\n\
          \            margin-bottom: 30px;\n            word-wrap: break-word;\n\
          \        }\n        .footer-divider {\n            width: 100px;\n     \
          \       height: 10px;\n            background-image: url(\"data:image/svg+xml,%3Csvg\
          \ width='100' height='10' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M0\
          \ 5 Q 10 0, 20 5 T 40 5 T 60 5 T 80 5 T 100 5' fill='none' stroke='%23eeeeee'\
          \ stroke-width='2'/%3E%3C/svg%3E\");\n            background-repeat: repeat-x;\n\
          \            margin: 30px auto;\n        }\n        .page-footer {\n   \
          \         text-align: center;\n            color: #888888;\n           \
          \ font-size: 16px;\n            line-height: 1.5;\n            margin-top:\
          \ 20px;\n            word-wrap: break-word;\n        }\n        @media (max-width:\
          \ 600px) {\n            .container {\n                padding: 10px;\n \
          \           }\n            .content-wrapper {\n                padding:\
          \ 0 15px;\n            }\n        }\n    </style>\n</head>\n<body>\n   \
          \ <div class=\"container\">\n        <div class=\"email-date\">{{ date }}</div>\n\
          \        <div class=\"email-title\">{{ email_title }}</div>\n        <img\
          \ src=\"https://media.discordapp.net/attachments/1032920107585896478/1261283907010035744/cover.png?ex=669265ac&is=6691142c&hm=ad08d9899147eeae30b6db3b9a97fa292a9f9757a57ebc561f7c533fc2b496bc&=&format=webp&quality=lossless&width=1920&height=1080\"\
          \ alt=\"Header Image\" class=\"header-image\">"
        title: Html - Part 1
        type: template-transform
        variables:
        - value_selector:
          - '1720621617132'
          - text
          variable: arg1
        - value_selector:
          - '1720787293636'
          - result1
          variable: date
        - value_selector:
          - '1720787662754'
          - output
          variable: email_title
      height: 54
      id: '1720672659201'
      position:
        x: 1006.7904034975418
        y: 637.6742207415048
      positionAbsolute:
        x: 1006.7904034975418
        y: 637.6742207415048
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        provider_id: feishu_base
        provider_name: feishu_base
        provider_type: builtin
        selected: false
        title: "\u67E5\u8BE2\u591A\u7EF4\u8868\u683C\u6570\u636E\u8868\u4E2D\u7684\
          \u73B0\u6709\u8BB0\u5F55"
        tool_configurations: {}
        tool_label: "\u67E5\u8BE2\u591A\u7EF4\u8868\u683C\u6570\u636E\u8868\u4E2D\u7684\
          \u73B0\u6709\u8BB0\u5F55"
        tool_name: list_base_records
        tool_parameters:
          Authorization:
            type: mixed
            value: '{{#1720718390681.result#}}'
          app_token:
            type: mixed
            value: ''
          filter_condition:
            type: mixed
            value: "{\n        \"conjunction\": \"and\",\n        \"conditions\":\
              \ [\n            {\n                \"field_name\": \"date\",\n    \
              \            \"operator\": \"is\",\n                \"value\": [\"Today\"\
              ]\n            }\n        ]\n}"
          table_id:
            type: mixed
            value: ''
        type: tool
      height: 54
      id: '1720710334132'
      position:
        x: 682.4299593125363
        y: 330.26771456262816
      positionAbsolute:
        x: 682.4299593125363
        y: 330.26771456262816
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "import re\n\ndef main(input_data: str) -> dict:\n    \"\"\"\n    \u4ECE\
          \u7ED9\u5B9A\u7684\u5B57\u7B26\u4E32\u4E2D\u63D0\u53D6 \"total\" \u503C\n\
          \    \n    :param input_data: \u5305\u542B \"total\" \u503C\u7684\u8F6C\u4E49\
          \ JSON \u5B57\u7B26\u4E32\n    :return: \u5305\u542B\u63D0\u53D6\u51FA\u7684\
          \ \"total\" \u503C\uFF08\u5B57\u7B26\u4E32\u7C7B\u578B\uFF09\u7684\u5B57\
          \u5178\n    \"\"\"\n    pattern_total = r'\"total\": (\\d+)'\n    match_total\
          \ = re.search(pattern_total, input_data)\n    \n    return {\n        \"\
          total\": match_total.group(1) if match_total else \"0\"\n    }"
        code_language: python3
        desc: ''
        outputs:
          total:
            children: null
            type: string
        selected: false
        title: "\u6570\u636E\u6761\u6570\u63D0\u53D6"
        type: code
        variables:
        - value_selector:
          - '1720710334132'
          - text
          variable: input_data
      height: 54
      id: '1720712509002'
      position:
        x: 682.4299593125363
        y: 415.90512921207466
      positionAbsolute:
        x: 682.4299593125363
        y: 415.90512921207466
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        cases:
        - case_id: 'true'
          conditions:
          - comparison_operator: is not
            id: 90781d6a-f521-467f-89b7-d2d131cc3694
            value: '0'
            varType: string
            variable_selector:
            - '1720712509002'
            - total
          id: 'true'
          logical_operator: and
        desc: ''
        selected: false
        title: "\u6761\u4EF6\u5206\u652F"
        type: if-else
      height: 126
      id: '1720713040995'
      position:
        x: 682.4299593125363
        y: 497.17116432030025
      positionAbsolute:
        x: 682.4299593125363
        y: 497.17116432030025
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        provider_id: feishu_base
        provider_name: feishu_base
        provider_type: builtin
        selected: false
        title: "\u66F4\u65B0 html \u6B63\u6587"
        tool_configurations: {}
        tool_label: "\u66F4\u65B0\u591A\u7EF4\u8868\u683C\u6570\u636E\u8868\u4E2D\u7684\
          \u4E00\u6761\u8BB0\u5F55"
        tool_name: update_base_record
        tool_parameters:
          Authorization:
            type: mixed
            value: '{{#1720718390681.result#}}'
          app_token:
            type: mixed
            value: ''
          fields:
            type: mixed
            value: '{{#1720769965637.result#}}'
          record_id:
            type: mixed
            value: '{{#1720719111245.result2#}}'
          table_id:
            type: mixed
            value: ''
        type: tool
      height: 54
      id: '1720713091793'
      position:
        x: 2180.607260104055
        y: 328.9250750349567
      positionAbsolute:
        x: 2180.607260104055
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        provider_id: feishu_base
        provider_name: feishu_base
        provider_type: builtin
        selected: true
        title: "\u65B0\u589E html \u8BB0\u5F55"
        tool_configurations: {}
        tool_label: "\u5728\u591A\u7EF4\u8868\u683C\u6570\u636E\u8868\u4E2D\u65B0\u589E\
          \u4E00\u6761\u8BB0\u5F55"
        tool_name: add_base_record
        tool_parameters:
          Authorization:
            type: mixed
            value: '{{#1720718390681.result#}}'
          app_token:
            type: mixed
            value: ''
          fields:
            type: mixed
            value: '{{#17207718235970.result#}}'
          table_id:
            type: mixed
            value: ''
        type: tool
      height: 54
      id: '1720715845564'
      position:
        x: 2184.4287837289694
        y: 637.6742207415048
      positionAbsolute:
        x: 2184.4287837289694
        y: 637.6742207415048
      selected: true
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        authorization:
          config: null
          type: no-auth
        body:
          data: "{\n    \"app_id\": \"\",\n    \"app_secret\": \"\"\n}"
          type: raw-text
        desc: ''
        headers: Content-Type:application/json; charset=utf-8
        method: post
        params: ''
        selected: false
        timeout:
          max_connect_timeout: 0
          max_read_timeout: 0
          max_write_timeout: 0
        title: "tenant_access_token \u83B7\u53D6"
        type: http-request
        url: https://open.feishu.cn/open-apis/auth/v3/tenant_access_token/internal
        variables: []
      height: 122
      id: '1720718089436'
      position:
        x: 65.81659914734007
        y: 331.52901327685925
      positionAbsolute:
        x: 65.81659914734007
        y: 331.52901327685925
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "import re\n\ndef main(arg1: str) -> dict:\n    \"\"\"\n    \u4ECE\u7ED9\
          \u5B9A\u7684\u5B57\u7B26\u4E32\u4E2D\u63D0\u53D6 \"tenant_access_token\"\
          \ \u503C\n    \n    :param arg1: \u5305\u542B \"tenant_access_token\" \u503C\
          \u7684\u8F6C\u4E49 JSON \u5B57\u7B26\u4E32\n    :return: \u5305\u542B\u63D0\
          \u53D6\u51FA\u7684 \"tenant_access_token\" \u503C\u7684\u5B57\u5178\n  \
          \  \"\"\"\n    pattern_token = r'\"tenant_access_token\":\"([^\"]+)\"'\n\
          \    match_token = re.search(pattern_token, arg1)\n    \n    return {\n\
          \        \"result\": match_token.group(1) if match_token else \"\"\n   \
          \ }"
        code_language: python3
        desc: ''
        outputs:
          result:
            children: null
            type: string
        selected: false
        title: "token \u63D0\u53D6"
        type: code
        variables:
        - value_selector:
          - '1720718089436'
          - body
          variable: arg1
      height: 54
      id: '1720718390681'
      position:
        x: 65.81659914734007
        y: 481.2622431255103
      positionAbsolute:
        x: 65.81659914734007
        y: 481.2622431255103
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "def main(input_data: str) -> dict:\n    \"\"\"\n    \u4ECE\u7ED9\u5B9A\
          \u7684\u5B57\u7B26\u4E32\u4E2D\u63D0\u53D6 'html' \u5B57\u6BB5\u7684 'text'\
          \ \u5185\u5BB9\u548C 'record_id' \u503C\n    \n    :param input_data: \u5305\
          \u542B 'html' \u548C 'record_id' \u503C\u7684 JSON \u5B57\u7B26\u4E32\n\
          \    :return: \u5305\u542B\u63D0\u53D6\u51FA\u7684 'html' \u4E2D\u7684 'text'\
          \ \u5185\u5BB9\u548C 'record_id' \u503C\u7684\u5B57\u5178\n    \"\"\"\n\
          \    # \u89E3\u6790JSON\n    data = json.loads(input_data)\n    \n    #\
          \ \u521D\u59CB\u5316\u53D8\u91CF\n    html_text = \"\"\n    record_id =\
          \ \"\"\n    \n    # \u63D0\u53D6html\u4E2D\u7684text\u5185\u5BB9\u548Crecord_id\n\
          \    if 'data' in data and 'items' in data['data'] and len(data['data']['items'])\
          \ > 0:\n        item = data['data']['items'][0]\n        if 'fields' in\
          \ item and 'html' in item['fields']:\n            html_content = item['fields']['html']\n\
          \            if isinstance(html_content, list) and len(html_content) > 0:\n\
          \                html_text = html_content[0].get('text', '')\n        record_id\
          \ = item.get('record_id', \"\")\n    \n    return {\n        \"result1\"\
          : html_text,\n        \"result2\": record_id\n}"
        code_language: python3
        desc: ''
        outputs:
          result1:
            children: null
            type: string
          result2:
            children: null
            type: string
        selected: false
        title: "\u6B63\u6587 & Record Id \u67E5\u8BE2"
        type: code
        variables:
        - value_selector:
          - '1720710334132'
          - text
          variable: input_data
      height: 54
      id: '1720719111245'
      position:
        x: 1002.9688798726274
        y: 328.9250750349567
      positionAbsolute:
        x: 1002.9688798726274
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        selected: false
        template: "\n        <div class=\"section\">\n            <div class=\"section-title\"\
          >{{ title }}</div>\n            <div class=\"section-content\">\n      \
          \          {{ text }}\n                <br>\n                <a href=\"\
          {{ link }}\" class=\"read-more\">\U0001F517 Click here to read the full\
          \ article</a>\n            </div>\n        </div>\n        <div class=\"\
          divider\"></div>\n"
        title: "\u6B63\u6587 Append - \u7B2C\u4E8C / N \u6BB5"
        type: template-transform
        variables:
        - value_selector:
          - '1720719111245'
          - result1
          variable: body_origin
        - value_selector:
          - '1720720065419'
          - output
          variable: body_append
        - value_selector:
          - '1720863643271'
          - title
          variable: title
        - value_selector:
          - '1720615783929'
          - link
          variable: link
        - value_selector:
          - '1720621617132'
          - text
          variable: text
      height: 54
      id: '1720721997007'
      position:
        x: 1311.1845859077928
        y: 328.9250750349567
      positionAbsolute:
        x: 1311.1845859077928
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "def main(arg1: int, arg2: int) -> dict:\n    return {\n        \"result\"\
          : arg1 + arg2,\n    }"
        code_language: python3
        desc: ''
        outputs:
          result:
            children: null
            type: string
        selected: false
        title: "Html \u62FC\u63A5\uFF08\u66F4\u65B0\uFF09"
        type: code
        variables:
        - value_selector:
          - '1720719111245'
          - result1
          variable: arg1
        - value_selector:
          - '1720721997007'
          - output
          variable: arg2
      height: 54
      id: '1720724507619'
      position:
        x: 1602.4190111947235
        y: 328.9250750349567
      positionAbsolute:
        x: 1602.4190111947235
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "import json\n\ndef main(arg1: str) -> dict:\n    return{\n        \"\
          result\": json.dumps({\"html\": arg1})\n    }"
        code_language: python3
        desc: ''
        outputs:
          result:
            children: null
            type: string
        selected: false
        title: "JSON \u8F6C\u4E49\u6E05\u7406"
        type: code
        variables:
        - value_selector:
          - '1720724507619'
          - result
          variable: arg1
      height: 54
      id: '1720769965637'
      position:
        x: 1889.3419462849406
        y: 328.9250750349567
      positionAbsolute:
        x: 1889.3419462849406
        y: 328.9250750349567
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        selected: false
        template: "\n        <div class=\"section\">\n            <div class=\"section-title\"\
          >{{ title }}</div>\n            <div class=\"section-content\">\n      \
          \          {{ text }}\n                <br>\n                <a href=\"\
          {{ link }}\" class=\"read-more\">\U0001F517 Click here to read the full\
          \ article</a>\n            </div>\n        </div>\n        <div class=\"\
          divider\"></div>\n"
        title: "\u6B63\u6587 Append - \u7B2C\u4E00\u6BB5"
        type: template-transform
        variables:
        - value_selector:
          - '1720719111245'
          - result1
          variable: body_origin
        - value_selector:
          - '1720720065419'
          - output
          variable: body_append
        - value_selector:
          - '1720863643271'
          - title
          variable: title
        - value_selector:
          - '1720615783929'
          - link
          variable: link
        - value_selector:
          - '1720621617132'
          - text
          variable: text
      height: 54
      id: '17207717259350'
      position:
        x: 1303.9221987183487
        y: 637.6742207415048
      positionAbsolute:
        x: 1303.9221987183487
        y: 637.6742207415048
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "def main(arg1: int, arg2: int) -> dict:\n    return {\n        \"result\"\
          : arg1 + arg2,\n    }"
        code_language: python3
        desc: ''
        outputs:
          result:
            children: null
            type: string
        selected: false
        title: "Html \u62FC\u63A5\uFF08\u65B0\u589E\uFF09"
        type: code
        variables:
        - value_selector:
          - '1720672659201'
          - output
          variable: arg1
        - value_selector:
          - '17207717259350'
          - output
          variable: arg2
      height: 54
      id: '17207717498450'
      position:
        x: 1606.2405348196378
        y: 637.6742207415048
      positionAbsolute:
        x: 1606.2405348196378
        y: 637.6742207415048
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "import json\n\ndef main(arg1: str) -> dict:\n    return{\n        \"\
          result\": json.dumps({\"html\": arg1})\n    }"
        code_language: python3
        desc: ''
        outputs:
          result:
            children: null
            type: string
        selected: false
        title: "JSON \u8F6C\u4E49\u6E05\u7406"
        type: code
        variables:
        - value_selector:
          - '17207717498450'
          - result
          variable: arg1
      height: 54
      id: '17207718235970'
      position:
        x: 1893.163469909855
        y: 637.6742207415048
      positionAbsolute:
        x: 1893.163469909855
        y: 637.6742207415048
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 250
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 2\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"RSS \u66F4\u65B0\u89E6\u53D1\u672C Workflow API\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"listitem\",\"version\":1,\"value\":1},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"\u628A link\
          \ \u7ED9\u5230 JinaReader \u62FF\u5168\u6587\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\"\
          ,\"version\":1,\"value\":2},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\u6309\u7167\u67D0\u79CD\u65B9\
          \u5F0F\u8FDB\u884C\u6458\u8981\uFF08\u6709\u5F88\u591A\u73A9\u6CD5\uFF0C\
          \u770B\u4F60\u5E0C\u671B\u600E\u4E48\u6458\u8981\u54AF\uFF09\u6539\u4E00\
          \u4E0B\u8FD9\u4E2A\u8282\u70B9\u7684\u63D0\u793A\u8BCD\u5C31\u597D\u4E86\
          \u3002\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":3},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"\u6216\u8005\u5982\u679C\u4F60\u60F3\u518D\u5F04\u590D\u6742\
          \u4E00\u70B9\uFF0C\u90A3\u4F60\u8FD8\u53EF\u4EE5\u591A\u52A0\u51E0\u4E2A\
          \ LLM \u8282\u70B9\u6765\u8FDB\u884C\u66F4\u590D\u6742\u7684\u8F93\u51FA\
          \u3002\uFF08\u968F\u4F60\uFF5E\uFF09\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"\
          version\":1,\"value\":4}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"list\",\"version\":1,\"listType\":\"bullet\",\"start\":1,\"\
          tag\":\"ul\"}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"root\",\"version\":1}}"
        theme: blue
        title: ''
        type: ''
        width: 243
      height: 250
      id: '1720772018774'
      position:
        x: 372.6720045745774
        y: 445.58547617606234
      positionAbsolute:
        x: 372.6720045745774
        y: 445.58547617606234
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 243
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 652
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 1\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"\u56E0\u4E3A\u6BCF\u6B21\u66F4\u65B0\u90FD\u89E6\u53D1\
          \ Workflow \u8FDB\u884C\u6458\u8981\uFF0C\u4F46\u5E76\u4E0D\u662F\u66F4\u65B0\
          \u4E00\u7BC7\u6587\u7AE0\u5C31\u8981\u53D1\u9001\u4E00\u5219\u90AE\u4EF6\
          \uFF0C\u56E0\u6B64\u6211\u4EEC\u53EF\u4EE5\u501F\u52A9\u5916\u90E8\u98DE\
          \u4E66\u591A\u7EF4\u8868\u683C\u4F5C\u4E3A\u4E2D\u8F6C\u5B58\u50A8\u3002\
          \",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\
          \",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":1},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u6709\u5F88\u591A\u79CD\u65B9\u6CD5\uFF0C\u5F53\u7136\u4F60\u4E5F\u80FD\
          \u4F7F\u7528 Notion\uFF0C\u5176\u4ED6\u7B14\u8BB0\u8F6F\u4EF6\uFF0C\u6216\
          \u8005\u662F\u6570\u636E\u5E93\u3002\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"\
          version\":1,\"value\":2},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"\u5728\u8FD9\u4E2A\u4F8B\u5B50\u4E2D\
          \uFF0C\u98DE\u4E66\u7684 tenant_access_token \u5B58\u5728 2 \u5C0F\u65F6\
          \u6709\u6548\u671F\uFF0C\u5982\u679C\u6211\u4EEC\u76F4\u63A5\u5199\u6B7B\
          \ token \u5C31\u4F1A\u5BFC\u81F4\u62A5\u9519\uFF0C\u6240\u4EE5\u6211\u4EEC\
          \u501F\u52A9\u98DE\u4E66\u83B7\u53D6 token \u7684 api \u6765\u6301\u7EED\
          \u83B7\u5F97\u6700\u65B0 token\u3002\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"\
          version\":1,\"value\":3},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"\u53C2\u8003\u6587\u6863\uFF1Ahttps://open.feishu.cn/document/server-docs/authentication-management/access-token/tenant_access_token_internal\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":4},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u90A3\u4E48\u8FD9\u4E2A app_id \u548C app_secret \u600E\u4E48\u62FF\u5462\
          \uFF1F\u53BB\u4E0A\u9762\u8FD9\u4E2A\u6587\u6863\uFF0C\u53F3\u4E0A\u89D2\
          \u70B9\u51FB\u300C\u5F00\u53D1\u8005\u540E\u53F0\u300D\uFF0C\u521B\u5EFA\
          \u4F01\u4E1A\u81EA\u5EFA\u5E94\u7528\u3002\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\"\
          ,\"version\":1,\"value\":5},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\u203C\uFE0F \u91CD\u8981 1\uFF1A\
          \u70B9\u51FB\u6743\u9650\u7BA1\u7406\uFF0C\u8981\u628A\u591A\u7EF4\u8868\
          \u683C\u7684\u6743\u9650\u5F00\u7740 ->\u300C\u67E5\u770B\u3001\u8BC4\u8BBA\
          \u3001\u7F16\u8F91\u548C\u7BA1\u7406\u591A\u7EF4\u8868\u683C\u300D\u548C\
          \u300C\u67E5\u770B\u3001\u8BC4\u8BBA\u548C\u5BFC\u51FA\u591A\u7EF4\u8868\
          \u683C\u300D\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"\
          format\":\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\"\
          :6},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"\u203C\uFE0F \u91CD\u8981 2\uFF1A\u65B0\u5EFA\u4E00\u4E2A\
          \u591A\u7EF4\u8868\u683C\uFF0C\u7136\u540E\u70B9\u51FB\u53F3\u4E0A\u89D2\
          \u7684\u4E09\u4E2A\u5C0F\u70B9 icon -> \u66F4\u591A -> \u6DFB\u52A0\u6587\
          \u6863\u5E94\u7528\u3002\u641C\u7D22\u628A\u4F60\u7684 App \u6DFB\u52A0\u8FDB\
          \u53BB\uFF0C\u624D\u7B97\u53EF\u4EE5\u6B63\u5E38\u5BF9\u6B64\u591A\u7EF4\
          \u8868\u683C\u8FDB\u884C\u64CD\u4F5C\u3002\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\"\
          ,\"version\":1,\"value\":7}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"list\",\"version\":1,\"listType\":\"bullet\",\"start\":1,\"\
          tag\":\"ul\"}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"root\",\"version\":1}}"
        theme: blue
        title: ''
        type: ''
        width: 247
      height: 652
      id: '1720772035174'
      position:
        x: 65.81659914734007
        y: 569.6878314571908
      positionAbsolute:
        x: 65.81659914734007
        y: 569.6878314571908
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 247
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 311
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 3\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"\u62FF\u5230 token \u5C31\u53EF\u4EE5\u67E5\u8BE2\u6570\
          \u636E\u4E86\u3002\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"\
          value\":1},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"\u6D4F\u89C8\u5668\u6253\u5F00\u4F60\u7684\u591A\
          \u7EF4\u8868\u683C\uFF0C\u7136\u540E\u590D\u5236\u770B\u770B\u4F60\u7684\
          \u591A\u7EF4\u8868\u683C\u94FE\u63A5\u3002\u5927\u6982\u7C7B\u4F3C\u4E8E\
          \uFF1Ahttps://example.feishu.cn/base/blabla?table=clacla&view=dladla\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":2},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u591A\u7EF4\u8868\u683C\u7684\u552F\u4E00\u6807\u8BC6\u7B26 app_token\uFF0C\
          \u6307\u7684\u662F blabla \u8FD9\u4E00\u4E32\u5B57\u7B26\u4E32\u3002\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":3},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u591A\u7EF4\u8868\u683C\u7684\u6570\u636E\u8868\u6307\u7684\u662F clacla\
          \ \u8FD9\u4E00\u4E32\u3002\u590D\u5236\u7C98\u8D34\u5230\u4E0A\u9762\u7684\
          \u300C\u67E5\u8BE2\u300D\u8282\u70B9\u91CC\u3002\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"listitem\",\"version\":1,\"value\":4}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"list\",\"version\":1,\"listType\":\"bullet\"\
          ,\"start\":1,\"tag\":\"ul\"}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"root\",\"version\":1}}"
        theme: blue
        title: ''
        type: ''
        width: 244
      height: 311
      id: '1720772309300'
      position:
        x: 690.0626111181598
        y: 657.8670054766783
      positionAbsolute:
        x: 690.0626111181598
        y: 657.8670054766783
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 244
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 521
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 4\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"\u65E5\u671F\u83B7\u53D6\uFF0C\u7528\u4E8E\u5199\u5728\
          \ html \u90AE\u4EF6\u91CC\uFF08\u6700\u9876\u4E0A\uFF09\u4EE3\u7801\u8282\
          \u70B9\u7684\u90A3\u4E2A arg1 \u4E0D\u7528\u7BA1\uFF0C\u662F\u56E0\u4E3A\
          \ Dify \u4EE3\u7801\u8282\u70B9\u5FC5\u987B\u8981\u6709\u4E00\u4E2A\u8F93\
          \u5165\u624D\u4E0D\u4F1A\u62A5\u9519\uFF08\u4F46\u5B9E\u9645\u4E0A\u8FD9\
          \u91CC\u83B7\u53D6\u65F6\u95F4\u6211\u4EEC\u7528\u4E0D\u7740\u8F93\u5165\
          \u53D8\u91CF\u3002\uFF09\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"version\"\
          :1,\"value\":1},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"\u7136\u540E\u4FEE\u6539\u90AE\u4EF6\u6807\u9898\
          \u6A21\u7248\u3002\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"\
          value\":2},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"\u7406\u8BBA\u4E0A\u5927\u5BB6\u4E0D\u5E94\u8BE5\
          \u624B\u52A8\u53BB\u78B0\u8FD9\u4E2A\u591A\u7EF4\u8868\u683C\uFF0C\u6240\
          \u4EE5\u5982\u679C\u6CA1\u6709\u5F53\u5929\u7684\u8BB0\u5F55\uFF0C\u5C31\
          \u4F1A\u81EA\u52A8\u628A\u6211\u4EEC\u7684 html \u6A21\u7248\u7B2C\u4E00\
          \u90E8\u5206 + \u6B63\u6587\u7B2C\u4E00\u6BB5\u6DFB\u52A0\u5230\u4E00\u6761\
          \u65B0\u589E\u7684\u591A\u7EF4\u8868\u683C\u8BB0\u5F55\u91CC\u3002\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":3},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u53CD\u4E4B\uFF0C\u5219\u8FDB\u5165\u4E0A\u9762\u7684\u5206\u652F\uFF0C\
          \u5148\u67E5\u8BE2\u539F\u6765\u7684\u8BB0\u5F55\uFF0C\u7136\u540E\u518D\
          \u540E\u9762 append \u6DFB\u52A0\u4E0A\u65B0\u7684 RSS \u8BB0\u5F55\u7684\
          \u6587\u7AE0\u7684\u6458\u8981\uFF0C\u4EE5\u66F4\u65B0 html\u3002\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"listitem\",\"version\":1,\"value\":4},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"\u4E0D\u8FC7\
          \u6700\u540E\u7684\u9875\u811A\u6211\u4EEC\u6682\u65F6\u4E0D\u7BA1\uFF0C\
          \u56E0\u4E3A\u5B83\u5E94\u8BE5\u662F\u5B9A\u65F6\u89E6\u53D1\uFF08\u53D1\
          \u9001\u65E5\u62A5\uFF09\u7684\u65F6\u5019\u624D\u53BB\u5C01\u88C5\u7684\
          \uFF0C\u5728\u53E6\u5916\u4E00\u5957 workflow \u91CC\u3002\uFF08\u53D1\u9001\
          [\u6628\u65E5]\u65E5\u62A5 workflow\uFF09\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\"\
          ,\"version\":1,\"value\":5},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\u6211\u4EEC\u53EF\u4EE5\u501F\
          \u52A9 iPhone \u81EA\u5E26\u7684 Shortcuts \u505A\u4E00\u4E2A\u5B9A\u65F6\
          \u4EFB\u52A1\uFF0C\u4F8B\u5982\u6BCF\u5929 10:00 \u53D1\u9001\u65E5\u62A5\
          \u3002\uFF08\u4E00\u4E2A post\uFF09\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"\
          version\":1,\"value\":6}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"list\",\"version\":1,\"listType\":\"bullet\",\"start\":1,\"\
          tag\":\"ul\"}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"root\",\"version\":1}}"
        theme: blue
        title: ''
        type: ''
        width: 244
      height: 521
      id: '1720774020912'
      position:
        x: 1006.7904034975418
        y: 717.0471418599145
      positionAbsolute:
        x: 1006.7904034975418
        y: 717.0471418599145
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 244
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 172
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 6\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"\u8FD9\u91CC\u8981\u6CE8\u610F\u4E00\u4E0B\uFF0C\u98DE\u4E66\
          \u7684\u8FD9\u4E24\u4E2A\u8282\u70B9\uFF08\u66F4\u65B0\u8282\u70B9\uFF09\
          \",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\
          \",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":1},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u4F8B\u5982\uFF1A\u300C\u6570\u636E\u8868\u7684\u5217\u5B57\u6BB5\u5185\
          \u5BB9\u300D\u8FD9\u4E00\u4E2A\u5B57\u6BB5\uFF0C\u4E0B\u9762\u6700\u597D\
          \u4E0D\u8981\u81EA\u5DF1\u5199\uFF1A{\\\"\u5B57\u6BB5\u540D\\\":\\\"Dify\
          \ \u8282\u70B9\u53D8\u91CF\\\"}\uFF0C\u8FD9\u6837\u4F1A\u51FA\u73B0\u4E00\
          \u4E9B\u6BD4\u8F83\u96BE\u641E\u7684 JSON \u8F6C\u4E49\u95EE\u9898\u3002\
          \",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\
          \",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":2},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"\u89E3\u51B3\u65B9\u6CD5\u662F\uFF1A\u5728\u524D\u9762\u6DFB\u52A0\u4E00\
          \u4E2A html \u8F6C\u4E49\u8282\u70B9\uFF0C\u76F4\u63A5 dumps \u8FD4\u56DE\
          \u5B8C\u6574\u7684\u8F6C\u4E49\u540E\u7684 JSON\u3002\u611F\u8C22 \",\"\
          type\":\"text\",\"version\":1},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"@Yeuoly\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"link\",\"version\":1,\"rel\":\"noreferrer\",\"target\":null,\"title\"\
          :null,\"url\":\"https://x.com/Yeuoly1\"}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":3}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"list\",\"version\"\
          :1,\"listType\":\"bullet\",\"start\":1,\"tag\":\"ul\"}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"root\",\"version\":1}}"
        theme: yellow
        title: ''
        type: ''
        width: 537
      height: 172
      id: '1720774242794'
      position:
        x: 1896.974598090564
        y: 732.3332363595729
      positionAbsolute:
        x: 1896.974598090564
        y: 732.3332363595729
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 537
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 174
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 5\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"html \u6A21\u7248\uFF0C\u5C31\u4E0D\u591A\u89E3\u91CA\u4E86\
          \u3002\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":1},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"\u4E24\u7AEF\u62FC\u63A5\u5230\u4E00\u8D77\u5C31\u662F\u5B8C\
          \u6574\u7684 html\u3002\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"listitem\",\"version\"\
          :1,\"value\":2}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"list\",\"version\":1,\"listType\":\"bullet\",\"start\":1,\"tag\":\"ul\"\
          }],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"root\"\
          ,\"version\":1}}"
        theme: pink
        title: ''
        type: ''
        width: 545
      height: 174
      id: '1720774257209'
      position:
        x: 1307.7333268990578
        y: 732.3332363595729
      positionAbsolute:
        x: 1307.7333268990578
        y: 732.3332363595729
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 545
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 370
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC \u6211\u7684 html\
          \ \u5B8C\u6574\u6A21\u7248\u793A\u8303\uFF0C\u4F60\u53EF\u4EE5\u590D\u5236\
          \u5230\u4EE3\u7801\u7F16\u8F91\u5668\u91CC\u67E5\u770B \U0001F447\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"---<!DOCTYPE html>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"<html lang=\\\"en\\\">\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"<head>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"    <meta charset=\\\"UTF-8\\\">\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"    <meta name=\\\"viewport\\\
          \" content=\\\"width=device-width, initial-scale=1.0\\\">\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"    <title>\U0001F48C Daily Newsletter</title>\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"    <style>\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        body {\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            font-family: Arial, sans-serif;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            color: #fff;\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            background-color:\
          \ #000;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            margin: 0;\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            padding: 0;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        .container {\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            width: 100%;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            max-width: 600px;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            margin: 0 auto;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            padding: 20px;\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            box-sizing:\
          \ border-box;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\"\
          ,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        .content-wrapper {\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   padding: 0 20px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"\
          direction\":null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"\
          version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"        .header-image {\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            width: 100%;\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            max-width: 600px;\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            height: auto;\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            border-radius: 12px;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            margin-bottom: 10px;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\",\"type\":\"\
          text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"indent\":0,\"\
          type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"\
          detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\" \
          \       .section {\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"            margin: 32px 0;\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        .section-title {\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            font-size: 24px;\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            font-weight: bold;\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            margin: 0 0\
          \ 10px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            word-wrap: break-word;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            color: #ff0000\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        .section-content {\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   font-size: 16px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"            line-height: 1.5;\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   margin: 0 0 10px;\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            word-wrap: break-word;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        .divider {\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            border-bottom:\
          \ 1px solid #ff0000;\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"            margin: 20px 0;\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        .email-date {\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            text-align: center;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            color: #888888;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            font-size:\
          \ 14px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            margin-bottom: 20px;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            margin-top:\
          \ 20px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        .email-title {\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   text-align: center;\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            font-size: 24px;\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            font-weight: bold;\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            margin-bottom:\
          \ 30px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            word-wrap: break-word;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\",\"type\":\"\
          text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"indent\":0,\"\
          type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"\
          detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\" \
          \       .footer-divider {\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            width: 100px;\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            height: 10px;\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            background-image: url(\\\
          \"data:image/svg+xml,%3Csvg width='100' height='10' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath\
          \ d='M0 5 Q 10 0, 20 5 T 40 5 T 60 5 T 80 5 T 100 5' fill='none' stroke='%23eeeeee'\
          \ stroke-width='2'/%3E%3C/svg%3E\\\");\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            background-repeat:\
          \ repeat-x;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"\
          format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"            margin: 30px auto;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\",\"type\":\"\
          text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"indent\":0,\"\
          type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"\
          detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\" \
          \       .page-footer {\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"            text-align: center;\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            color: #888888;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            font-size:\
          \ 16px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            line-height: 1.5;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            margin-top:\
          \ 20px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            word-wrap: break-word;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"        }\",\"type\":\"\
          text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"indent\":0,\"\
          type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"\
          detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\" \
          \       @media (max-width: 600px) {\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            .container\
          \ {\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"                padding: 10px;\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            }\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":null,\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            .content-wrapper {\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"                padding:\
          \ 0 15px;\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"            }\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        }\",\"type\":\"text\",\"version\":1}],\"\
          direction\":null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"\
          version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"    </style>\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"</head>\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"<body>\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"    <div class=\\\"container\\\">\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        <div class=\\\"email-date\\\">{{ date }}</div>\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        <div class=\\\"email-title\\\">{{ email_title }}</div>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        <img src=\\\"...your cover image url here...\\\">\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        \",\"type\":\"text\",\"version\":1}],\"direction\":null,\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        <div class=\\\"section\\\">\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-title\\\">WE ARE EXPANSIVE</div>\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-date\\\">01-Jan-2024</div>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <br>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            <div class=\\\"section-content\\\">\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque\
          \ sed bibendum ex. Fusce turpis metus, venenatis vel dui a, eleifend luctus\
          \ augue. Aenean porttitor luctus odio imperdiet pharetra.\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"                <br>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"                <br>\",\"type\":\"\
          text\",\"version\":1},{\"type\":\"linebreak\",\"version\":1},{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \       <a href=\\\"{{ link }}\\\" class=\\\"read-more\\\">\U0001F517 Click\
          \ here to read the full article</a>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            </div>\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        </div>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\"\
          ,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"        <div class=\\\"divider\\\"></div>\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"type\":\"linebreak\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        <div class=\\\"section\\\">\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-title\\\">WE ARE INCLUSIVE</div>\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-date\\\">02-Jan-2024</div>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <br>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            <div class=\\\"section-content\\\">\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque\
          \ sed bibendum ex. Fusce turpis metus, venenatis vel dui a, eleifend luctus\
          \ augue. Aenean porttitor luctus odio imperdiet pharetra.\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"                <br>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"                <br>\",\"type\":\"\
          text\",\"version\":1},{\"type\":\"linebreak\",\"version\":1},{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \       <a href=\\\"{{ link }}\\\" class=\\\"read-more\\\">\U0001F517 Click\
          \ here to read the full article</a>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            </div>\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        </div>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\"\
          ,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"        <div class=\\\"divider\\\"></div>\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"type\":\"linebreak\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        <div class=\\\"section\\\">\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-title\\\">WE ARE RESILIENT</div>\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <div class=\\\
          \"section-date\\\">03-Jan-2024</div>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            <br>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            <div class=\\\"section-content\\\">\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque\
          \ sed bibendum ex. Fusce turpis metus, venenatis vel dui a, eleifend luctus\
          \ augue. Aenean porttitor luctus odio imperdiet pharetra.\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"                <br>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"                <br>\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"                <a href=\\\"{{ link }}\\\" class=\\\"read-more\\\">\U0001F517\
          \ Click here to read the full article</a>\",\"type\":\"text\",\"version\"\
          :1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"            </div>\",\"\
          type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"\
          indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"        </div>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\"\
          ,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"        <div class=\\\"divider\\\"></div>\",\"type\":\"\
          text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"type\":\"linebreak\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        <div class=\\\"footer-divider\\\"></div>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"type\":\"linebreak\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"        <footer class=\\\"page-footer\\\">\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   <p>\U0001F44B Hey there! I'm your AI friend Lucky (Powered By Dify)\
          \ \U0001F340 . I hope this summary was helpful and brightened your day!\
          \ Remember, every day is a new opportunity to learn and grow. Stay curious!\
          \ \U0001F331\u2728</p>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"        </footer>\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"    </div>\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"</body>\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"</html>\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"root\",\"version\":1}}"
        theme: violet
        title: ''
        type: ''
        width: 531
      height: 370
      id: '1720774565522'
      position:
        x: 1318.8172377134163
        y: -61.26615155369237
      positionAbsolute:
        x: 1318.8172377134163
        y: -61.26615155369237
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 531
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 364
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC \u6216\u8005\uFF0C\
          \u4F60\u53EA\u5173\u5FC3\u6B63\u6587\u672C\u5206\u7684 html \u6A21\u7248\
          \u3002\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"\u53EF\u4EE5\u770B\u5230\uFF0C\u5728 section-xxx\
          \ \u90E8\u5206\uFF0C\u5206\u522B\u5E26\u5165 dify \u8282\u70B9\u4E2D\u7684\
          \u53D8\u91CF\u5373\u53EF\uFF08\u4E00\u5F00\u59CB\u8F93\u5165\u7684 title\u3001\
          link\u3001date\uFF0C\u4EE5\u53CA LLM \u603B\u7ED3\u7684 Summary\uFF09\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"listitem\",\"version\":1,\"value\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"list\",\"version\":1,\"\
          listType\":\"bullet\",\"start\":1,\"tag\":\"ul\"},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"---\",\"type\"\
          :\"text\",\"version\":1},{\"type\":\"linebreak\",\"version\":1}],\"direction\"\
          :null,\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"        <div class=\\\"section\\\">\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            <div class=\\\"section-title\\\">{{ title }}</div>\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\"\
          :\"            <br>\",\"type\":\"text\",\"version\":1}],\"direction\":\"\
          ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"\
          textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\"\
          ,\"style\":\"\",\"text\":\"            <div class=\\\"section-content\\\"\
          >\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\
          \",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"                {{ text }}\",\"type\":\"text\",\"version\":1}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\"\
          ,\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\"\
          :0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"                <br>\"\
          ,\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\"\
          ,\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"\
          children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\":\"\"\
          ,\"text\":\"                <a href=\\\"{{ link }}\\\" class=\\\"read-more\\\
          \">\U0001F517 Click here to read the full article</a>\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\":[{\"detail\"\
          :0,\"format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"         \
          \   </div>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"\
          format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\"\
          :0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"        </div>\",\"type\":\"text\",\"version\":1}],\"direction\"\
          :\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"paragraph\",\"version\"\
          :1,\"textFormat\":0},{\"children\":[{\"detail\":0,\"format\":0,\"mode\"\
          :\"normal\",\"style\":\"\",\"text\":\"        <div class=\\\"divider\\\"\
          ></div>\",\"type\":\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0}],\"\
          direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\":\"root\",\"version\"\
          :1}}"
        theme: blue
        title: ''
        type: ''
        width: 533
      height: 364
      id: '1720774704632'
      position:
        x: 1896.974598090564
        y: -61.26615155369237
      positionAbsolute:
        x: 1896.974598090564
        y: -61.26615155369237
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 533
    - data:
        desc: ''
        outputs: []
        selected: false
        title: "\u7ED3\u675F 2"
        type: end
      height: 54
      id: '1720774741080'
      position:
        x: 2463.58864259775
        y: 637.6742207415048
      positionAbsolute:
        x: 2463.58864259775
        y: 637.6742207415048
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        author: "\u83B1\u68EE LysonOber"
        desc: ''
        height: 165
        selected: false
        showAuthor: true
        text: "{\"root\":{\"children\":[{\"children\":[{\"detail\":0,\"format\":0,\"\
          mode\":\"normal\",\"style\":\"\",\"text\":\"\U0001F4CC Part 0\",\"type\"\
          :\"text\",\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"paragraph\",\"version\":1,\"textFormat\":0},{\"children\"\
          :[{\"children\":[{\"detail\":0,\"format\":0,\"mode\":\"normal\",\"style\"\
          :\"\",\"text\":\"Jina \u722C\u53D6\u5168\u6587\uFF0C\u5E76\u8F6C\u6362\u4E3A\
          \ LLM \u53CB\u597D\u7684\u8F93\u5165\u6587\u672C\u3002\",\"type\":\"text\"\
          ,\"version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"listitem\",\"version\":1,\"value\":1},{\"children\":[{\"detail\":0,\"\
          format\":0,\"mode\":\"normal\",\"style\":\"\",\"text\":\"\u4EE3\u7801\u5206\
          \u79BB title \u548C body\uFF0C\u539F\u56E0\u662F\u8BA9\u7528\u6237\u53EA\
          \u9700\u8981\u8F93\u5165 Link \u5373\u53EF\uFF0C\u800C\u4E0D\u662F\u624B\
          \u52A8\u586B\u5199\u6807\u9898\u548C\u94FE\u63A5\",\"type\":\"text\",\"\
          version\":1}],\"direction\":\"ltr\",\"format\":\"\",\"indent\":0,\"type\"\
          :\"listitem\",\"version\":1,\"value\":2}],\"direction\":\"ltr\",\"format\"\
          :\"\",\"indent\":0,\"type\":\"list\",\"version\":1,\"listType\":\"bullet\"\
          ,\"start\":1,\"tag\":\"ul\"}],\"direction\":\"ltr\",\"format\":\"\",\"indent\"\
          :0,\"type\":\"root\",\"version\":1}}"
        theme: blue
        title: ''
        type: ''
        width: 242
      height: 165
      id: '1720786358443'
      position:
        x: -244.50360799073
        y: 718.5082319854444
      positionAbsolute:
        x: -244.50360799073
        y: 718.5082319854444
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom-note
      width: 242
    - data:
        code: "from datetime import datetime\n\ndef main(arg1: str) -> dict:\n   \
          \ today = datetime.now()\n    formatted_date = today.strftime(\"%b %d, %Y\"\
          )\n    week_number = today.strftime(\"%W\")\n    return {\n        \"result1\"\
          : formatted_date,\n        \"result2\": week_number\n    }"
        code_language: python3
        desc: ''
        outputs:
          result1:
            children: null
            type: string
          result2:
            children: null
            type: string
        selected: false
        title: "\u65E5\u671F & \u5468\u6570\u83B7\u53D6"
        type: code
        variables:
        - value_selector:
          - '1720863643271'
          - title
          variable: arg1
      height: 54
      id: '1720787293636'
      position:
        x: 1006.7904034975418
        y: 478.2512874242092
      positionAbsolute:
        x: 1006.7904034975418
        y: 478.2512874242092
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        desc: ''
        selected: false
        template: "\U0001F4EC Week {{ week_number }}: Hello Lyson, daily newsletter\
          \ is here!"
        title: "\u90AE\u4EF6\u6807\u9898"
        type: template-transform
        variables:
        - value_selector:
          - '1720787293636'
          - result2
          variable: week_number
      height: 54
      id: '1720787662754'
      position:
        x: 1006.7904034975418
        y: 565.2248780673485
      positionAbsolute:
        x: 1006.7904034975418
        y: 565.2248780673485
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    - data:
        code: "import json\n\ndef main(arg1: str) -> dict:\n    # Parse the JSON string\n\
          \    data = json.loads(arg1)\n    \n    # Extract the nested JSON string\
          \ from the 'text' field\n    inner_json = json.loads(data['text'])\n   \
          \ \n    # Extract title and content from the inner JSON\n    title = inner_json['data']['title']\n\
          \    content = inner_json['data']['content']\n    \n    # Create and return\
          \ the result dictionary\n    return {\n        \"title\": title,\n     \
          \   \"body\": content\n    }"
        code_language: python3
        desc: ''
        outputs:
          body:
            children: null
            type: string
          title:
            children: null
            type: string
        selected: false
        title: "\u6807\u9898\u63D0\u53D6"
        type: code
        variables:
        - value_selector:
          - '1720672602189'
          - text
          variable: arg1
      height: 54
      id: '1720863643271'
      position:
        x: -244.50360799073
        y: 633.203234018364
      positionAbsolute:
        x: -244.50360799073
        y: 633.203234018364
      selected: false
      sourcePosition: right
      targetPosition: left
      type: custom
      width: 244
    viewport:
      x: -643.6511989766176
      y: 182.93529408378902
      zoom: 0.46614953924785246


