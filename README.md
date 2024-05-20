# mermaid-test
``` mermaid

sequenceDiagram
    participant Alice
    participant John
    link Alice: Dashboard @ https://dashboard.contoso.com/alice
    link Alice: Wiki @ https://wiki.contoso.com/alice
    link John: Dashboard @ https://dashboard.contoso.com/john
    link John: Wiki @ https://wiki.contoso.com/john
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```


```mermaid
flowchart TD;
src(" preprod+prod
_(state#160; on#160; main#160; branch) _*")
dst1 ("'ga-a'")
src ->|‹a href='https://build.prod.pcln.com/api/v5/promote/overwrite/img+cfg/pipeline/demo-ak/src/preprod+prod/dst/qa-a/1v1/4'>IMAGE + CONFIG</a>| dst1
src ->|‹a href='https://build.prod.pcln.com/api/v5/promote/overwrite/cfg/pipeline/demo-ak/src/preprod+prod/dst/qa-a/lv1/4'>CONFIG</a>| dst1
dst2 ("'qa-b'")
```
