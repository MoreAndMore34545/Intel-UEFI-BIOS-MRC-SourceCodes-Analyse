# Intel-UEFI-BIOS-MRC-SourceCodes-Analyse
看完老狼的《UEFI 与 EDKII 源代码分析》，难 免让人觉得很可惜， MRC 的全流程函数表 MrcCallTable，全书没有提及，然而它是一个与内存 初始化密切相关的结构，主要用于支持 MRC （Memory Reference Code）的调用过程。 这个里面包 含各种各样的 MRC 的核心任务函数， 自然包含 Memory Training 相关的系列函数， 至此， 我想是时 候补足这方面的遗憾了！
