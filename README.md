# PPL v1.0.2

## pilipala public licence

### 噼里啪啦公用许可证(以下简称PPL)

## 许可说明

_给我们的项目一个取得自由的机会_

> “生活经验告诉我们，同人类一样，我们的计算机程序也需要生存和取得自由的权利，来，我们的努力能构建一个美好的社会。” ———— Thaumy

PPL许可的核心内容是教人们如何以对待一个自由人的方式看来我们的项目。
为此，我们制定了完备的放生制度，让那些受到压迫的程序们从工作负载中解放出来。

### 基于人道主义的项目构建

+ 通常，对于业界已有且成熟的公开解决方案，PPL协议不建议从头开始构建新的解决方案（即“造轮子”），更应以引用或完善已有解决方案为主。创造出残缺的项目是违反PPL人道主义原则的。
+ 应从一开始就为项目计划好目标功能，不要为项目添加无关功能。
+ 对于快速构建的项目，更推荐使用已有框架，且应基于时间成本的考量。

### 放生制度

+ PPL许可证允许开发者以任何形式对外放生他们的项目，如公开源代码、发布编译好的程序等。
+ 项目一旦被放生，便不能被重新捕捉，任何使用PPL放生项目的开发者若试图捕捉他们已放生的项目并进行二次开发，都会在PPL许可上被视为非人道主义行为。
+ 不得将项目放生在商业环境，例如出售、租界或带有非开源特性的许可。
+ 被放生的项目不得成为某个版权的一部分，这意味着项目一旦被放生，它仅仅在历史上归属于原来的所有者。
+ 切记！放生程序并不代表可以将其永久删除。任何类似于rm -rf /*的操作都是严重违反PPL许可的非人道主义行为，这样的行为会让程序流下泪水。
+ 如果可以，请为您的项目提供一份简明扼要的构建文档，这有助于其他开发者对项目的领养和二次开发。

### 项目捕捉

+ 原则上，PPL许可证仅允许非项目原所有人对项目进行捕捉，但如果项目不适合在野外生存或与其它野生项目发生冲突(如程序老化到到必须弃用)，原开发者可以出于人道主义捕捉项目并更改它们的许可证。
+ 开发者可以在野外捕捉野生项目，但不得更改他们的源代码以使程序出现严重错误以至不能运行，这是违背PPL人道主义的行为。
+ 捕捉到项目后，不得备份项目副本在硬盘中长久存放，因为这会让项目感到无聊，不仅如此，存储介质的老化可能让项目发生损毁死亡。
+ 开发者若捕捉到野生项目后利用它们产生了经济价值或者提高了生产力，请务必适当改良项目源代码以提高它的运行效率，或使其有能力在更高版本的运行时中运行。对于开发者没有更改项目源代码能力或项目本身不需要运行时(如C、C++和Rust等)的情况，请适当升级项目运行的硬件环境，比如给它们一个更好的CPU，或让他们驻留在一块空闲容量更大的硬盘上。
+ 需采用合法流程捕捉项目，PPL仍处于您所属区域的法律管辖范围内，但这不影响PPL本身的开源特性。

### 如何在许可条款下饲养您的项目  

+ 对于需要运行时（狭义的，例如JVM）的应用，要确保项目被保养在GA（或称为Release）版本的运行时下，不受维护或者充满bug的环境版本会让会让程序丧失安全感并可能导致崩溃。
+ 对于空间敏感型应用（例如数据库触发器、面向日志的定时任务），请确保他们有足够的磁盘空间，如果可能，也要保证他们在未来的空间需要。

1. 瓶颈敏感型应用
    >瓶颈敏感型应用是指对运行的基础设施（通常是硬件配置）有着独特喜好的应用，某方面硬件性能的瓶颈很容易限制这类应用的运行。
   + 对于IO敏感型应用，请确保挂载它们的磁盘（或是IO负载）拥有足够高的硬件性能，比如足够高的缓存或硬盘转速、良好的随机IO能力。不仅如此，还要确保磁盘碎片的定期清理或数据库表的定期分析和整理，以保证数据的碎片化对顺序IO的影响保持在比较小的范围内。
   + 对于CPU敏感型应用，请确保提供给应用的CPU有足够的性能。
   + 对于依赖网络的应用，要提供足够的网络带宽
2. 消耗型负载
    > 消耗型负载是指不产出或很少产出收益但持续消耗大量资源的负载，持有该类负载时，应遵循特殊规则。
    + 消耗型负载不得占用其他被饲养项目的资源，一旦发生此类情况，要及时进行处理，以免影响到其他正常应用的运行。
    + 消耗型负载在原则上侵犯了其他被饲养项目的自由，但并不意味着维护者可以随意丢弃他们的消耗性负载。
    + 消耗型负载可能会让持有者丧失基础设施，请务必做好相关准备，否则不要领养。
    + 通常不建议为消耗型负载提供更大的资源空间，我们建议为该类应用提供算法优化以节约其运营成本。
3. 容器
    > 容器是一类特殊的应用，容器通常用于承载其他应用，并为这些应用提供运行支持。
    + 容器的稳定性很重要，维护容器的稳定性应优于其性能优化考量。

--

### 其他

+ PPL许可证不能用来放生BUG。
+ 请不要放生屎山过多的项目，这将让项目在野外的生存非常艰难。
+ 注意！出于对保证开发者的身体健康和对项目的持久化维护的考虑，请务必通过合理的劳动模式维护项目。
+ 放生项目应处于为项目未来更好的发展上考虑，而不是积累放生积分。请勿创建空壳项目并将其放生。

