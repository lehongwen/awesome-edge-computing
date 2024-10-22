### 边缘计算（初创）公司的产品和解决方案 ###



相对于云计算而言，边缘计算是从云计算的“资源集中共享模式”走向各边缘节点的“分布式互助共享模式”。根据分布在“端、管、云”的计算点位置，可以大致分为以下6类，具体如图1所示。
![](https://github.com/lehongwen/edge-computing-engineering/blob/master/Edge-Computing-Companies/maps/5G%20MEC%E7%9A%84%E6%9C%AC%E8%B4%A8.jpg)

（1）云服务商为主的边缘计算，“云服务引流”   
比如腾讯、百度、阿里的边缘云节点，Google GKE On-Prem，微软Azure Stack以及华为公有云的边缘计算，是以云生态的入口引流为目的，在边缘云形态上实现一个小边缘云，遇到更复杂的内容，将在云上提供。

（2）站点设施边缘联盟/站点服务商，“站点 + 计算服务”   
 以Vapor为代表十几家公司联合建立了生态，类似中国铁塔公司提供众多中立站点的概念，通过机房、集装箱等多种机制，把边缘站点联成网。
 
（3）固定运营商为主的边缘计算，“固定联接 + 计算服务”    
 中国的边缘计算联盟（ECC）是华为固网很早发起的、与工业互联网广泛互动的固定网络边缘计算，以企业网的交换设备、固定接入边缘设备为主要场景。
 
（4）移动运营商为主的边缘计算（MEC），“移动联接 + 计算服务”     
 边缘计算在2014年被叫作“mobile edge computing”，最早的场景是在移动基站本地做 cache，后来演变为分组移动网关PGW本地分流、内容缓存和加速、对接固网IPTV组播等多种形态，得以商用（例如华为在全球多个地区商用）。2017年华为无线核心网等各方提议ETSI将MEC全称改为“multi-access edge computing”，同时在2018年结合5G网络架构，在3GPP国际标准SA2（网络架构组）明确MEC是部署在UPF位置，并对UPF有多种增强，伴随着5G，MEC也走向固移融合和多种接入。
 
（5）行业/企业/交通路政组建的网络或自组织网络形态的边缘计算，“行业自建联接 + 计算服务”      
可以展开来分解，一部分按技术协议栈等同于第四类移动运营商为主或者第三类固定运营商为主的网络（频谱可以改变为unlicensed），还有一部分例如LoRa或者 Wi-Fi自由组网，配合云服务商、站点服务商、物联网整网以及终端形态的实现，协议栈近似于第一类/第二类/第六类。
 
（6）终端/CPE形态、IoT GW形态、车载形态的边缘计算，“近端计算服务”     
先在本地及时做计算处理，随后才连接宏网络，和上一级节点或者周边节点做互助。

参考：
> 周艳;5G MEC的本质是“联接+计算”[A];2019全国边缘计算学术研讨会论文集[C];2019年



# 端

## 电信设备商
### 华为

行业引领者，边缘云和云化网关两类形态；围绕重点行业与场景，构建Huawei Inside全栈全场景伙伴生态。   
边缘云，将中心云的能力拉近到边缘，解决方案：智慧园区、平安城市、智能制造、MEC、CDN等场景。
产品包括：智能边缘平台（IEF:Intelligent EdgeFabric ）、IoT、CDN、Atlas、ROBO等；云化网关，网关设备基于云计算技术的演进，关键能力：多样连接、实时处理、云化管理、人工智能、边云协同，产品：EC-IOT、SD-WAN、Ocean Connect Edge、Atlas AI。开发者&开源：开发公有云、LF Arkarino（CNCF Kubeedge、Linaro EC PR）。   
[https://e.huawei.com/cn/products-and-solutions?pos=enterprise-network&source=corp_comm](https://e.huawei.com/cn/products-and-solutions?pos=enterprise-network&source=corp_comm)
### Ericsson
[https://www.ericsson.com/en/digital-services/trending/edge-computing](https://www.ericsson.com/en/digital-services/trending/edge-computing "edge-computing")
### 诺基亚

### 中兴
中兴通讯提出了“聚焦4C”的边缘计算发展战略，围绕Cloud(云化部署，统一运维)、Compute(专用硬件，异构加速)、Connection(多种制式，融合接入)、Capability(开放平台，共建生态)，打造了在边缘计算领域的四大服务能力。中兴通讯还提供全系列MEC服务器，匹配不同应用场景，实现性能与成本的最佳匹配。中兴通讯发布了E5410(单节点)和E5430(三节点)两款MEC服务器，服务器搭载英特尔最新至强Scalableprocessor，配合AI加速卡，使其在边缘侧具备很强的神经网络推理能力。

### Cisco
思科领导着网络市场，在联网物联网设备市场中也扮演着关键角色，它提供IoT网络硬件、用于管理边缘数据的Cisco Kinetic IoT平台、IoT威胁防御安全、IoT管理和自动化解决方案，以及咨询和技术服务，以帮助其他组织启动和运行其物联网计划。思科的物联网客户包括公用事业，制造商，运输公司，城市和政府机构，零售商和教育机构。
### 新华三
2017年9月，新华三发布了H3C AD-EC应用驱动边缘计算解决方案及相关产品，H3C AD-EC应用驱动边缘计算解决方案就是新华三在“边缘即云”概念下，针对边缘计算场景提出的，包含AD-EC控制器、LA系列融合网关、生态应用在内的一整套边缘计算解决方案。AD-EC控制器采用了开放的SDN控制平台，拥有南北向标准接口，具有一体化的ICT管理能力，实现高效运维。LA系列融合网关则具备IT&CT融合、开放平台、丰富物联接口、场景化定制等一系列特性。2019年发布新华三针对边缘计算发布了的HPE EL1000和EL4000两款服务器，凭借先进的设计理念和制造工艺，不仅实现了体积的微型化，还可以在恶劣工况条件下提供强大的性能、管理及无线连接能力。
## IT设备商

### ADLINK
**凌华科技（ADLINK)**：凌华科技专注于边缘技术，它提供物联网硬件和软件，人工智能（AI）软件和机器人解决方案。它服务于医疗、制造、网络、通信、军事、航空和公共部门的客户。
### Samsung

### Dell EMC
Dell EMC将其边缘计算硬件分为三个不同类别：
1）Mobile Edge产品组合包括用于移动或远程位置的云硬件，例如PowerEdge XR2 Rugged Server，PowerEdge R740 / R740XD和Micro Modulear Data Center。
2）Enterprise Edge产品组合包括VEP460 Open uCPE平台，
3）IoT Edge产品组合为制造商、零售商和数字城市提供Edge网关。该公司还通过OpenManage Mobile提供边缘计算管理和编排功能。
### HPE
惠普公司（HPE）通过其Aruba网络子公司提供有线和无线网络产品，包括支持边缘计算的网络安全解决方案。HPE还提供 Edgeline Converged Edge Systems，其中包括控制系统、电信、工业网络和IoT数据采集。此外，该公司还提供与物联网和边缘计算有关的服务。
### IBM
IBM收购了Red Hat之后推出了基于OpenShift技术的边缘计算平台，它还为服务器提供边缘计算，帮助组织管理其网络边缘的基础设施，以及将其AI技术应用于物联网的沃森物联网平台。IBM在企业资产管理、设施管理、系统工程等方面有具体的物联网解决方案。
### 浪潮
浪潮推出边缘计算服务器，NE5260M5和NF5250M5服务器就是专为5G时代的各类边缘计算应用所设计,高度为2U,宽19英寸,深度为430mm,仅有传统标准服务器深度的1/2稍多。这款产品并没有因为空间小而牺牲配置性能,而是配置了2颗第二代英特尔至强可扩展处理器,16个内存插槽,其中2个支持AEP内存,主板集成2个10G SFP网卡,6个PCIe-3.0接口。存储方面,可支持6块HDD/SSD,以及2块2.5寸M2接口的SSD。体积小和性能强是浪潮在设计边缘计算服务器时所追求的两个方向。
### 联想
围绕“联想商用IoT边缘计算解决方案生态全景图”，联想商用依托x86、ARM等开放硬件架构以及软件工具、平台，依托自身在商业计算领域的技术、产品实力，整合联想其他业务部门的优势资源，针对不同行业关键业务场景的数字化创新需求，提供了聚焦业务回报，看重商业价值的解决方案。推出专为边缘计算和AI量身定制的ThinkSystem边缘服务器，凭借在外形、性能、连接、安全、管理等方面的优势，助力客户高效应对智慧化转型过程中不断出现的复杂挑战。在应用层面，ThinkSystem SE350适用于包括VR/AR、智慧社区、智慧交通、智慧城市与智能制造等在内的多种应用场景。
## 安防监控类

### 海康
### 大华

## 芯片

### Intel
英特尔以芯片制造而闻名，作为其物联网平台的一部分，英特尔提供了一系列边缘计算产品，包括物联网网关、英特尔安全设备内置（SDO）服务，风河Helix设备云，风河Titanium边缘和具有英特尔处理器和存储功能的边缘计算组件。英特尔还拥有用于物联网部署的参考架构，开发工具包、工具和SDK，其他公司可以购买英特尔的产品来创建自己的物联网产品和服务。
### ARM
ARM+Linux 的组合，占据了几乎整个智能硬件市场，而Intel仍然拿不出像样的平台来抵抗。ARM平台目前有CortexA,CortexR.CortexM,Mechine Learning,SecurCore几个平台，其中以Cortex A系列最被市场接收。
目前，大量的智能手机（ios,android)，商业广告机，快递柜等，都是由ARM支持。由于边缘计算技术的兴起，特别是在设备侧的人脸识别，语音识别能力兴起，ARM的高阶芯片开始面向市场，可以有利地支持AI的发展。

### NVIDIA
主打产品：芯片处理器
在智能计算芯片领域，怎么能少得了英伟达。基于Jetson Nano处理器组装的轻型NVIDIA EGX平台可实现每秒5亿次并把功耗维持在几瓦特；搭载NVIDIA T4的EGX边缘服务器可以达到10万亿每秒的运算。
芯片的低功耗对人工智能运算很重要，目前传统CPU在这类运算中能耗巨大，EGX目前是少数能够实现低功耗的计算平台。Jetson Nano处理器在最近的一项针对机器学习的基准评测中战胜了Google的EdgeTPU和英特尔的边缘处理器，取得了机器学习计算性能上的领先地位。

### Qualcomm
### Socionext
### NXP
### 地平线
专注边缘人工智能芯片。2017年，地平线大规模流片并发布了边缘人工智能处理器——专注于自动驾驶的地平线“征程”系列处理器与专注于AIoT边缘计算的地平线“旭日”系列处理器。2018年，地平线托其独特的软硬结合人工智能处理器技术，相继发布了Matrix自动驾驶计算平台与和地平线XForce边缘AI计算平台。其中，地平线Matrix自动驾驶计算平台于2019年初获CES创新奖。

## CPE
CPE的英文全称为：Customer Premise Equipment
CPE客户终端设备常布放于，FTTX家客业务的客户端，用于提供家庭客户的有线宽带、IPTV、VOIP等业务的综合接入。
CPE上联PON传输网络，下连具体业务设备，完成接入网络与用户设备的连接。
## 工业互联

### Fujitsu
### GE
### 施耐德
## 自动驾驶

## 无人机

### 扩博智能
扩博智能聚焦计算机视觉和机器学习技术，专注于为行业企业用户提供端到端一体化智能服务。
### 大疆

# 管
主要是电信设备商，从移动运营商、固定运营商的电信网络发展，延展更多的App业务和生态，从移动网面向消费者（2C）的基本普遍网服务，扩展到面向家庭场景（2H）、行业场景（2B）的更广泛服务，和5G整体业务目标保持一致。
## 通信运营

### 中国移动
边缘IaaS平台BC-Edge、边缘PaaS平台Sigma、OTII边缘定制服务器等产品，以及和阿里、腾讯、百度等互联网及垂直行业等领先公司合作15个示范项目，包括边缘vCDN、云游戏、边缘AI、智慧工厂、智慧楼宇等重点应用领域。成立边缘计算开放实验室，目前已有79家合作伙伴。实验室已经和合作伙伴进行试验床建设共15项，盖了高清视频处理、vPLC、人工智能、 TSN 等新兴技术，涉及智慧楼宇、智慧建造、柔性制造、CDN、云游戏和车联网等多个场景。19年2月发布中国移动边缘计算“Pioneer 300”先锋行动。
### 中国电信
中国电信在MEC上进行了很多研究探索，打造边缘计算开放平台ECOP，构建边缘云网融合的网络服务平台及应用使能环境，推进边缘业务应用创新发展。中国电信定义了服务框架类、网络服务类、ICT服务类三大类API接口，而在产业推进方面，中国电信积极开展广泛的业务与技术，ECOP外部合作伙伴超过12家。
### 中国联通
MEC边缘云是中国联通5G全云化网络架构的关键要素，边缘云与通信云、公有云、私有云互通，具备云边协同能力，落地实践是实现MEC边缘云价值的最重要的推手。中国联通在边缘计算领域积极探索，全力构建 CUBE-Edge 2.0 边缘业务平台，加快5G商用步伐。2018年，联通已开展15个省市的MEC边缘云规模试点。中国联通积极推动MEC边缘云标准体系的完善，在ETSI、ITU-T、3GPP、CCSA主导10余项标准立项。和网宿成立合资公司云际智慧，入局CDN&边缘计算。
### AT&T
### SK Telecom
### 德国电信
### Korea Telecom
### CenturyLink
CenturyLink（一家面向企业的固定网络运营商）
# 云

## 行业/企业服务


### 海尔
海尔专门为物联网企业打造的一站式设备管理平台COSMOEdge平台， 提供多源的边缘设备接入能力与强大的边缘计算能力，支持多种工业协议解析，提供可视化流式管道，提供数字化建模与实体映射，提供设备即服务的应用模式，帮助用户快速构建物联网应用，实现数字化生产，助力于企业效益提升；
### 佰才邦
### 艾睿电子
利用其广泛的生态系统、产品和服务组合、专业知识和规模来协调部署边缘解决方案

### CloudHedge
其面向Linux的自动容器化和基于Windows的解决方案将在Red Hat OpenShift和Docker上运行
### Indra
提供能源设施解决方案Minsait ACS
### ClearBlade
ClearBlade是一家纯粹的物联网和边缘计算供应商。其主要产品包括ClearBlade企业物联网平台、ClearBlade Edge物联网软件和ClearBlade Secure IoT Cloud。它还为联网产品，智能轨道，智能监控，实时定位和资产跟踪提供边缘计算解决方案。它为铁路、矿业、石油和天然气、物流，医疗和能源行业的公司以及公共部门的组织提供服务。
### Hitachi Vantara
Hitachi Vantara提供存储、融合基础架构、IT运营管理、数据保护、分析和视频智能产品，以及其一系列IoT产品。这为在边缘收集和处理数据提供了完整的解决方案。其主要物联网产品是Lumada平台，包括Lumada Edge Intelligence、Lumada Maintenance Insights、Lumada Manufacturing Insights和Lumada Video Insights。它为能源、制造和运输行业的公司提供解决方案，以及维护和维修的解决方案。
### Oracle
甲骨文基于公司云服务架构为边缘提供了硬件，它还拥有一套基于SaaS的IoT应用程序，以及针对工业制造、建筑和工程、公用事业、零售、医疗和保险的特定行业解决方案。其物联网客户包括日立咨询，埃森哲，AskStory和LT Infotech。
### Saguna
Saguna是一家纯粹的边缘计算公司，致力于“将通信网络转变为边缘云计算平台”。其旗舰产品是一个多接入边缘计算（MED）解决方案，其中包括边缘虚拟化、开放式管理和自动化功能。该初创公司为移动运营商、企业和应用程序开发人员提供解决方案，但它主要专注于电信行业和网络服务提供商。它的客户包括HPE，Dell，BY，Akamai，5Tonic，Wind，Vodafone，Vimmi和KDDI。
### SAP
SAP将其边缘计算产品归入SAP Leonardo IoT Edge品牌。该端到端解决方案包括可在IoT网关及其Edge Platform上运行的SAP Edge Services，从而将公司的云计算能力扩展到了边缘。该公司为众多行业的企业提供服务。
### Edge Intelligence
边缘计算的使用方式：Edge Intelligence是用于移动边缘计算的分析平台。该公司的软件平台可以实时处理数据，从而使企业能够洞察路由器，网络服务器甚至威胁情报平台等设备在地理上分布的边缘数据。  
### Azion
边缘计算的使用方式：Azion 帮助企业在边缘构建可扩展且安全的无服务器应用程序。该公司的边缘产品可连接到任何云服务，并促进应用程序构建，从而减少了从内容下载到个性化安全构建等所有内容的延迟时间。
### Phizzle
边缘计算的使用方式：Phizzle为希望从营销数据中获取更多收益的公司构建了MEC解决方案。Phizzle利用边缘计算来帮助组织将其商业智能与机器学习相结合，以改善从SMS营销到社交数据可视化的一切。
### Rigado
边缘计算的使用方式：Rigado为智能，互联环境创建IoT数据解决方案。该公司的产品之一，Cascade-500 IoT网关，提供了到传感器，设备和云的边缘连接。通过广泛的连接选项（包括蜂窝LTE），Rigado可以以较低的延迟将智能建筑信息中继到云中。
### FogHorn
如何使用边缘计算：FogHorn 开发了用于工业物联网（IIoT）的边缘智能软件。从石油和天然气到智能建筑和制造业，各行各业都使用FogHorn的智能平台来收集实时设备信息，并将处理和存储成本降低100-1000 倍。
### Cloudera
Cloudera是世界领先的企业数据云公司之一，在企业和大型机构在寻求解决棘手的大数据问题时，往往会使用开源软件基础架构Hadoop的服务。 
因此我们也不会感到惊讶，Cloudera也是推动新边缘计算战略发展的先驱之一。该公司最近才宣布推出两款最先进的边缘数据管理解决方案，旨在为物联网架构师和开发人员提供强大的方法来控制他们的边缘数据。
Cloudera的新解决方案包括可以帮助处理流数据的Cloudera Edge Management和Cloudera Flow Management。Flow选项是一种无代码，高规模的数据提取解决方案。
### Acromove
帮助客户在任何环境下几分钟内便部署完成高机动性的地理弹性边缘数据中心
### Equinix

### AlefEdge
Alef 主要的产品包括：
边缘网关：移动的边缘计算平台，提供边缘连接、超低延迟和时序计算能力。
边缘云: 创建新一代API 和 微服务支持的 (i) 边缘增强（现有应用程序），可以从边缘更好或更快地完成交互，比如视频流； （ii）边缘原生应用，没有边缘就不可能存在，比如无人驾驶汽车。
边缘应用： 垂直领域专门的产品及服务。基于边缘网关和边缘云的组合，可以是智慧城市、工业4.0, AR/VR 等等 你能想得到的高速、低延迟 应用。具体的应用场景在：智能移动边缘连接/广告技术/边缘游戏

### LeapMind
LeapMind的商业模式比较的简单，是基于嵌入式硬件的深度学习开发板，提供给B端客户进行二次开发。
产品组合包括:
DeLTA-Lite：用于打造嵌入式深度学习模型的开发板；
DeLTA-Kit:基于DeLTA-Lite 的硬件套装，包括摄像头，连接线，电源等；
DelTA- Mark:用于深度学习建模的标记工具；

### Verizon
### Altran
### Charter
### Dianomic

### inwinSTACK
### Juniper
瞻博网络
### Netsia
### NTT Group
### OSIsoft
### Radisys

### Seagate
### Wipro
### ZEDEDAA
### Beechwoods
### Stratus
### Hazelcast
提供低延迟内存计算
### Humio
提供具有流观测能力的企业日志管理服务
### Portworx
提供 Kubernetes 存储服务，在边缘运行生产应用
### Sysdig
提供嵌入式容器安全服务
### Turbonomic
提供人工智能驱动的应用资源管理服务
### Eurotech
通过 IBM Cloud Pak for Data 和 IBM 边缘应用管理器，将经过训练的数字图像分析结果部署到边缘设备上
### Geniatech
提供传感器和可穿戴设备，可与 IBM Maximo 配合应用于工人安全使用环境
### Smartcone
该公司的设备提供智能工作区和高精度资产跟踪功能，可在边缘实时作出响应
### BT
BT云平台边界将延伸到城域之外，扩展到BT在英国运营的部分中心局点。目前， BT拥有近1200个本地端局，它们可以作为第一汇集点。据报道， BT计划在其移动子公司EE的5G商用元年，将平均时延从30ms降低到20ms。中期目标是低于10ms，以此使能一组新的5G应用，如动态机器人和无人机业务。借助其新架构， BT还可以通过多种访问技术提供服务。
### Telefónica
MEC是Telefónica总体网络演进战略的重要组成部分，是Telefónica向全融合、虚拟化和软件定义网络（称为开放访问网络（OPA）和Unica计
划 ）转型的组成部分 。 作为Unica计划的一部分， Telefónica正在完成其数据中心的虚拟化，当前重点工作为中心局点。 Telefónica围绕如何广泛部署边缘能力展开了一系列探讨，从长远来看，这可能反映市场的发展情况。Telefónica正在为客户搭建现网试点案例，其中云游戏于2019年第二季度推出，第一季度推出混合存储业务。利用其边缘能力， Telefónica近期商用了扩展现实（XR）内容。

### Telstra
Telstra与Ericsson、澳大利亚联邦银行合作，通过在5G网络上测试端到端银行解决方案，探索金融行业边缘计算应用和网络能力。通过类似试点，可以预测未来银行网点将呈现什么形态，以及基于5G的边缘计算如何帮助减少目前银行网点所需的网络基础设施。
### Rakuten
日本乐天（Rakuten）表示，作为虚拟化网络建设的一部分，将进行大规模边缘部署，计划提供4000种边缘业务。尽管在初始阶段，边缘计算资源将主要用于支撑公司核心移动业务的交付，但在2020年其5G网络商用之后，乐天将可以探索并开发第三方应用和业务。
### 星耀科技
星耀科技核心团队启动MEC场景研究和技术开发，2016年，成功申请“一种对移动终端的业务分流方法及设置”等6项MEC相关知识产权，2017年，启动MEC商业化应用，2018年，成功部署七大场景应用。星耀科技关注边缘云和边缘计算平台Paas赋能的能力。在安防和无人商超场景下的人脸识别业务，利用边缘节点，部署AI识别服务，本地对比人脸数据库，返回计算结果，再将必要的信息上传至中心数据库做存储和多地信息同步。星耀科技便通过应用，推动MEC的尽快落地。2018年1月25日，星耀科技实现了业界首个“MEC智能安防”商用;2018年2月15日，全国首个MEC智能农业项目落地;2018年5月12日，为第二届全球网络发展峰会提供全程VR直播服务;2018年5月15日，为浙江联通“联通5G来了”活动提供全程VR直播。

### CertusNet
赛特斯发布三款边缘网络产品包括边缘网关(FlexEGW)、边缘云(FlexEstack)、边缘云管理平台（FlexECO)。其中，柔性边缘云解决方案以微服务构架构与柔性网络技术结合，平台内置数十种通用微服务在根据不同的业务场景，编排器制定相关的策略与业务流程，实现软件定义硬件与业务按需处理的能力。赛特斯以柔性网络技术为边缘计算注入新的动力。在家宽边缘，赛特斯通过边缘网关(FlexEGW)为网络插上翅膀，注入低延迟、高带宽与海量接入能力，实现各类大视频、大数据、大智能的业务落入寻常百姓家。

