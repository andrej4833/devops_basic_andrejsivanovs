# Atbildes uz jautājumiem

13)Git redz atšķirības starp failiem

```sh
$ git ls-files -s
100644 6a7a0224496fce7d0087e5a6bbddc774ac111b67 0       README.md
100644 1ee93706916567832fff81b1cb2d1097da7a7b3d 0       module_1/Foto1.png
100644 21a5750d1b53996ee83bd825f21267a8991c3c87 0       module_1/README.md
100644 1ee93706916567832fff81b1cb2d1097da7a7b3d 0       module_2/Foto1.png
100644 a2302ee5dc8c9b3ab3c8b33c0540b26e52dd3890 0       module_2/README.md
```

16)veidi kā atradu izmaiņas 

- git prijektā sadaļā commits (https://github.com/hashicorp/terraform/commits/main)
- rakstot terminālā git log --after="2022-4-17"

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

21) Tika izveidots 16.apr, bet atjaunots 20.apr. 

```sh
$ git log --after="2021-4-20" --before="2021-4-21" --reverse --pretty=fuller

commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
Author:     James Bardin <j.bardin@gmail.com>
AuthorDate: Fri Apr 16 17:11:27 2021 -0400
Commit:     James Bardin <j.bardin@gmail.com>
CommitDate: Tue Apr 20 17:04:56 2021 -0400

    update hcl

    update to v2.10.0
```