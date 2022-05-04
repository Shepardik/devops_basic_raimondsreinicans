C:\Users\shepa>ssh-keygen -t ed25519 -C "<Atslega darbam ar repozitoriju WebLapas>"
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\shepa/.ssh/id_ed25519):
Created directory 'C:\Users\shepa/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\shepa/.ssh/id_ed25519.
Your public key has been saved in C:\Users\shepa/.ssh/id_ed25519.pub.
The key fingerprint is:
SHA256:h9GoDgVWnBGk3+lXxsT+ZK4Ub5mm31n/SygkL49jEA4 <Atslega darbam ar repozitoriju WebLapas>
The key's randomart image is:
+--[ED25519 256]--+
|    o+=+         |
|   . oo  o .     |
|    . . o . o    |
|     E + + +     |
|    . = S...* o  |
|     o + .+o B.o |
|      . o..o..O..|
|         ++..=..+|
|        ....o..o*|
+----[SHA256]-----+



https://github.com/Shepardik/devops_basic_raimondsreinicans/tree/master


PS C:\DevOps\git_repos> git log --stat
commit 35b16e964a8b6843c0ca99891cbc1de63a5362d6 (HEAD -> master, origin/master)
Author: Raimonds <raimonds.reinicans@gmail.com>
Date:   Fri Apr 29 09:28:50 2022 +0300

    module 2

 module_2/1.jpg     | Bin 0 -> 2902861 bytes
 module_2/README.md |   0
 2 files changed, 0 insertions(+), 0 deletions(-)

commit ae7d94a1d0a68c687fa25ac7108c1b9ab369dd38
Author: Raimonds <raimonds.reinicans@gmail.com>
Date:   Fri Apr 29 09:07:41 2022 +0300

    Link fix

 module_1/README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

commit ac68a3a0183f2ec3ccb4ece486ac59d795d2f0bb
Author: Raimonds <raimonds.reinicans@gmail.com>
Date:   Fri Apr 29 09:03:46 2022 +0300

    ADD PIC

 module_1/README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

commit 2751833cd7039fe05c8ee260e011856ff6100c7b
Author: Raimonds <raimonds.reinicans@gmail.com>
Date:   Fri Apr 29 08:47:16 2022 +0300




module_1/1.jpg
commit 2751833cd7039fe05c8ee260e011856ff6100c7b

module_2/1.jpg
35b16e964a8b6843c0ca99891cbc1de63a5362d6


lAURA

PS C:\DevOps\git_repos\terraform> git log --author="Laura"
commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400

    more edits

commit 912e6ff6de5d79bdd5e0ea3672817be3f12d9779
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:54:50 2022 -0400

    Apply suggestions from PR review

commit a0ebb94fb598a5822fdab6c6575fae55f3a8efff
Merge: 201c9168f 2f7aa2fcb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:40:26 2022 -0400

    Merge branch 'main' into update-TF-WORKSPACE-variable

commit d3e660d91272c239350f0cf9a01ca94c7437f775
Merge: eb2724d37 b1d933936
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:25:43 2022 -0400

    Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions

    [WIP] Preconditions and Postconditions Content Updates

commit b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:19:29 2022 -0400

    Final formatting nits

commit 3c7c5bbd21dc32fa650c2b3505c77315838421aa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:06:50 2022 -0400

    add links to function and expressions; move result types back to conditionals page (oops)

commit 2a206c7984573d054c1dd6ea2b7eb2a733da01be
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:49:33 2022 -0400

    fix incorrect HCL syntax for example

commit 7a43db405c8da55f918b64b37aae59be2a8180b7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:46:37 2022 -0400

    Add link to operators page and all out other types

commit ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:30:20 2022 -0400

    Apply suggestions from PR review

commit 686dbcdb8dfcf45b2063bb28960310b243847614
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:24:23 2022 -0400

    fix confusing sentence on lifecycle page

commit 4d4d774aef4a7abbc77b0c951e2f124af1a2327c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:23:15 2022 -0400

    fix confusing sentence on resources page

commit ce757244f284a8270210b6dd85bea554a9fb5b7f



PS C:\DevOps\git_repos\terraform> git log --pretty=format:"%ad - %an: %s" --after="2021-09-01" --until="2021-09-31" --author="Laura"
Mon Sep 20 17:24:31 2021 -0400 - Laura Pacilio: Merge pull request #29567 from drasko95/patch-1
Thu Sep 16 17:30:37 2021 -0400 - Laura Pacilio: Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar
Thu Sep 16 17:11:31 2021 -0400 - Laura Pacilio: Fix alphabetical order of sidebar
Thu Sep 16 17:06:52 2021 -0400 - Laura Pacilio: Add Machine-Readable UI to sidebar and add hyphen :-)
Mon Sep 13 10:39:02 2021 -0400 - Laura Pacilio: Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key
Thu Sep 9 15:09:31 2021 -0400 - Laura Pacilio: Merge pull request #28579 from ChadBailey/patch-2
Thu Sep 9 14:54:17 2021 -0400 - Laura Pacilio: Merge pull request #29451 from kmadof/patch-1
Thu Sep 9 11:06:58 2021 -0400 - Laura Pacilio: Merge pull request #29502 from hashicorp/alisdair/json-format-version
Fri Sep 3 12:11:34 2021 -0400 - Laura Pacilio: Merge pull request #29509 from drewmullen/d-module-source-revision-option
Fri Sep 3 10:19:30 2021 -0400 - Laura Pacilio: Merge pull request #28345 from yvespp/destroy_provisioners_doc
Thu Sep 2 14:47:38 2021 -0400 - Laura Pacilio: Merge pull request #28334 from paultyng/patch-1



PS C:\DevOps\git_repos\terraform> git log --pretty=format:"%ad - %an: %s" --after="2022-05-03" --until="2022-05-03" --author="Laura"
PS C:\DevOps\git_repos\terraform>