### TERMINUS
特斯联发布自主研发的边缘侧新产品——AI边缘融合服务器致慧X9系列。致慧X9是一款兼具AI计算能力与存储能力的边缘融合服务器，主要用于需要人脸识别二次交叉比对与数据后处理功能，同时又需要本地数据存储的使用场景。这是特斯联在“云-雾-端”分层业务构架中的“雾（边缘）”侧的又一重量级产品。致慧X9将与特斯联已量产投入使用的AI算力增强模组致慧X1、AI边缘计算网关致慧X3、边缘存储服务器致慧S9等产品形成合力，使边缘侧在数据处理分析中发挥更大价值。特斯联的边缘计算产品具备多融合组网、边缘存储一体化、弹性算力自由配置和边缘节电处理的四大优势。

### 江行智能
专注边缘计算领域，核心产品EdgeBox™️已广泛应用于工业、智慧城市、能源等领域，展现出强劲的市场竞争力。在输电线路维护、变电站巡检和配电台区智能化场景中，EdgeBox™️借助其多传感器融合、超低功耗的识别技术及人工智能深度学习等能力，在边缘侧进行实时计算，及时回传预警信息，有效降低电力行业的通信开销和计算延迟。在制造、水务、安防领域，以EdgeBox™ 为核心的边缘计算方案也在各个场景中提供降本、增效和安全的服务。

