# Atbildes uz jautājumiem

16)1. veids - atradu izmaiņas git prijektā sadaļā commits (https://github.com/hashicorp/terraform/commits/main)

2. veids - rakstot terminālā git log --after="2022-4-17"

17)Komitus kurus veic “Laura Pacilio” atrod ar git log --author=“Laura Pacilio”

18)Kommit kurus "Laura Pacilio" veica pagājušā gada septembrī 

```sh
git log --author="Laura Pacilio" --after="2021-9-1" --before="2021-9-31" --reverse
```
```sh
commit 73a3bb27029054a0c14f2aef8081900bf821c809
Merge: 05f21cdff b8a0929a5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 2 14:47:38 2021 -0400

    Merge pull request #28334 from paultyng/patch-1

    Add null to type conversion docs
```

19) Nav