---
sidebar_position: 1
---

# Linux Kernel Intro

Linux Kernel 是一款 Unix-like 免費的開源作業系統核心，由 Linus Torvalds 建立的專案。第一次 [公開釋出](https://www.oldlinux.org/Linus/) 在 1991 年，由於當時沒有一款免費+開源的作業系統，所以短時間內吸引很多開發者加入。目前是世界上最主流的嵌入式裝置、伺服器、手機作業系統之一。

Linux Kernel 作為一開始就也有目標學習目的的作業系統，其中 [Linux-0.12](https://github.com/ultraji/linux-0.12) 及 [Linux-2.6](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux-2.6.git
) 這兩個版本(僅是自己有接觸到的，一定還有更多），有作者整理學習資源及教學，讓複雜的系統更容易被學習、理解。

Linux Kernel 位置處於電腦軟體跟硬體的溝通層，所以相關知識可能可以涉及硬體、韌體、軟體，所以閱讀本系列如果發現開始越來越多不理解的名詞或概念，可以往以下領域/科目去閱讀：作業系統(OS)、編譯器(Compiler)、計算機組織(組合語言)、CPU(ISA)。表面上看起來要能夠自己開始做專案的知識量大且艱深，但經過一段時間(一兩年)研讀後
覺得還是有條入門路徑。自己便嘗試以邊學習邊整理的方式，紀錄一條自己經過的學習/知識路線！

這個系列文，主軸會以 Tobert Love 所寫的 [內核設計與實現(3rd)](https://www.books.com.tw/products/CN10762012)的章節排序為進程，加上很多很棒的閱讀素材及一些小的專案實作。

---

The Linux Kernel is a free and open-source Unix-like operating system kernel, created by Linus Torvalds. Its [first release]((https://www.oldlinux.org/Linus/))
 was back in 1991. At that time, there wasn’t really a free and open-source OS, so the project quickly attracted lots of developers. Today, the Linux Kernel powers many of the world’s most common platforms—embedded devices, servers, and even mobile phones.

Besides being a real-world OS, Linux has also been a great learning resource. Versions like [Linux-0.12]((https://github.com/ultraji/linux-0.12))
 and [Linux-2.6](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux-2.6.git
)
 (these are the ones I’ve personally tried, but there are many more) have tutorials and resources put together by the community, which makes this huge system a lot easier to study and understand.

The Kernel sits right between software and hardware—it’s basically the layer that lets them talk to each other. Because of this, learning Linux often touches different areas: hardware, firmware, and software. If you ever feel stuck because of unfamiliar terms, it might help to look into related topics like Operating Systems (OS), Compilers, Computer Architecture (assembly), or CPU design (ISA).

At first, it looks like you need to master a huge amount of deep knowledge before you can do anything hands-on. But after spending some time studying, I realized there is actually a doable entry path. So, in this series, I’ll try to document my own learning journey and the knowledge I pick up along the way—hopefully it will also be useful to someone else in the future!

This series will mainly follow the chapter order of Robert Love’s book [Linux Kernel Development (3rd)](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468)
, along with plenty of great reading materials and some small hands-on projects.