### 中科边缘智慧
边缘智能信息服务基础平台（III@E）系列产品提供者，通过边缘计算与智能计算的融合创新、自主可控及产业化，为国防军工和民用民生应用领域提供系统级自主可控解决方案与高标准高效率高质量服务。中科边缘智慧致力于信息系统平台关键技术及核心装备开发与研制，通过在数据服务（DaaS）和人工智能服务（AIaaS）等新一代信息技术领域的持续创新，以自主可控的技术、产品和应用为基础，以边缘计算、智能计算、云雾计算和大数据技术的创新突破和综合应用为主要技术特色。

### 研华科技

### Tata
[https://www.tata.com/](https://www.tata.com/)

### Nutanix
[https://www.nutanix.com/en](https://www.nutanix.com/en)

### 日海智能
[http://www.sunseagroup.com/](http://www.sunseagroup.com/)

### Aricent

## 网络安全服务商
--------------

## 云服务商

云服务商为主的边缘计算“云服务引流”，比如腾讯、百度、阿里的边缘云节点，Google GKE On-Prem，微软 Azure Stack 以及华为公
有云的边缘计算，是以云生态的入口引流为目的，在边缘云形态上实现一个小边缘云，遇到更复杂的内容，将在云上提供。

### 腾讯
发布腾讯智能边缘计算网络平台TSEC（Tencent SmartEdge Connector），TSEC致力于构建使能5G/IoT网络与业务协同的网络层PaaS服务，具备移动流量分流、移动网络加速、边缘流量转发、移动网络隧道、物联接入控制等核心功能。开源领域，腾讯与合作伙伴在Linux基金会共同发起成立LinuxFoundation Edge项目，并担任董事会董事，下设EdgeXFoundry、Akraino EdgeStack、Home Edge、EVE等多个项目。腾讯在Akraino Edge Stack项目中提交面向云游戏、高清视频和直播业务的5G MEC/切片蓝图，推进腾讯TSEC在5G边缘计算和切片技术领域的开源与开放。
### 百度
2018年2月，百度云天工发布“智能边缘”，并开启邀请制测试，这是国内云计算厂商推出的首款边缘计算产品。2018年5月底，，百度云发布了国内首个智能边缘产品百度智能边缘（BaiduIntelliEdge-BIE）。智能边缘BIE是百度云发布的国内首个智能边缘产品，符合“端云一体化”趋势。部署了智能边缘BIE的设备和边缘计算节点，既可以与百度云天工进行无缝数据交换，对敏感数据进行过滤计算，也可以在无网或者网络不稳定的情况下，缓存数据、独立计算，实现实时的反馈控制。2018年12月智能边缘计算平台OpenEdge全面开源。OpenEdge是中国首个全面开源的边缘计算平台。借助开源OpenEdge，开发人员可以更灵活地开发自己的边缘解决方案和应用。
### 阿里
2018年3月发布IOT边缘计算产品Link Edge，将阿里云在云计算、大数据、人工智能的优势拓宽到更靠近端的边缘计算上，打造云、边、端一体化的协同计算体系。推出ENS，边缘节点服务（ENS）被定义为边缘融合的计算平台，融合是指在边缘的基础设施如MEC、IDC等资源上做融合。也有在计算形态、提供形式以及运维方面的融合。ENS全部边缘节点总数超过300个，平均每个运营商在每个省份的覆盖是3个，可以在省内建立多可用边缘布局。
### Google
谷歌提供一系列用于边缘计算的联网家居产品，并且还提供用于管理边缘数据的云计算服务，最著名的是其Cloud IoT Core服务。此外，它以Edge TPU的形式提供硬件，用于在网络边缘运行AI和分析。边缘分析是Google特别关注的重点，它吹捧其他AI云服务是对边缘计算产品的良好补充。它服务于各种不同的行业。
### 微软
与其他领先的云计算提供商一样，微软的Azure部门也推出了许多支持边缘计算的产品和服务，包括物联网服务，例如Azure IoT中心（IoT应用程序平台），Azure IoT Edge（部署在边缘设备上的AI服务），Azure IoT Hub（将边缘设备连接到Azure云的通信服务），Azure Sphere（物联网安全） ）和Azure Stack Edge（用于将要转移到Azure的AI工作负载的本地处理）等。微软还提供Windows IoT平台，其中包括开发工具和轻量级版本的Windows，用于在边缘设备上运行。微软的物联网客户包括Ecolab，Texa和Avacon。
### AWS
AWS以其云计算服务而闻名，但它也为工业、商业和联网家庭物联网市场提供了一系列服务。这些服务包括Amazon FreeRTOS微控制器操作系统、AWS IoT Greengrass（它将Lambda等AWS服务引入边缘设备)、AWS物联网核心、AWS物联网设备防御、AWS物联网设备管理、AWS物联网分析等。AWS还提供诸如车联网解决方案、物联网设备模拟器、AWS物联网摄像头连接器等解决方案。当然，它还销售边缘设备，包括其受欢迎的Echo和Alexa智能家居设备。
### vmware
### 九州云
开源技术服务提供商，凭借自身的技术优势深度参与CORD、StarlingX、Akraino、 OpenStack Edge Group等边缘计算国际开源社区。九州云凭借自身的技术优势深度参与CORD、Starlingx、Akraino,、OpenStack Edge Group等边缘计算国际开源社区，并在边缘计算领域广泛拓展合作伙伴和国际客户。在MEC领域，九州云携手运营商打造出符合ETSIMEC标准规范的、基于开放架构的边缘平台解决方案。九州云遵循ETSI规范、基于TOSCA电信标准、容器YAML编排规范和StarlingX、Tacker等开放技术，打造ETSI规范中定义的MEC三大子模块（MEAO、MEPM、ME-IaaS），构成了运营商边缘整体解决方案。
### 金山云
金山云推出的容器云平台——KENC，可支持在边缘运行定义的容器镜像，将云端转码、游戏渲染等放在边缘来完成，真正实现热门场景下延时减低50%以上，显著减低中央系统负载压力。金山云布局智慧人居IoT，丰富边缘计算落地场景。金山云打造了AI-House企业管理平台，支持数百种风格统一、价廉物美的智能硬件设备一键批量连接管理。除了在边和端上布局边缘计算外，在客户端上，金山云联合小米发布了“1KM边缘计算”解决方案，以“云+亿级终端”边缘计算模式，弱网互联，实现全网速度提升，并解决了网民上网弱网丢包、劫持两大痛点。
## 内容服务

### Akamai
Akamai作为全球CDN领头羊早在2003年就与IBM合作边缘计算，今年6月Akamai与IBM在其WebSphere上提供基于边缘Edge的服务。
### Qwilt
Qwilt - 内容交付共享,开放式缓存解决方案，以优化内容交付，提高体验质量并启用新应用程序。
Qwilt多年来一直致力于将视频更贴近用户，这是一种相对普遍的做法，是边缘计算趋势的先驱。重要的是，Verizon在2017年与Qwilt达成协议，将供应商的“开放式缓存”部署到其网络中以进行视频传输。
此举使Verizon能够将视频内容存储在更接近最终用户的物理位置，从而消除了通过运营商网络传输的流量。Verizon随后报告称其网络流量减少了20％。
现在，Qwilt正在开发一种专门用于边缘计算的新型独特音调。该公司表示，其内容交付共享（CDS）模式通过激励ISP部署和运营核心交付基础架构，并利用边缘计算作为内容交付和其他边缘云功能的战略平台，从根本上消除了价值链中的商业CDN。

### Edgeworx
Edgeworx - Edgexworx的ioFog平台
Edgeworx去年年底出现了隐形模式，其开源，区块链启发的ioFog平台。
通过使用数字分类帐，Edgeworx系统可以通过不断验证系统中所有节点的一组安全规则来创建安全的分布式网络。当找到恶意节点时，它可以被自动隔离并可能擦除所有软件和数据。
该公司表示，将其添加到可能潜入大型开发者社区的开源战略中，难怪Edgeworx为何会在电信，石油和天然气以及政府/安全领域获得牵引力。

Edgeworx是一家技术型公司，帮助开发者打造云边一体化的连续体。创立于2017年，目前已经获得Samsung Next, SEQUOIA, CLOUDSCALE的投资。
该公司的产品基于容器的架构允许您利用任何语言，框架和SDK，可以在任何硬件上运行任何软件。

### MobilEdgeX
MobiledgeX - MobiledgeX R 1.0
MobiledgeX可能是5G和边缘计算最清晰的交叉点。该公司是Deutsche Telekom在硅谷的全资子公司，正在努力推动该欧洲巨头的边缘计算战略。
MobiledgeX已经宣布其Edge-Cloud R1.0软件现已普及，并已部署在德国的Telekom Deutschland网络中，使开发人员有机会试用他们的应用程序 - 特别是增强现实，混合现实和同步本地化和映射 -在Deutsche Telekom的国内网络边缘。
此外，Deutsche Telekom，MobiledgeX，AR游戏专家Niantic和三星最近展示了Niantic的“Codename：Neon”游戏，该游戏通过部署边缘创业公司的系统实现的低延迟连接成为可能，德国电信称。
MobiledgeX称，MobiledgeX计划在德国启用六个位置，使用DT和MobiledgeX边缘计算软件，这一数字今年将增加一倍。

### 网宿科技
从技术层面看，网宿科技持续深化边缘计算布局，从远边缘、近边缘和最边缘3个层面推进边缘计算，在远边缘，主要基于现有CDN节点，构建边缘计算资源池；在近边缘，引入运营商合作资源，将计算节点下沉至城域网或者基站；在最边缘，基于客户业务现场，提供计算资源和应用服务支撑。从产品层面看，网宿科技推出了边缘计算平台，并结合容器等虚拟化技术，不断升级平台服务，面向家庭娱乐、云VR/AR、车联网、智能制造等提供边缘计算服务。2月份和中国联通合作成立云际智慧，7月份与铁塔智联达成合作近195万座铁塔将加速边缘计算节点布局。
### CloudFlare
CloudFlare公司在2017年就推出了CloudFlare Workers，以微服务的形式开放边缘计算服务，支持用户在边缘端编程，这标志着它已经初步搭建好了边缘计算的平台。
### Nuu
bit宣布可以与微软的Azure宇宙数据库进行整合，同时微软的Azure系统也可以把Nuu：bit的数据整合在平台上，这也是一个极大的突破。

### Limelight
Limelight在今年上半年在其CDN网络上推出了增强版的EdgePrism OS软件，允许用户在边缘端进行本地内容输入和交付。

## IT站点服务

### Edge Micro
主打产品：低延迟的边缘主机托管
数据密集型的边缘计算还需要一定规模的数据中心作为支撑，这样的数据中心需要满足边缘计算的低延迟的需求，微型边缘数据中心应运而生，特别在5G时代，随着边缘计算业务的发展，对于微型数据中心的需求将会大大增加。
Edge Micro就是提供这种微型数据中心的一家初创公司，这样的初创公司还有很多，这些公司主要在提供低延迟、低功耗、高可靠性、环境适应性、容灾备份等方面进行竞争。
### Vapor IO
Vapor IO - Kinetic Edge Alliance
边缘计算的使用方式：Vapor IO 使用托管功能将类似云的服务带到无线网络的边缘。该公司的数据中心设施位于手机塔的底部，从而可以将IT设备放置在尽可能靠近用户的位置（并尽可能靠近蜂窝网络的边缘）。 

Vapor IO推出了所谓的“Kinetic Edge Alliance（KEA）”，其中包括联邦无线，Linode，MobiledgeX，Packet和StackPath以及技术合作伙伴Alef Mobitech，Detecon International，Hitachi Vantara，New Continuum数据中心等厂商， Pluribus Networks和希捷科技。该联盟基本上将边缘计算所需的硬件和技术供应商聚集在一起，无论是用于计算，存储还是在蜂窝网络边缘的接入和互连。

Vapor提供业界首个基础架构边缘计算解决方案。Kinetic Edge以前所未有的性能水平实现了新的和创新的边缘驱动应用，并通过其创新的边缘托管功能降低了CDN，云和网络运营商的CAPEX和OPEX要求。

Vapor的产品包括：Edge Colocation(边缘主机托管）,Edge Interconnection（边缘互联）,Edge SDN（边缘软件定义网络）。

Edge Colocation: Vapor IO提供了一种新的托管方式，由Kinetic Edge提供支持。这是一种比较“奇怪”的边缘数据中心，每个Kinetic Edge城市都有多个微型数据中心，这些数据中心以环形排列，间隔为10-20公里。然后将这些Kinetic Edge节点与高速光纤网格连接在一起，以实现负载平衡，弹性和工作负载迁移。简单来说，托管的机房被打散分布在一个环上，为了达到尽量靠近消费者的目的。

Edge Interconnection：Vapor IO的边缘互联服务和边缘会议室将服务搭载在通往运营商，云提供商，区域数据中心和其他重要场所的高速通道上。从主要的网络运营商和云服务提供商到网络规模的应用程序或私有基础设施，都可以与Kinetic Edge保持联系。通过在Kinetic Edge上互连的服务，可以实现性能和成本的提升，是普通的网络无法比拟的。Kinetic Edge是无线网络中的一跳，采用直接光纤进行回程，是下一代互联网的平台。

Edge SDN:借助Kinetic Edge的软件定义网络（SDN），可以通过自己的专用网络连接所有Kinetic Edge位置。使用API或Vapor Edge Portal创建实时虚拟专用网络，连接城市范围内的多个数据中心。根据需要进行管理和部署，具有安全性和隔离性。

Vapor IO革命性的Kinetic Edge平台采用专有的SDN技术，允许配置连接区域中关键位置的专用网络。对于开发人员和运营商，以呈现地理位置分散的数据中心集合，就好像它们位于具有多个可用区域的单个设施中一样。

### EdgeConneX
边缘计算的使用方式：EdgeConneX通过专门定位的数据中心提供边缘基础架构解决方案，帮助移动网络使服务，数据，内容和应用程序更靠近边缘，以提高流传输速度和速度。此外，EdgeConneX MEC基础架构还用于为虚拟现实平台提供动力并测试5G网络。    
行业影响：自2013年以来，EdgeConneX已在北美，欧洲和南美建立了40多个边缘计算数据中心。

### SWIM
什么是SWIM，像分布式操作系统,全面解决了构建大规模分布式实时应用程序的问题。
流媒体网络，为了透明地互连分布式应用程序，Swim将HTTP升级为连续一致的多路复用流协议，称为WARP。
通用运行时 ，凭借其小型，独立的运行时，Swim可以跨越适度的边缘设备，大型服务器集群以及介于两者之间的所有内容无缝地分发应用程序。鲜活用户体验，人类是实时的存在。我们将意识流当做生命体验。Swim的流式UI框架使应用程序以用户的生活方式工作。

首先，SWIM是一套分布式操作系统，解决的是构建大规模分布式应用程序问题。不同于一般的Windows,Linux操作系统，分布式操作系统是管理计算机集群，让大量的计算设备协同工作，产生较大的算力，提供强大的计算服务， 

首先进入脑海的，一定是云计算的分布式操作系统，比如阿里的飞天操作系统。显然SWIM 不是走这样的道路，它瞄准的是海量边缘设备，边缘数据中心，通过接入SWIM 分布式操作系统，管理广大的边缘设备。

其次，SWIM是实时交互的流媒体网络，简单一点说，它让边缘设备可以通过升级的HTTP协议快速双向交互。当我们用浏览器打开视频网站的时候，你可能发现加载的速率并不怎么高，但是点开视频，播放1080P 高清视频的时候，反倒觉得挺流畅。本质上，网速决定了交互的流畅性，但技术上的革新，对于加载速度的帮助也是巨大的。

SWIM的这个WARP技术，就类似于流媒体视频播放的技术，在两者之间架设快速的交互通道。
再次，SWIM可以跨平台分发应用程序。这个技术类似于Qwilt的解决方案（见上方），可以将内容和应用，在不同的边缘设备上进行发布，管理边缘设备就类似于管理云平台。

SWIM 的应用场景包括：
智慧城市 -- 将所有的信号灯和流量监控系统，组合成分布式网络进行运算，有效缓解疏导交通压力。目前， SWIM 为硅谷的Palo Alto市提供实时流媒体交通管理系统，该系统每秒可分析交通信号灯，车辆和行人的30,000个数据点。
运输监控 -- 监控城市内的所有物流车，包括轨迹，车辆状况，人员状况等信息，为车队管理提供有效保障。
 
### Edgegap
蒙特利尔初创公司Edgegap宣布完成100万美元的种子轮融资，以开发创新的游戏基础设施。

该公司成立于2018年，曾表示正在建设“下一代”游戏基础设施。

Edgegap的解决方案使视频游戏工作室能够改善玩家体验，同时减少延迟，而以思科和SAP校友为首的团队正在提供一种利用边缘计算的解决方案。

[https://www.w3.org/wiki/Networks/Edge_computing](https://www.w3.org/wiki/Networks/Edge_computing)


