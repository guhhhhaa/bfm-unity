# 信息科学部

四种文法：

1. 无限制文法（Unrestricted Grammar）：也称为类型0文法，没有任何规则限制，可以生成任何形式的字符串，包括无限长度的字符串。
2. 上下文有关文法（Context-Sensitive Grammar）：也称为类型1文法，其中规则的左侧和右侧可以包含有限个非终结符，并且在规则应用时，左侧的非终结符必须被替换为右侧的符号串。
3. 上下文无关文法（Context-Free Grammar）：也称为类型2文法，其中规则的左侧只包含一个非终结符，右侧可以是任何符号串。
4. 正则文法（Regular Grammar）：也称为类型3文法，其中规则的左侧只包含一个非终结符，右侧必须是一个终结符或者一个终结符后跟一个非终结符。

四种形式语言：

1. 无限制语言（Unrestricted Language）：也称为递归可枚举语言，可以通过图灵机来生成和识别。
2. 上下文有关语言（Context-Sensitive Language）：只能由上下文有关文法生成的语言，可以通过线性有界非确定性图灵机来识别。
3. 上下文无关语言（Context-Free Language）：只能由上下文无关文法生成的语言，可以通过非确定性下推自动机和确定性下推自动机来识别。
4. 正则语言（Regular Language）：只能由正则文法生成的语言，可以通过有限状态自动机来识别。

四种自动机：

1. 有限状态自动机（Finite State Automaton，FSA）：也称为有限状态转换器，它可以处理正则语言，并且只能识别有限状态的语言。
2. 下推自动机（Pushdown Automaton，PDA）：它可以处理上下文无关语言，具有一个有限状态控制器和一个栈，用于存储和弹出符号串。
3. 线性有界非确定性图灵机（Linear Bounded Non-deterministic Turing Machine，LBNtM）：它可以处理上下文有关语言，是一个图灵机的变种，但是限制了它的内部存储器空间和输入输出的空间相同。
4. 图灵机（Turing Machine，TM）：它可以处理无限制语言，是一个抽象的计算模型，包括一个无限长的纸带和一个读写头，可以读取纸带上的符号并进行状态转移。

计算机的体系架构类型主要包括以下几种：

1.冯·诺伊曼体系结构（Von Neumann Architecture）：由美国数学家冯·诺伊曼于20世纪40年代提出，是目前计算机体系结构的主流。该架构将计算机分为五个部件：运算器、控制器、存储器、输入设备和输出设备。

2.哈佛体系结构（Harvard Architecture）：该架构在存储器方面与冯·诺伊曼体系结构有所不同，分为指令存储器和数据存储器。指令和数据分别存储在不同的存储器中，因此在执行指令时可以同时从指令存储器和数据存储器中获取数据，提高了计算机的运行速度。

3.栈式体系结构（Stack Architecture）：该架构将存储器分为栈区和堆区。栈区用于存储程序执行过程中的数据和指令，堆区用于存储程序执行中动态分配的内存。栈式体系结构在编程语言实现中广泛应用，如Java虚拟机。

4.并行体系结构（Parallel Architecture）：该架构将计算机分为多个处理器，可以同时执行多个任务，提高了计算机的处理能力。并行体系结构应用于高性能计算、大数据处理等领域。