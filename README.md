## 简介

- 精简版思源字体，含思源宋体
- 精简了 ttf 和 otf 两个版本
- 包含基础常用的中文、英文字符和符号
- 可用于 web 端、pdf 等
    

## 目录
* min-output: 压缩精简后的字体文件，可以直接用
* source-file: 字体的原始文件，可以自行重新压缩使用，包含 `ttf` 和 `otf` 两个版本

## 使用的提取工具 `fonttools-pyftsubset` 
* `fonttools-pyftsubset` 支持 `ttf` 和 `otf` 的转换
* `Python pip` 安装即可 源代码：[Github](https://github.com/fonttools/fonttools)
* 参考 - [地址](https://tamshen.com/archives/20210913.html)
```shell
# 使用环境：Python ( 工具4.x版本需要 Python 3.6+)
# 实际使用过程注意 python3 pip3 等前缀

pip install fonttools
pyftsubset 1.otf --text-file=1.txt --output-file=2.otf

# 1.otf 要被裁剪精简的字体文件
# --text-file=1.txt裁剪的字体中保留1.txt这个文档中的所有字符
# --output-file= 将裁剪后的字体保存为2.otf
```

## 包含的字体数据如下：

```text
啊阿埃挨哎唉哀皑癌蔼矮艾碍爱隘鞍氨安俺按暗岸胺案肮昂盎凹敖熬翱袄傲奥懊澳芭捌扒叭吧笆八疤巴拔跋靶把耙坝霸罢爸白柏百摆佰败拜稗斑班搬扳般颁板版扮拌伴瓣半办绊邦帮梆榜膀绑棒磅蚌镑傍谤苞胞包褒剥薄雹保堡饱宝抱报暴豹鲍爆杯碑悲卑北辈背贝钡倍狈备惫焙被奔苯本笨崩绷甭泵蹦迸逼鼻比鄙笔彼碧蓖蔽毕毙毖币庇痹闭敝弊必辟壁臂避陛鞭边编贬扁便变卞辨辩辫遍标彪膘表鳖憋别瘪彬斌濒滨宾摈兵冰柄丙秉饼炳病并玻菠播拨钵波博勃搏铂箔伯帛舶脖膊渤泊驳捕卜哺补埠不布步簿部怖擦猜裁材才财睬踩采彩菜蔡餐参蚕残惭惨灿苍舱仓沧藏操糙槽曹草厕策侧册测层蹭插叉茬茶查碴搽察岔差诧拆柴豺搀掺蝉馋谗缠铲产阐颤昌猖场尝常长偿肠厂敞畅唱倡超抄钞朝嘲潮巢吵炒车扯撤掣彻澈郴臣辰尘晨忱沉陈趁衬撑称城橙成呈乘程惩澄诚承逞骋秤吃痴持匙池迟弛驰耻齿侈尺赤翅斥炽充冲虫崇宠抽酬畴踌稠愁筹仇绸瞅丑臭初出橱厨躇锄雏滁除楚础储矗搐触处揣川穿椽传船喘串疮窗幢床闯创吹炊捶锤垂春椿醇唇淳纯蠢戳绰疵茨磁雌辞慈瓷词此刺赐次聪葱囱匆从丛凑粗醋簇促蹿篡窜摧崔催脆瘁粹淬翠村存寸磋撮搓措挫错搭达答瘩打大呆歹傣戴带殆代贷袋待逮怠耽担丹单郸掸胆旦氮但惮淡诞弹蛋当挡党荡档刀捣蹈倒岛祷导到稻悼道盗德得的蹬灯登等瞪凳邓堤低滴迪敌笛狄涤翟嫡抵底地蒂第帝弟递缔颠掂滇碘点典靛垫电佃甸店惦奠淀殿碉叼雕凋刁掉吊钓调跌爹碟蝶迭谍叠丁盯叮钉顶鼎锭定订丢东冬董懂动栋侗恫冻洞兜抖斗陡豆逗痘都督毒犊独读堵睹赌杜镀肚度渡妒端短锻段断缎堆兑队对墩吨蹲敦顿囤钝盾遁掇哆多夺垛躲朵跺舵剁惰堕蛾峨鹅俄额讹娥恶厄扼遏鄂饿恩而儿耳尔饵洱二贰发罚筏伐乏阀法珐藩帆番翻樊矾钒繁凡烦反返范贩犯饭泛坊芳方肪房防妨仿访纺放菲非啡飞肥匪诽吠肺废沸费芬酚吩氛分纷坟焚汾粉奋份忿愤粪丰封枫蜂峰锋风疯烽逢冯缝讽奉凤佛否夫敷肤孵扶拂辐幅氟符伏俘服浮涪福袱弗甫抚辅俯釜斧脯腑府腐赴副覆赋复傅付阜父腹负富讣附妇缚咐噶嘎该改概钙盖溉干甘杆柑竿肝赶感秆敢赣冈刚钢缸肛纲岗港杠篙皋高膏羔糕搞镐稿告哥歌搁戈鸽胳疙割革葛格蛤阁隔铬个各给根跟耕更庚羹埂耿梗工攻功恭龚供躬公宫弓巩汞拱贡共钩勾沟苟狗垢构购够辜菇咕箍估沽孤姑鼓古蛊骨谷股故顾固雇刮瓜剐寡挂褂乖拐怪棺关官冠观管馆罐惯灌贯光广逛瑰规圭硅归龟闺轨鬼诡癸桂柜跪贵刽辊滚棍锅郭国果裹过哈骸孩海氦亥害骇酣憨邯韩含涵寒函喊罕翰撼捍旱憾悍焊汗汉夯杭航壕嚎豪毫郝好耗号浩呵喝荷菏核禾和何合盒貉阂河涸赫褐鹤贺嘿黑痕很狠恨哼亨横衡恒轰哄烘虹鸿洪宏弘红喉侯猴吼厚候后呼乎忽瑚壶葫胡蝴狐糊湖弧虎唬护互沪户花哗华猾滑画划化话槐徊怀淮坏欢环桓还缓换患唤痪豢焕涣宦幻荒慌黄磺蝗簧皇凰惶煌晃幌恍谎灰挥辉徽恢蛔回毁悔慧卉惠晦贿秽会烩汇讳诲绘荤昏婚魂浑混豁活伙火获或惑霍货祸击圾基机畸稽积箕肌饥迹激讥鸡姬绩缉吉极棘辑籍集及急疾汲即嫉级挤几脊己蓟技冀季伎祭剂悸济寄寂计记既忌际妓继纪嘉枷夹佳家加荚颊贾甲钾假稼价架驾嫁歼监坚尖笺间煎兼肩艰奸缄茧检柬碱碱拣捡简俭剪减荐槛鉴践贱见键箭件健舰剑饯渐溅涧建僵姜将浆江疆蒋桨奖讲匠酱降蕉椒礁焦胶交郊浇骄娇嚼搅铰矫侥脚狡角饺缴绞剿教酵轿较叫窖揭接皆秸街阶截劫节桔杰捷睫竭洁结解姐戒藉芥界借介疥诫届巾筋斤金今津襟紧锦仅谨进靳晋禁近烬浸尽劲荆兢茎睛晶鲸京惊精粳经井警景颈静境敬镜径痉靖竟竞净炯窘揪究纠玖韭久灸九酒厩救旧臼舅咎就疚鞠拘狙疽居驹菊局咀矩举沮聚拒据巨具距踞锯俱句惧炬剧捐鹃娟倦眷卷绢撅攫抉掘倔爵觉决诀绝均菌钧军君峻俊竣浚郡骏喀咖卡咯开揩楷凯慨刊堪勘坎砍看康慷糠扛抗亢炕考拷烤靠坷苛柯棵磕颗科壳咳可渴克刻客课肯啃垦恳坑吭空恐孔控抠口扣寇枯哭窟苦酷库裤夸垮挎跨胯块筷侩快宽款匡筐狂框矿眶旷况亏盔岿窥葵奎魁傀馈愧溃坤昆捆困括扩廓阔垃拉喇蜡腊辣啦莱来赖蓝婪栏拦篮阑兰澜谰揽览懒缆烂滥琅榔狼廊郎朗浪捞劳牢老佬姥酪烙涝勒乐雷镭蕾磊累儡垒擂肋类泪棱楞冷厘梨犁黎篱狸离漓理李里鲤礼莉荔吏栗丽厉励砾历利僳例俐痢立粒沥隶力璃哩俩联莲连镰廉怜涟帘敛脸链恋炼练粮凉梁粱良两辆量晾亮谅撩聊僚疗燎寥辽潦了撂镣廖料列裂烈劣猎琳林磷霖临邻鳞淋凛赁吝拎玲菱零龄铃伶羚凌灵陵岭领另令溜琉榴硫馏留刘瘤流柳六龙聋咙笼窿隆垄拢陇楼娄搂篓漏陋芦卢颅庐炉掳卤虏鲁麓碌露路赂鹿潞禄录陆戮驴吕铝侣旅履屡缕虑氯律率滤绿峦挛孪滦卵乱掠略抡轮伦仑沦纶论萝螺罗逻锣箩骡裸落洛骆络妈麻玛码蚂马骂嘛吗埋买麦卖迈脉瞒馒蛮满蔓曼慢漫谩芒茫盲氓忙莽猫茅锚毛矛铆卯茂冒帽貌贸么玫枚梅酶霉煤没眉媒镁每美昧寐妹媚门闷们萌蒙檬盟锰猛梦孟眯醚靡糜迷谜弥米秘觅泌蜜密幂棉眠绵冕免勉娩缅面苗描瞄藐秒渺庙妙蔑灭民抿皿敏悯闽明螟鸣铭名命谬摸摹蘑模膜磨摩魔抹末莫墨默沫漠寞陌谋牟某拇牡亩姆母墓暮幕募慕木目睦牧穆拿哪呐钠那娜纳氖乃奶耐奈南男难囊挠脑恼闹淖呢馁内嫩能妮霓倪泥尼拟你匿腻逆溺蔫拈年碾撵捻念娘酿鸟尿捏聂孽啮镊镍涅您柠狞凝宁拧泞牛扭钮纽脓浓农弄奴努怒女暖虐疟挪懦糯诺哦欧鸥殴藕呕偶沤啪趴爬帕怕琶拍排牌徘湃派攀潘盘磐盼畔判叛乓庞旁耪胖抛咆刨炮袍跑泡呸胚培裴赔陪配佩沛喷盆砰抨烹澎彭蓬棚硼篷膨朋鹏捧碰坯砒霹批披劈琵毗啤脾疲皮匹痞僻屁譬篇偏片骗飘漂瓢票撇瞥拼频贫品聘乒坪苹萍平凭瓶评屏坡泼颇婆破魄迫粕剖扑铺仆莆葡菩蒲埔朴圃普浦谱曝瀑期欺栖戚妻七凄漆柒沏其棋奇歧畦崎脐齐旗祈祁骑起岂乞企启契砌器气迄弃汽泣讫掐洽牵扦钎铅千迁签仟谦乾黔钱钳前潜遣浅谴堑嵌欠歉枪呛腔羌墙蔷强抢橇锹敲悄桥瞧乔侨巧鞘撬翘峭俏窍切茄且怯窃钦侵亲秦琴勤芹擒禽寝沁青轻氢倾卿清擎晴氰情顷请庆琼穷秋丘邱球求囚酋泅趋区蛆曲躯屈驱渠取娶龋趣去圈颧权醛泉全痊拳犬券劝缺炔瘸却鹊榷确雀裙群然燃冉染瓤壤攘嚷让饶扰绕惹热壬仁人忍韧任认刃妊纫扔仍日戎茸蓉荣融熔溶容绒冗揉柔肉茹蠕儒孺如辱乳汝入褥软阮蕊瑞锐闰润若弱撒洒萨腮鳃塞赛三叁伞散桑嗓丧搔骚扫嫂瑟色涩森僧莎砂杀刹沙纱傻啥煞筛晒珊苫杉山删煽衫闪陕擅赡膳善汕扇缮墒伤商赏晌上尚裳梢捎稍烧芍勺韶少哨邵绍奢赊蛇舌舍赦摄射慑涉社设砷申呻伸身深娠绅神沈审婶甚肾慎渗声生甥牲升绳省盛剩胜圣师失狮施湿诗尸虱十石拾时什食蚀实识史矢使屎驶始式示士世柿事拭誓逝势是嗜噬适仕侍释饰氏市恃室视试收手首守寿授售受瘦兽蔬枢梳殊抒输叔舒淑疏书赎孰熟薯暑曙署蜀黍鼠属术述树束戍竖墅庶数漱恕刷耍摔衰甩帅栓拴霜双爽谁水睡税吮瞬顺舜说硕朔烁斯撕嘶思私司丝死肆寺嗣四伺似饲巳松耸怂颂送宋讼诵搜艘擞嗽苏酥俗素速粟僳塑溯宿诉肃酸蒜算虽隋随绥髓碎岁穗遂隧祟孙损笋蓑梭唆缩琐索锁所塌他它她塔獭挞蹋踏胎苔抬台泰酞太态汰坍摊贪瘫滩坛檀痰潭谭谈坦毯袒碳探叹炭汤塘搪堂棠膛唐糖倘躺淌趟烫掏涛滔绦萄桃逃淘陶讨套特藤腾疼誊梯剔踢锑提题蹄啼体替嚏惕涕剃屉天添填田甜恬舔腆挑条迢眺跳贴铁帖厅听烃汀廷停亭庭艇通桐酮瞳同铜彤童桶捅筒统痛偷投头透凸秃突图徒途涂屠土吐兔湍团推颓腿蜕褪退吞屯臀拖托脱鸵陀驮驼椭妥拓唾挖哇蛙洼娃瓦袜歪外豌弯湾玩顽丸烷完碗挽晚皖惋宛婉万腕汪王亡枉网往旺望忘妄威巍微危韦违桅围唯惟为潍维苇萎委伟伪尾纬未蔚味畏胃喂魏位渭谓尉慰卫瘟温蚊文闻纹吻稳紊问嗡翁瓮挝蜗涡窝我斡卧握沃巫呜钨乌污诬屋无芜梧吾吴毋武五捂午舞伍侮坞戊雾晤物勿务悟误昔熙析西硒矽晰嘻吸锡牺稀息希悉膝夕惜熄烯溪汐犀檄袭席习媳喜铣洗系隙戏细瞎虾匣霞辖暇峡侠狭下厦夏吓掀锨先仙鲜纤咸贤衔舷闲涎弦嫌显险现献县腺馅羡宪陷限线相厢镶香箱襄湘乡翔祥详想响享项巷橡像向象萧硝霄削哮嚣销消宵淆晓小孝校肖啸笑效楔些歇蝎鞋协挟携邪斜胁谐写械卸蟹懈泄泻谢屑薪芯锌欣辛新忻心信衅星腥猩惺兴刑型形邢行醒幸杏性姓兄凶胸匈汹雄熊休修羞朽嗅锈秀袖绣墟戌需虚嘘须徐许蓄酗叙旭序畜恤絮婿绪续轩喧宣悬旋玄选癣眩绚靴薛学穴雪血勋熏循旬询寻驯巡殉汛训讯逊迅压押鸦鸭呀丫芽牙蚜崖衙涯雅哑亚讶焉咽阉烟淹盐严研蜒岩延言颜阎炎沿奄掩眼衍演艳堰燕厌砚雁唁彦焰宴谚验殃央鸯秧杨扬佯疡羊洋阳氧仰痒养样漾邀腰妖瑶摇尧遥窑谣姚咬舀药要耀椰噎耶爷野冶也页掖业叶曳腋夜液一壹医揖铱依伊衣颐夷遗移仪胰疑沂宜姨彝椅蚁倚已乙矣以艺抑易邑屹亿役臆逸肄疫亦裔意毅忆义益溢诣议谊译异翼翌绎茵荫因殷音阴姻吟银淫寅饮尹引隐印英樱婴鹰应缨莹萤营荧蝇迎赢盈影颖硬映哟拥佣臃痈庸雍踊蛹咏泳涌永恿勇用幽优悠忧尤由邮铀犹油游酉有友右佑釉诱又幼迂淤于盂榆虞愚舆余俞逾鱼愉渝渔隅予娱雨与屿禹宇语羽玉域芋郁吁遇喻峪御愈欲狱育誉浴寓裕预豫驭鸳渊冤元垣袁原援辕园员圆猿源缘远苑愿怨院曰约越跃钥岳粤月悦阅耘云郧匀陨允运蕴酝晕韵孕匝砸杂栽哉灾宰载再在咱攒暂赞赃脏葬遭糟凿藻枣早澡蚤躁噪造皂灶燥责择则泽贼怎增憎曾赠扎喳渣札轧铡闸眨栅榨咋乍炸诈摘斋宅窄债寨瞻毡詹粘沾盏斩辗崭展蘸栈占战站湛绽樟章彰漳张掌涨杖丈帐账仗胀瘴障招昭找沼赵照罩兆肇召遮折哲蛰辙者锗蔗这浙珍斟真甄砧臻贞针侦枕疹诊震振镇阵蒸挣睁征狰争怔整拯正政帧症郑证芝枝支吱蜘知肢脂汁之织职直植殖执值侄址指止趾只旨纸志挚掷至致置帜峙制智秩稚质炙痔滞治窒中盅忠钟衷终种肿重仲众舟周州洲诌粥轴肘帚咒皱宙昼骤珠株蛛朱猪诸诛逐竹烛煮拄瞩嘱主著柱助蛀贮铸筑住注祝驻抓爪拽专砖转撰赚篆桩庄装妆撞壮状椎锥追赘坠缀谆准捉拙卓桌琢茁酌啄着灼浊兹咨资姿滋淄孜紫仔籽滓子自渍字鬃棕踪宗综总纵邹走奏揍租足卒族祖诅阻组钻纂嘴醉最罪尊遵昨左佐柞做作坐座昇阿啊哎哀唉埃挨癌矮艾爱碍安氨俺岸按案暗昂凹熬傲奥澳八巴叭吧拔把坝爸罢霸白百柏摆败拜班般颁斑搬板版办半伴扮瓣邦帮膀傍棒包胞宝饱保堡报抱豹暴爆卑杯悲碑北贝备背倍被辈奔本崩逼鼻比彼笔币必毕闭辟碧蔽壁避臂边编蝙鞭扁便变遍辨辩标表别宾滨冰兵丙柄饼并病拨波玻剥播脖伯驳泊勃博搏膊薄卜补捕不布步部擦猜才材财裁采彩踩菜蔡参餐残蚕惨灿仓苍舱藏操曹槽草册侧测策层叉插查茶察差拆柴缠产阐颤昌长肠尝偿常厂场畅倡唱抄超巢朝潮吵炒车扯彻撤尘臣沉陈闯衬称趁撑成呈承诚城乘惩程橙吃池驰迟持匙尺齿斥赤翅充冲虫崇抽仇绸愁筹酬丑瞅臭出初除厨础储楚处触川穿传船喘串窗床晨创吹垂锤春纯唇醇词瓷慈辞磁雌此次刺从匆葱聪丛凑粗促催脆翠村存寸措错搭达答打大呆代带待袋逮戴丹单担胆旦但诞弹淡蛋氮当挡党荡刀导岛倒蹈到盗道稻得德的灯登等邓凳瞪低堤滴迪敌笛底抵地弟帝递第颠典点电店垫淀殿雕吊钓调掉爹跌叠蝶丁叮盯钉顶订定丢东冬懂动冻洞都斗抖陡豆督毒读独堵赌杜肚度渡端短段断锻堆队对吨敦蹲盾顿多夺朵躲俄鹅额恶饿鳄恩儿而尔耳二发乏伐罚阀法帆番翻凡烦繁反返犯泛饭范贩方坊芳防妨房肪仿访纺放飞非啡菲肥废沸肺费分纷芬坟粉份奋愤粪丰风枫封疯峰锋蜂冯逢缝凤奉佛否夫肤孵弗伏扶服浮符幅福辐蝠抚府辅腐父付妇负附复赴副傅富赋腹覆该改钙盖溉概干甘杆肝赶敢感刚岗纲缸钢港高搞稿告戈哥胳鸽割歌阁革格葛隔个各给根跟更耕工弓公功攻供宫恭巩拱共贡勾沟钩狗构购够估咕姑孤菇古谷股骨鼓固故顾瓜刮挂拐怪关观官冠馆管贯惯灌罐光广归龟规硅轨鬼柜贵桂滚棍郭锅国果裹过哈孩海害含函寒韩罕喊汉汗旱杭航毫豪好号浩耗呵喝合何和河核荷盒贺褐赫鹤黑嘿痕很狠恨哼恒横衡轰哄红宏洪虹鸿侯喉猴吼后厚候乎呼忽狐胡壶湖葫糊蝴虎互户护花华哗滑化划画话桦怀淮坏欢还环缓幻唤换患荒慌皇黄煌晃灰恢挥辉徽回毁悔汇会绘惠慧昏婚浑魂混活火伙或货获祸惑霍击饥圾机肌鸡积基迹绩激及吉级即极急疾集辑籍几己挤脊计记纪忌技际剂季既济继寂寄加夹佳家嘉甲贾钾价驾架假嫁稼尖坚间肩艰兼监减剪检简碱见件建剑健舰渐践鉴键箭江姜将浆僵疆讲奖蒋匠降交郊娇浇骄胶焦礁角脚搅叫轿较教阶皆接揭街节劫杰洁结捷截竭姐解介戒届界借巾今斤金津筋仅紧锦尽劲近进晋浸禁京经茎惊晶睛精鲸井颈景警净径竞竟敬境静镜纠究九久酒旧救就舅居局菊橘举矩句巨拒具俱剧惧据距聚卷倦决绝觉掘嚼军君均菌俊峻卡开凯慨刊堪砍看康抗炕考烤靠科棵颗壳咳可渴克刻客课肯坑空孔恐控口扣枯哭苦库裤酷夸跨块快宽款狂况矿亏葵愧溃昆困扩括阔垃拉啦喇腊蜡辣来莱赖兰拦栏蓝篮览懒烂滥郎狼廊朗浪捞劳牢老乐勒雷蕾泪类累冷愣厘梨离莉犁璃黎礼李里哩理鲤力历厉立丽利励例隶粒俩连帘怜莲联廉脸练炼恋链良凉梁粮两亮辆量辽疗聊僚了料列劣烈猎裂邻林临淋磷灵玲凌铃陵羚零龄领岭令另溜刘流留硫瘤柳六龙笼隆垄拢楼漏露卢芦炉鲁陆录鹿碌路驴旅铝履律虑率绿氯滤卵乱掠略伦轮论罗萝逻螺裸洛络骆落妈麻马玛码蚂骂吗嘛埋买迈麦卖脉蛮满曼慢漫忙芒盲茫猫毛矛茅茂冒贸帽貌么没枚玫眉梅媒煤霉每美妹门闷们萌盟猛蒙孟梦弥迷谜米泌秘密蜜眠绵棉免勉面苗描秒妙庙灭民敏名明鸣命摸模膜摩磨蘑魔抹末沫陌莫漠墨默谋某母亩牡姆拇木目牧墓幕慕穆拿哪内那纳娜钠乃奶奈耐男南难囊恼脑闹呢嫩能尼泥你拟逆年念娘酿鸟尿捏您宁凝牛扭纽农浓弄奴努怒女暖挪诺哦欧偶爬帕怕拍排牌派攀盘判叛盼庞旁胖抛炮跑泡胚陪培赔佩配喷盆朋棚蓬鹏膨捧碰批披皮疲脾匹屁譬片偏篇骗漂飘瓢票拼贫频品平评凭苹屏瓶萍坡泼颇婆迫破剖扑铺葡蒲朴浦普谱七妻栖戚期欺漆齐其奇歧骑棋旗企岂启起气弃汽契砌器恰千迁牵铅谦签前钱潜浅遣欠枪腔强墙抢悄敲乔桥瞧巧切茄且窃亲侵秦琴禽勤青氢轻倾清情晴顷请庆穷丘秋蚯求球区曲驱屈躯趋取娶去趣圈全权泉拳犬劝券缺却雀确鹊裙群然燃染嚷壤让饶扰绕惹热人仁忍认任扔仍日绒荣容溶熔融柔肉如儒乳辱入软锐瑞润若弱撒洒萨塞赛三伞散桑嗓丧扫嫂色森僧杀沙纱刹砂傻啥晒山杉衫珊闪陕扇善伤商赏上尚梢烧稍少绍哨舌蛇舍设社射涉摄申伸身深神审婶肾甚渗慎升生声牲胜绳省圣盛剩尸失师诗施狮湿十什石时识实拾蚀食史使始驶士氏世市示式事侍势视试饰室是适逝释收手守首寿受兽售授瘦书抒叔枢殊疏舒输蔬熟暑署属鼠薯术束述树竖数刷耍衰摔甩帅双霜爽谁水税睡顺瞬说丝司私思斯撕死四寺似饲松耸宋送颂搜艘苏俗诉肃素速宿塑酸蒜算虽随髓岁遂碎穗孙损笋缩所索锁他它她塌塔踏胎台抬太态泰贪摊滩坛谈潭坦叹炭探碳汤唐堂塘糖躺趟涛掏逃桃陶淘萄讨套特疼腾藤梯踢啼提题蹄体替天添田甜填挑条跳贴铁厅听廷亭庭停蜓挺艇通同桐铜童统桶筒痛偷头投透突图徒涂途屠土吐兔团推腿退吞托拖脱驼妥拓唾挖哇蛙娃瓦歪外弯湾丸完玩顽挽晚碗万汪亡王网往忘旺望危威微为围违唯惟维伟伪尾纬委萎卫未位味胃谓喂慰魏温文纹闻蚊吻稳问翁窝我沃卧握乌污屋无吴吾五午伍武舞务物误悟雾夕西吸希析息牺悉惜晰稀溪锡熙嘻膝习席袭媳洗喜戏系细隙虾瞎峡狭辖霞下吓夏厦仙先纤掀鲜闲弦贤咸衔嫌显险县现线限宪陷献腺乡相香厢湘箱详祥翔享响想向巷项象像橡削消萧硝销小晓孝效校笑些歇协胁斜谐携鞋写泄泻卸屑械谢蟹心辛欣新信兴星猩刑行形型醒杏姓幸性凶兄匈胸雄熊休修羞朽秀绣袖嗅须虚需徐许序叙畜绪续蓄宣玄悬旋选穴学雪血寻巡询循训讯迅压呀鸦鸭牙芽崖哑雅亚咽烟淹延严言岩沿炎研盐颜衍掩眼演厌宴艳验焰雁燕央扬羊阳杨洋仰养氧痒样腰邀摇遥咬药要耀爷也冶野业叶页夜液一伊衣医依仪夷宜姨移遗疑乙已以矣蚁椅义亿忆艺议亦异役抑译易疫益谊逸意溢毅翼因阴音吟银引饮蚓隐印应英婴鹰迎盈营蝇赢影映硬哟拥永泳勇涌用优忧幽悠尤犹由邮油游友有又右幼诱于予余鱼娱渔愉愚与宇羽雨语玉吁育郁狱浴预域欲喻寓御裕遇愈誉豫元员园原圆袁援缘源远怨院愿曰约月岳钥悦阅跃越云匀允孕运晕韵蕴杂砸灾栽宰载再在咱暂赞脏葬遭糟早枣藻灶皂造噪燥躁则择泽责贼怎曾增赠渣扎眨炸摘宅窄债沾粘展占战站张章涨掌丈仗帐胀账障招找召兆赵照罩遮折哲者这浙针侦珍真诊枕阵振镇震争征挣睁蒸整正证郑政症之支汁芝枝知织肢脂蜘执直值职植殖止只旨址纸指趾至志制治质致智置中忠终钟肿种仲众重州舟周洲轴宙皱骤朱株珠诸猪蛛竹烛逐主煮嘱住助注贮驻柱祝著筑抓爪专砖转赚庄桩装壮状撞追准捉桌着仔兹姿资滋籽子紫字自宗综棕踪总纵走奏租足族阻组祖钻嘴最罪醉尊遵昨左作坐座做蔼隘庵鞍黯肮拗袄懊扒芭疤捌跋靶掰扳拌绊梆绑榜蚌谤磅镑苞褒雹鲍狈悖惫笨绷泵蹦匕鄙庇毙痹弊璧贬匾辫彪憋鳖瘪彬斌缤濒鬓秉禀菠舶渤跛簸哺怖埠簿睬惭沧糙厕蹭茬岔豺掺搀禅馋蝉铲猖敞钞嘲澈忱辰铛澄逞秤痴弛侈耻宠畴稠锄雏橱矗揣囱疮炊捶椿淳蠢戳绰祠赐醋簇窜篡崔摧悴粹搓撮挫瘩歹怠贷耽档叨捣祷悼蹬嘀涤缔蒂掂滇巅碘佃甸玷惦奠刁叼迭谍碟鼎董栋兜蚪逗痘睹妒镀缎兑墩盹囤钝咄哆踱垛堕舵惰跺讹娥峨蛾扼鄂愕遏噩饵贰筏矾妃匪诽吠吩氛焚忿讽敷芙拂俘袱甫斧俯脯咐缚尬丐柑竿尴秆橄赣冈肛杠羔膏糕镐疙搁蛤庚羹埂耿梗蚣躬汞苟垢沽辜雇寡卦褂乖棺逛闺瑰诡癸跪亥骇酣憨涵悍捍焊憾撼翰夯嚎皓禾烘弘弧唬沪猾徊槐宦涣焕痪凰惶蝗簧恍谎幌卉讳诲贿晦秽荤豁讥叽唧缉畸箕稽棘嫉妓祭鲫冀颊奸歼煎拣俭柬茧捡荐贱涧溅槛缰桨酱椒跤蕉侥狡绞饺矫剿缴窖酵秸睫芥诫藉襟谨荆兢靖窘揪灸玖韭臼疚拘驹鞠桔沮炬锯娟捐鹃绢眷诀倔崛爵钧骏竣咖揩楷勘坎慷糠扛亢拷铐坷苛磕蝌垦恳啃吭抠叩寇窟垮挎筷筐旷框眶盔窥魁馈坤捆廓睐婪澜揽缆榄琅榔唠姥涝烙酪垒磊肋擂棱狸漓篱吏沥俐荔栗砾痢雳镰敛粱谅晾寥嘹撩缭瞭咧琳鳞凛吝赁躏拎伶聆菱浏琉馏榴咙胧聋窿娄搂篓陋庐颅卤虏赂禄吕侣屡缕峦抡仑沦啰锣箩骡蟆馒瞒蔓莽锚卯昧媚魅氓朦檬锰咪靡眯觅缅瞄渺藐蔑皿闽悯冥铭谬馍摹茉寞沐募睦暮捺挠瑙呐馁妮匿溺腻捻撵碾聂孽拧狞柠泞钮脓疟虐懦糯殴鸥呕藕趴啪耙徘湃潘畔乓螃刨袍沛砰烹彭澎篷坯劈霹啤僻翩撇聘乒坪魄仆菩圃瀑曝柒凄祈脐崎鳍乞迄泣掐洽钳乾黔谴嵌歉呛跷锹侨憔俏峭窍翘撬怯钦芹擒寝沁卿蜻擎琼囚岖渠痊瘸冉瓤壬刃纫韧戎茸蓉榕冗揉蹂蠕汝褥蕊闰腮叁搔骚臊涩瑟鲨煞霎筛删煽擅赡裳晌捎勺奢赦呻绅沈笙甥矢屎恃拭柿嗜誓梳淑赎蜀曙恕庶墅漱蟀拴栓涮吮烁硕嗽嘶巳伺祀肆讼诵酥粟溯隋祟隧唆梭嗦琐蹋苔汰瘫痰谭檀毯棠膛倘淌烫滔誊剔屉剃涕惕恬舔迢帖彤瞳捅凸秃颓蜕褪屯豚臀驮鸵椭洼袜豌宛婉惋皖腕枉妄偎薇巍帷苇畏尉猬蔚瘟紊嗡涡蜗呜巫诬芜梧蜈侮捂鹉勿戊昔犀熄蟋徙匣侠暇馅羡镶宵潇箫霄嚣淆肖哮啸蝎邪挟懈芯锌薪馨衅腥汹锈戌墟旭恤酗婿絮轩喧癣炫绚渲靴薛勋熏旬驯汛逊殉丫押涯衙讶焉阎蜒檐砚唁谚堰殃秧鸯漾夭吆妖尧肴姚窑谣舀椰腋壹怡贻胰倚屹邑绎姻茵荫殷寅淫瘾莺樱鹦荧莹萤颖佣庸咏踊酉佑迂淤渝隅逾榆舆屿禹芋冤鸳渊猿苑粤耘陨酝哉赃凿蚤澡憎咋喳轧闸乍诈栅榨斋寨毡瞻斩盏崭辗栈绽彰樟杖昭沼肇辙蔗贞斟疹怔狰筝拯吱侄帜挚秩掷窒滞稚衷粥肘 帚咒昼拄瞩蛀铸拽撰 妆幢椎锥坠缀赘谆卓拙
灼茁浊酌啄琢咨姊揍卒佐佘赊1234567890-=！@#￥%……&*()~:"{}[]|\?/<>,.;'+abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZπアナスイシリーズからドムをプレゼンりやかなベルガモットオジビタからロピカなフアやャクヤなどがミドっぱくラバニラサダウのブはとてもおいしそうなりんかマカョⒶⒷⒸⒹⒺⒻⒼⒽⒾⒿⓀⓁⓂⓃⓄⓅⓆⓇⓈⓉⓊⓋⓌⓍⓎⓏⓐⓑⓒⓓⓔⓕⓖⓗⓘⓙⓚⓛⓜⓝⓞⓟⓠⓡⓢⓣⓤⓥⓦⓧⓨⓩ⒜⒝⒞⒟⒠⒡⒢⒣⒤⒥⒦⒧⒨⒩⒪⒫⒬⒭⒮⒯⒰⒱⒲⒳⒴⒵아무것도난해준게없어받기만했을뿐그래서미안해나같은여자를왜사랑했는지왜떠나야했는지어떻게든우린다시사랑해야해....αβγδεζηθικλμνξοπρστυφχψωΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣΤΥΦΧΨΩабвгдеёжзийклмнопрстуфхцчшщъыьэюяАБВГДЕЁЖЗИЙКЛМНОПРСТУФХЦЧШЩЪЫЬЭЮЯ─━│┃┄┅┆┇┈┉┊┋┌┍┎┏┐┑┒┓└┕┖┗┘┙┚┛├┝┞┟┠┡┢┣┤┥┦┧┨┩┪┫┬┭┮┯┰┱┲┳┴┵┶┷┸┹┺┻┼┽┾┿╀╁╂╃╄╅╆╇╈╉╊╋═║╒╓╔╕╖╗╘╙╚╛╜╝╞╟╠╡╢╣╤╥╦╧╨╩╪╫╬╭╮╯╰╱╲╳◎⊕⊙▽▼§〃〒※♀♂×∫∮∵∴φω░▒☻☺☼♠◈♤♦◊♨♣♧♥♡▦▩▣▧▨▤▥▪▫◘◙☏☎☜☞◑◐◦°°✔☑₪‧；︰…‥﹐﹒˙·﹔﹕‘’“”〝〞‵′〃₪εїз™✿｡◕‿◕｡◕｡◕⊙◎☺☻▧▨♨◐◑↔↕▪♦▀▬(︶ε.︶メ)▣▤▥▦▩♭☀ஐ☁☂☃☄❉❊❋❖❤❥❦❧☇☈☉☊☋☌☍☑☒☢☸☹☽☾✙✈✉✌✁✎✐❀✰❁➳➽〠〄㍿♝♞➴➵℗☪♈₪¤큐≡✩✫✬✭✮✰❁❀✿✾❃✺❇❈❊❉✱✲♋☯㈱㊣男女秘日月金木水火土株有社名特财祝劳适优㊞注项休写医宗学监企资协夜秘㊤㊥㊦㊧㊨㊚㊛㊙㊝㊊㊋㊌㊍㊎㊏㊐㈱㍿囍卐卍ォミ灬彡ツ〡〢〣〤〥〦〧〨〩❶❷❸❹❺❻❼❽❾❿⑴⑵⑶⑷⑸⑹⑺⑻⑼⑽⑾⑿⒀⒁⒂⒃⒄⒅⒆⒇⓪①②③④⑤⑥⑦⑧⑨⑩⑪⑫⑬⑭⑮⑯⑰⑱⑲⑳一二三四五六七八九十一二三四五六七八九十ⅠⅡⅢⅣⅤⅥⅦⅧⅨⅩⅪⅫ⒈⒉⒊⒋⒌⒍⒎⒏⒐⒑⒒⒓⒔⒕⒖⒗⒘⒙⒚⒛ⅠⅡⅢⅣⅤⅥⅦⅧⅨⅩ♩♪♫♬♯♭♮⺁⺂⺃⺄⺅⺆⺇⺈⺉⺊⺋⺌⺍⺎⺏⺐⺑⺒⺓⺔⺕⺖⺗⺘⺙⺛⺜⺝⺞⺟⺠⺡⺢⺣⺤⺥⺦⺧⺨⺩⺪⺫⺬⺭⺮⺯⺰⺱⺲⺳⺴⺵⺶⺷⺸⺹⺺⺻⺼⺽⺾⺿⻀⻁⻂⻃⻄⻅⻆⻇⻈⻉⻊⻋⻌⻍⻎⻏⻐⻑⻒⻓⻔⻕⻖⻗⻘⻙⻚⻛⻜⻝⻞⻟⻠⻡⻢⻣⻤⻥⻦⻧⻨⻩⻪⻫⻬⻭⻮⻯⻰⻱⻲⻳⼀⼁⼂⼃⼄⼅⼆⼇⼈⼉⼊⼋⼌⼍⼎⼏⼐⼑⼒⼓⼔⼕⼖⼗⼘⼙⼚⼛⼜⼝⼞⼟⼠⼡⼢⼣⼤⼥⼦⼧⼨⼩⼪⼫⼬⼭⼮⼯⼰⼱⼲⼳⼴⼵⼶⼷⼸⼹⼺⼻⼼⼽⼾⼿⽀⽁⽂⽃⽄⽅⽆⽇⽈⽉⽊⽋⽌⽍⽎⽏⽐⽑⽒⽓⽔⽕⽖⽗⽘⽙⽚⽛⽜⽝⽞⽟⽠⽡⽢⽣⽤⽥⽦⽧⽨⽩⽪⽫⽬⽭⽮⽯⽰⽱⽲⽳⽴⽵⽶⽷⽸⽹⽺⽻⽼⽽⽾⽿⾀⾁⾂⾃⾄⾅⾆⾇⾈⾉⾊⾋⾌⾍⾎⾏⾐⾑⾒⾓⾔⾕⾖⾗⾘⾙⾚⾛⾜⾝⾞⾟⾠⾡⾢⾣⾤⾥⾦⾧⾨⾩⾪⾫⾬⾭⾮⾯⾰⾱⾲⾳⾴⾵⾶⾷⾸⾹⾺⾻⾼⾽⾾⾿⿀⿁⿂⿃⿄⿅⿆⿇⿈⿉⿊⿋⿌⿍⿎⿏⿐⿑⿒⿓⿔⿕开朩囘囙囚四囜囝回囟因囡团団囤囥囦囧囨囩囱囫囬园囮囯困囱囲図围囵囶囷囸囹固囻囼国图囿圀圁圂圃圄圅圆囵圈圉圊国圌围圎圏圐圑园圆圔圕图圗团圙圚圛圜圝圞`1234567890－=qwertyuiop[]、asdfghjkl；‘zxcvbnm，。/QWERTYUIOPASDFGHJKLZXCVBNM！·#￥%……—*…（）～…——+—{—}—|—：“《》？〈〉@&\↑↓→←↘↙↖↗↔↕➳➴➵➶➷➹▶➩➾➔➘➚➛➝➞➟➠➡➢➤➥➦➧↚↛↜⇜↝↞↟↠↡↢↣↤↥↦↧⇅⇆⇇⇈⇉⇊⇋⇌⇍⇎⇏⇐⇑⇓⇒⇔⇖⇗⇘⇙↩↪↫↬↭↮↯↰↱↲↳↴↵↶↷↸↹↺↻⇞⇟⇠⇡⇢⇣⇤⇥⇦⇧⇨⇩⇪ㄅㄉˇˋㄓˊ˙ㄚㄞㄢㄦㄆㄊㄍㄐㄔㄗㄧㄛㄟㄣㄇㄋㄎㄑㄕㄘㄨㄜㄠㄤㄈㄌㄏㄒㄖㄙㄩㄝㄡㄥ≈≡≠=≤≥<>≮≯∷±+－×÷/∫∮∝∞∧∨∑∏∪∩∈∵∴⊥∥∠⌒⊙≌∽√∟∣∶≒≦≧⊕⊿°′″$￡￥‰%℃¤￠āáǎàōóǒòêēéěèīíǐìūúǔùǖǘǚǜüńňǹɑɡ。，、＇：∶；?‘’“”〝〞ˆˇ﹕︰﹔﹖﹑·¨….¸;！´？！～—ˉ｜‖＂〃｀@﹫¡¿﹏﹋﹌︴々﹟#﹩$﹠&﹪%*﹡﹢﹦﹤‐￣¯―﹨ˆ˜﹍﹎+=<＿_-\ˇ~﹉﹊（）〈〉‹›﹛﹜『』〖〗［］《》〔〕{}「」【】︵︷︿︹︽_﹁﹃︻︶︸﹀︺︾ˉ﹂﹄︼〔〕一丨丿丶乛一乙二十丁厂七卜八人入儿九匕几了乃刀力又乜三干亍于亏士土工才下寸丈大兀与万弋上小口山巾千乞川亿彳个么久勺丸夕凡及广亡门丫义之尸已巳弓己卫孑子孓也女飞刃习叉马乡幺丰王井开亓夫天元无韦云专丐扎廿艺木五支厅卅不仄太犬区历友歹尤匹厄车巨牙屯戈比互切瓦止少曰日中贝内水冈见手午牛毛气壬升夭长仁仃什片仆仉化仇币仂仍仅斤爪反兮刈介父爻从仑今凶分乏公仓月氏勿风欠丹匀乌勾殳凤卞六文亢方闩火为斗忆计订户讣认讥冗心尹尺夬引丑爿巴孔队办以允邓予劝双书毋幻玉刊末未示击邗戋打巧正扑卉扒邛功扔去甘世艾艽古节艿本术札可叵匝丙左厉丕石右布夯龙戊平灭轧东匜劢卡北占凸卢业旧帅归目旦且叮叶甲申号电田由卟叭只央史叱叽兄叼叩叫叻叨另叹冉皿凹囚四生失矢氕乍禾仨仕丘付仗代仙仟仡仫伋们仪白仔他仞斥卮瓜乎丛令用甩印氐乐尔句匆犰册卯犯外处冬鸟务刍包饥主市庀邝立冯邙玄闪兰半汀汁汇头汈汉忉宁穴宄它讦讧讨写让礼讪讫训必议讯记永司尻尼民弗弘阢出阡辽奶奴尕加召皮边孕发圣对弁台矛纠驭母幼丝匡耒邦玎玑式迂刑邢戎动圩圬圭扛寺吉扣扦圪考托圳老圾巩执扩圹扪扫圯圮地扬场耳芋芏共芊芍芨芄芒亚芝芎芑芗朽朴机权过亘臣吏再协西压厌厍戌在百有存而页匠夸夺夼灰达戍尥列死成夹夷轨邪尧划迈毕至此乩贞师尘尖劣光当吁早吐吓旯曳虫曲团同吕吊吃因吸吗吆屿屹岌帆岁回岂屺则刚网肉凼囝囡钆钇年朱缶氘氖牝先丢廷舌竹迁乔迄伟传乒乓休伍伎伏伛优臼伢伐仳延佤仲仵件任伤伥价伦份伧华仰伉仿伙伪伫自伊血向囟似后行甪舟全会杀合兆企汆氽众爷伞创刖肌肋朵杂夙危旬旭旮旨负犴刎犷匈犸舛各名多凫争邬色饧冱壮冲妆冰庄庆亦刘齐交次衣产决亥邡充妄闭问闯羊并关米灯州汗污江汕汔汲汐汛汜池汝汤汊忖忏忙兴宇守宅字安讲讳讴军讵讶祁讷许讹论讼农讽设访诀聿寻那艮厾迅尽导异弛阱阮孙阵阳收阪阶阴防丞奸如妁妇妃好她妈戏羽观牟欢买纡红纣驮纤纥驯纨约级纩纪驰纫巡佘寿玕\弄玙麦玖玚玛形进戒吞远违韧运扶抚坛抟技坏抔抠坜扰扼拒找批扯址走抄汞坝贡攻赤圻折抓扳坂抡扮抢扺孝坎坍均坞抑抛投抃\坟坑抗坊抖护壳志块抉扭声把报拟抒却劫毐芙芫芜苇邯芸芾芰苈苊苣芽芷芮苋芼苌花芹芥苁芩芬苍芪芴芡芟苄芳严苎芦芯劳克芭苏苡杆杜杠材村杖杌杏杉巫杓极杧杞李杨杈求忑孛甫匣更束吾豆两邴酉丽医辰励邳否还矶奁豕尬歼来忒连欤轩轪轫迓邶忐芈步卤卣邺坚肖旰旱盯呈时吴呋助县里呓呆吱吠呔呕园呖呃旷围呀吨旸吡町足虬邮男困吵串呙呐呗员听吟吩呛吻吹呜吭吣吲吼邑吧囤别吮岍帏岐岖岈岗岘帐岑岚兕财囵囫钉针钊钋钌迕氙氚牡告我乱利秃秀私岙每佞兵邱估体何佐伾佑攸但伸佃佚作伯伶佣低你佝佟住位伴佗身皂伺佛伽囱近彻役彷返佘余希佥坐谷孚妥豸含邻坌岔肝肟肛肚肘肠邸龟甸奂免劬狂犹狈狄角删狃狁鸠条彤卵灸岛邹刨饨迎饩饪饫饬饭饮系言冻状亩况亨庑床庋库庇疔疖疗吝应冷这庐序辛肓弃冶忘闰闱闲闳间闵闶闷羌判兑灶灿灼炀弟沣汪沅沄沐沛沔汰沤沥沌沘沏沚沙汩汨汭汽沃沂沦汹汾泛沧沨沟没汴汶沆沩沪沈沉沁泐怃忮怀怄忧忡忤忾怅忻忪怆忭忱快忸完宋宏牢究穷灾良证诂诃启评补初社祀祃诅识诈诉罕诊诋诌词诎诏诐译诒君灵即层屁屃尿尾迟局改张忌际陆阿孜陇陈阽阻阼附坠陀陂陉妍妩妓妪妣妙妊妖妗姊妨妫妒妞姒妤努邵劭忍刭劲甬邰矣鸡纬纭驱纯纰纱纲纳纴纵驳纶纷纸纹纺纻驴纽纾奉玩玮环玡武青责现玫玠玢玥表玦甙盂忝规匦抹卦邽坩坷坯拓垅拢拔抨坪拣拤拈坫垆坦担坤押抻抽拐拃拖拊者拍顶坼拆拎拥抵坻拘势抱拄垃拉拦幸拌拧坨坭抿拂拙招坡披拨择拚抬拇坳拗耵其耶取茉苷苦苯昔苛苤若茂茏苹苫苴苜苗英苒苘茌苻苓茚苟茆茑苑苞范茓茔茕直苠茀茁茄苕茎苔茅枉林枝杯枢枥柜枇杪杳枘枧杵枚枨析板枞松枪枫构杭枋杰述枕杻杷杼丧或画卧事刺枣雨卖矸郁矻矾矽矿砀码厕奈刳奔奇奄奋态瓯欧殴垄殁郏妻轰顷转轭斩轮软到郅鸢非叔歧肯齿些卓虎虏肾贤尚盱旺具昊昙果味杲昃昆国哎咕昌呵咂畅呸昕明易咙昀昂旻昉炅咔畀虮迪典固忠咀呷呻黾咒咋咐呱呼呤咚鸣咆咛咏呢咄呶咖呦咝岵岢岸岩帖罗岿岬岫帜帙帕岭岣峁刿峂迥岷剀凯帔峄沓败账贩贬购贮囹图罔钍钎钏钐钓钒钔钕钗邾制知迭氛迮垂牦牧物乖刮秆和季委竺秉迤佳侍佶岳佬佴供使侑佰侉例侠臾侥版侄岱侦侣侗侃侧侏凭侨侩佻佾佩货侈侪佼依佯侬帛卑的迫阜侔质欣郈征徂往爬彼径所舍金刽郐刹命肴郄斧怂爸采籴觅受乳贪念贫忿瓮戗肼肤朊肺肢肽肱肫肿肭胀朋肷股肮肪肥服胁周剁昏迩郇鱼兔狉狙狎狐忽弥狗狍狞狒咎备炙枭饯饰饱饲饳饴冽变京享冼庞店夜庙府底庖疟疠疝疙疚疡剂卒郊兖庚废净妾盲放刻於劾育氓闸闹郑券卷单炜炬炖炒炝炊炕炎炉炔沫浅法泔泄沽沭河泷沾泸沮泪油泱泅泗泊泠泜泺泃沿泖泡注泣泫泮泞沱泻泌泳泥泯沸泓沼波泼泽泾治怔怯怙怵怖怦怛怏性怍怕怜怩怫怊怿怪怡学宝宗定宕宠宜审宙官空帘穸穹宛实宓诓诔试郎诖诗诘戾肩房诙戽诚郓衬衫衩祆祎祉视祈诛诜话诞诟诠诡询诣诤该详诧诨诩建肃隶录帚屉居届刷鸤\屈弧弥弦承孟陋戕陌孤孢陕亟降函陔限卺妹姑姐妲妯姓姗妮始帑弩孥驽姆虱迦迢驾叁参迨艰线绀绁绂练驵组绅细驶织驷驸驹终绉驺驻绊驼绋绌绍驿绎经骀贯甾砉耔契贰奏春帮珏珐珂珑玷玳珀顸珍玲珊珉珈玻毒型韨拭挂封持拮拷拱垭挝垣项垮挎垯挞城挟挠垤政赴赵赳贲垱挡拽垌哉垲挺括挢埏郝垍垧垢拴拾挑垛指垫挣挤垓垟拼垞挖按挥挦挪垠拯拶某甚荆茸革茜茬荐荙巷荚荑贳荛荜茈带草茧茼莒茵茴茱莛荞茯荏荇荃荟茶荀茗荠茭茨荒垩茳茫荡荣荤荥荦荧荨茛故荩胡荪荫茹荔南荬荭药柰标栈柑枯栉柯柄柘栊柩枰栋栌相查柙枵柚枳柞柏柝栀柃柢栎枸栅柳柱柿栏柈柠柁枷柽树勃剌郚剅要酊郦柬咸威歪甭研砖厘砗厚砑砘砒砌砂泵砚斫砭砜砍面耐耍奎耷牵鸥虺残殂殃殇殄殆轱轲轳轴轵轶轷轸栎轺轻鸦虿皆毖韭背战觇点虐临览竖尜省削尝哐昧眄眍盹是郢眇眊盼眨昽眈哇咭哄哑显冒映禺哂星昨咴曷昴咧昱昵咦哓昭哔畎畏毗趴呲胄胃贵畋畈界虹虾虼虻蚁思蚂盅咣虽品咽骂哕剐郧勋咻哗囿咱咿响哌哙哈哚咯哆咬咳咩咪咤哝哪哏哞哟峙炭峡峣罘帧罚峒峤峋峥峧帡贱贴贶贻骨幽钘钙钚钛钝钞钟钡钠钢钣钤钥钦钧钨钩钪钫钬钭钮钯御缸拜看矩矧毡氡氟氢牯怎郜牲选适秕秒香种秭秋科重复竽竿笈笃俦段俨俅便俩俪叟垡贷牮顺修俏俣俚保俜促俄俐侮俭俗俘信皇泉皈鬼侵禹侯追俑俟俊盾逅待徊徇徉衍律很须舢舣叙俞弇郗剑逃俎郤爰郛食瓴盆胚胧胨胩胪胆胛胂胜胙胍胗胝朐胞胖脉胫胎鸨葡勉狨狭狮独狯狰狡飐飑狩狱狠狲訇訄逄昝贸怨急饵饶蚀饷饸饹饺饻胤饼峦弯孪娈将奖哀亭亮庤度弈奕迹庭庥疬疣疥疭疮疯疫疢疤庠咨姿亲竑音彦飒帝施闺闻闼闽闾闿阀阁阂差养美羑姜迸叛送类籼迷籽娄前酋首逆兹总炳炻炼炟炽炯炸烀烁炮炷炫烂烃剃洼洁洱洪洹洒洧洌浃柒浇泚浈浉浊洞洇洄测洙洗活洑涎洎洫派浍洽洮染洵洚洺洛浏济洨浐洋洴洣洲浑浒浓津浔浕洳恸恃恒恹恢恍恫恺恻恬恤恰恂恪恼恽恨举觉宣宦宥宬室宫宪突穿窀窃客诫冠诬语扁扃袆衲衽袄衿袂祛祜祓祖神祝祚诮祗祢祠误诰诱诲诳鸩说昶诵郡垦退既屋昼咫屏屎弭费陡逊牁眉胥孩陛陟陧陨除险院娃姞姥娅姨娆姻姝娇姚姽姣姘姹娜怒架贺盈怼羿勇炱怠癸蚤柔矜垒绑绒结绔骁绕骄骅绗绘给绚彖绛络骆绝绞骇统骈耕耘耖耗耙艳挈恝泰秦珥珙顼珰珠珽珩珧珣珞琤班珲敖素匿蚕顽盏匪恚捞栽捕埔埂捂振载赶起盐捎捍埕捏埘埋捉捆捐埚埙损袁挹捌都哲逝耆耄捡挫捋埒换挽贽挚热恐捣垸壶捃捅盍埃挨耻耿耽聂莰茝荸莆恭莽莱莲莳莫莴莪莉莠莓荷莜莅荼莶莩荽获莸荻莘晋恶莎莞莹茛莺真莙鸪莼框梆桂桔栲栳郴桓栖桡桎桢桄档桐桤株梃栝桥桕桦桁栓桧桃桅栒格桩校核样栟桉根栩逑索逋彧哥速鬲豇逗栗贾酐酎酌配酏逦翅辱唇厝孬夏砝砹砸砺砰砧砷砟砼砥砾砣础破硁恧原套剞逐砻烈殊殉顾轼轾轿辀辁辂较鸫顿趸毙致剕龀柴桌鸬虔虑监紧逍党眬唛逞晒晟眩眠晓眙唝哧哳哮唠鸭晃哺哽唔晔晌晁剔晏晖晕鸮趵趿畛蚌蚨蚜蚍蚋蚬畔蚝蚧蚣蚊蝌蚓哨唢哩圃哭圄哦唣唏恩盎唑鸯唤唁哼唧啊唉唆帱崂崃罡罢罟峭峨峪峰圆觊峻贼贿赂赃赅赆钰钱钲钳钴钵钷钹钺钻钼钽钾钿铀铁铂铃铄铅铆铈铉铊铋铌铍铎眚缺氩氤氦氧氨毪特牺造乘敌舐秣秫秤租秧积盉秩称秘透笄笕笔笑笊笫笏笋笆俸倩债俵倻借偌值倚俺倾倒俳俶倬倏倘俱倡候赁恁倭倪俾倜隼隽倞俯倍倦倓倌倥臬健臭射皋躬息郫倨倔衄颀徒徕徐殷舰舨舱般航舫瓞途拿釜耸爹舀爱豺豹奚鬯衾鸰颁颂翁胯胰胱胴胭脍脎脆脂胸胳脏脐胶脑胲胼朕脒胺脓鸱玺鱽鸲逛狴狸狷猁狳猃狺逖狼卿狻逢桀鸵留袅眢鸳皱饽饿馀馁凌凇凄栾挛恋桨浆衰勍衷高亳郭席准座症疳疴病疽疸疾痄斋疹痈疼疱疰痃痂疲痉脊效离衮紊唐凋颃瓷资恣凉站剖竞部旁旆旄旅旃畜阃阄阅阆羞羔恙瓶桊拳敉粉料粑益兼朔郸烤烘烜烦烧烛烟烨烩烙烊剡郯烬递涛浙涝浡浦涑浯酒涞涟涉娑消涅涠浞涓涢涡浥涔浩海浜涂浠浴浮涣浼涤流润涧涕浣浪浸涨烫涩涌涘浚悖悚悟悭悄悍悝悃悒悔悯悦悌悢悛害宽宸家宵宴宾窍窅窄容窈剜宰案请朗诸诹诺读扅诼冢扇诽袜袪袒袖袗袍袢被袯祯祧祥课冥诿谀谁谂调冤谄谅谆谇谈谊剥恳展剧屑屐屙弱陵陬勐奘疍牂蚩祟陲陴陶陷陪烝姬娠娱娌娉娟娲恕娥娩娴娣娘娓婀砮哿畚通能难逡预桑剟绠骊绡骋绢绣验绤绥绦骍继绨骎骏邕鸶赊彗耜焘舂琎球琏琐理琇麸琉琅捧掭堵揶措描埴域捺掎埼掩埯捷捯排焉掉掳掴埸堌捶赦赧推堆捭埠晳掀逵授捻埝堋教堍掏掐掬鸷掠掂掖培掊接堉掷掸控捩掮探悫埭埽据掘掺掇掼职聃基聆勘聊聍娶菁菝著菱萁菥菘堇勒黄萘萋勚菲菽菖萌萜萝菌萎萸萑菂菜棻菔菟萄萏菊萃菩菼菏萍菹菠菪菅菀萤营萦乾萧菰菡萨菇械梽彬梵梦婪梗梧梾梢梏梅觋检桴桷梓梳棁梯桫棂桶梭救啬郾匮曹敕副豉票鄄酝酞酗酚厢厣戚戛硎硅硭硒硕硖硗硐硚硇硌鸸瓠匏奢盔爽厩聋龚殒殓殍盛赉匾雩雪辄辅辆堑龁颅虚彪雀堂常眶眭唪眦啧匙晡晤晨眺眵睁眯眼眸悬野圊啪啦喏喵啉勖曼晦晞晗晚冕啄啭啡畦趼趺距趾啃跃啮跄略蚶蛄蛎蛆蚰蚺蛊圉蚱蚯蛉蛀蛇蛏蚴唬累鄂唱患啰唾唯啤啥啁啕唿啐唼唷啴啖啵啶啷唳啸啜帻崖崎崦崭逻帼崮崔帷崟崤崩崞崇崆崛赇赈婴赊圈铐铑铒铕铗铘铙铚铛铜铝铞铟铠铡铢铣铤铥铧铨铩铪铫铭铬铮铯铰铱铲铳铴铵银铷矫氪牾甜鸹秸梨犁稆秽移秾逶笺筇笨笸笼笪笛笙笮符笱笠笥第笳笤笾笞敏偾做鸺偃偕袋悠偿偶偈偎偲傀偷您偬售停偻偏躯皑兜皎假衅鸻徘徙倘得衔舸舻舳盘舴舶船鸼舷舵斜龛盒鸽瓻敛悉欲彩领翎脚脖脯豚脶脸脞脬脱脘脲朘匐鱾象够逸猜猪猎猫猗凰猖猡猊猞猄猝斛觖猕猛馗祭馃馄馅馆凑减鸾毫孰烹庶庹麻庵庼庾庳痔痍疵痊痒痕廊康庸鹿盗章竟翊商旌族旎旋望袤率阇阈阉阊阋阌阍阎阏阐着羚羝羟盖眷粝粘粗粕粒断剪兽敝焐焊烯焓焕烽焖烷烺焌清渍添渚鸿淇淋淅淞渎涯淹涿渠渐淑淖挲淌淏混淠涸渑淮淦淆渊淫淝渔淘淳液淬涪淤淡淙淀涫深渌涮涵婆梁渗淄情惬悻惜惭悱悼惝惧惕惘悸惟惆惚惊惇惦悴惮惋惨惯寇寅寄寂逭宿窒窑窕密谋谌谍谎谏扈皲谐谑裆袱袼裈裉祷祸祲谒谓谔谕谖谗谙谚谛谜谝逮逯敢尉屠艴弹隋堕郿随蛋隅隈粜隍隗隆隐婧婊婞婳婕娼婢婚婵婶婉胬袈颇颈翌恿欸绩绪绫骐续骑绮绯绰骒绲绳骓维绵绶绷绸绹绺绻综绽绾绿骖缀缁巢耠琫琵琴琶琪瑛琳琦琢琥琨靓琼斑琰琮琯琬琛琚辇替鼋揳揍款堪堞搽塔搭塃揸堰揠堙揩越趄趁趋超揽提堤揖博揾颉揭喜彭揣塄揿插揪搜煮堠耋揄援搀蛰蛩絷塆裁揞搁搓搂搅揎壹握摒揆搔揉掾葜聒斯期欺联葑葚葫靰靸散葳惹蒇葬蒈募葺葛蒉葸萼蓇萩董葆葩葡敬葱蒋葶蒂蒌葓蒎落萱葖韩戟朝葭辜葵棒楮棱棋椰植森棼焚椟椅椒棹棵棍椤棰椎棉椑鹀赍棚椋椁棬棕棺榔楗棣椐椭鹁惠惑逼覃粟棘酣酤酢酥酡酦鹂觌厨厦硬硝硪硷确硫雁厥殖裂雄殚殛颊雳雯辊辋椠暂辌辍辎雅翘辈斐悲紫凿黹辉敞棠牚赏掌晴睐暑最晰量睑睇鼎睃喷戢喋嗒喃喳晶喇遇喊喱喹遏晷晾景喈畴践跖跋跌跗跞跚跑跎跏跛跆遗蛙蛱蛲蛭蛳蛐蛔蛛蜓蛞蜒蛤蛴蛟蛘蛑畯喁喝鹃喂喟斝喘啾嗖喤喉喻喑啼嗟喽嗞喧喀喔喙嵌嵘嵖幅崴遄詈帽嵎崽嵚嵬嵛翙嵯嵝嵫幄嵋赋赌赎赐赑赔黑〔丿〕铸铹铺铻铼铽链铿销锁锃锄锂锅锆锇锈锉锊锋锌锎锏锐锑锒锓锔锕甥掣掰短智矬氰毳毯氮毽氯犊犄犋鹄犍鹅颋剩嵇稍程稀黍桴税稂筐等筘筑策筚筛筜筒筅筏筵筌答筋筝傣傲傅傈舄牍牌傥堡集焦傍傧储遑皓皖粤奥傩遁街惩御徨循舾艇舒畲弑逾颌翕釉番释鹆禽舜貂腈腊腌腓腆腴脾腋腑腙腚腔腕腱腒鱿鲀鲁鲂鲃颍猢猹猩猥猬猾猴飓觞觚猸猱惫飧然馇馈馉馊馋亵装蛮脔就敦裒庾斌痣痨痦痘痞痢痤痪痫痧痛鄌赓竦童瓿竣啻颏鹇阑阒阔阕善翔羡普粪粞尊奠遒道遂孳曾焯焜焰焙焱鹈湛港渫滞湖湘渣渤湮湎湝湨湜渺湿温渴渭溃湍溅滑湃湫溲湟溆渝湲湾渡游溠溇湔滋湉渲溉渥湄滁愤慌惰愠惺愦愕惴愣愀愎惶愧愉愔慨喾割寒富寓窜窝窖窗窘寐谟扉遍雇扊裢裎裣裕裤裥裙祾祺祼谠禅禄幂谡谢谣谤谥谦谧塈遐犀属屡孱弼强粥巽疏隔骘隙隘媒媪絮嫂媛婷媚婿巯毵翚登皴婺骛缂缃缄缅彘缆缇缈缉缌缎缏缑缒缓缔缕骗编缗骙骚缘飨耢瑟瑚鹉瑁瑞瑰瑀瑜瑗瑄瑕遨骜瑙遘韫魂髡肆摄摸填搏塥塬鄢趔趑摅塌摁鼓摆赪携塮蜇搋搬摇搞搪塘搒搐搛搠摈彀毂搌搦摊搡聘蓁戡斟蒜蓍鄞勤靴靳靶鹊蓐蓝墓幕蓦鹋蒽蓓蓖蓊蒯蓟蓬蓑蒿蒺蓠蒟蒡蓄蒹蒴蒲蒗蓉蒙蓂蓥颐蒸献蓣楔椿楠禁楂楚楝楷榄想楫榀楞楸椴槐槌楯榆榇榈槎楼榉楦概楣楹椽裘赖剽甄酮酰酯酪酩酬蜃感碛碍碘碓碑硼碉碎碚碰碇碗碌碜鹌尴雷零雾雹辏辐辑辒输督频龃龄龅龆觜訾粲虞鉴睛睹睦瞄睚嗪睫韪嗷嗉睡睨睢雎睥睬嘟嗜嗑嗫嗬嗔鄙嗦嗝愚戥嗄暖盟煦歇暗暅暄暇照遢暌畸跬跨跶跷跸跣跹跳跺跪路跻跤跟遣蛸蜈蜎蜗蛾蜊蜍蜉蜂蜣蜕畹蛹嗣嗯嗅嗥嗲嗳嗡嗌嗍嗨嗤嗵嗓署置罨罪罩蜀幌嵊嵩嵴骰锖锗错锘锚锛锜锝锞锟锡锢锣锤锥锦锧锨锪锫锩锬锭键锯锰锱矮雉氲犏辞歃稞稚稗稔稠颓愁筹筠筢筮筻筲筼筱签简筷毁舅鼠牒煲催傻像躲鹎魁敫僇衙微徭愆艄觎毹愈遥貊貅貉颔腻腠腩腰腼腽腥腮腭腹腺腧鹏塍媵腾腿詹鲅鲆鲇鲈鲉鲊稣鲋鲌鲍鲏鲐肄猿颖鹐飔飕觥触解遛煞雏馌馍馏馐酱鹑禀亶廒瘃痱痹痼廓痴痿瘐瘁瘅痰瘆廉鄘麂裔靖新鄣歆韵意旒雍阖阗阘阙羧豢誊粳粮数煎猷塑慈煤煳煜煨煅煌煊煸煺滟溱溘滠满漭漠滢滇溥溧溽源滤滥裟溻溷溦滗滫溴滏滔溪滃溜滦漓滚溏滂溢溯滨溶滓溟滘溺滍粱滩滪愫慑慎慥慊誉鲎塞骞寞窥窦窠窣窟寝谨裱褂褚裸裼裨裾裰禊福谩谪谫谬群殿辟障媾嫫媳媲嫒嫉嫌嫁嫔媸叠缙缜缚缛辔缝骝缟缠缡缢缣缤骟剿耥璈静碧瑶璃瑭瑢獒赘熬觏慝嫠韬髦墈墙摽墟墁撂摞嘉摧撄赫截翥踅誓銎摭墉境摘墒摔撇榖撖摺綦聚蔫蔷靺靼鞅靽鞁靿蔌慕暮摹蔓蔑薨蔸蓰蔹蔡蔗蔟蔺戬蔽蕖蔻蓿蔼斡熙蔚鹕兢嘏蓼榛榧模槚槛榻榫槜榭槔榴槁榜槟榨榕槠榷榍歌遭僰酵酽酾酲酷酶酴酹酿酸厮碶\碡碟碴碱碣碳碲磋磁碹碥愿劂臧豨殡需霆霁辕辖辗蜚裴翡雌龇龈睿裳颗夥瞅瞍睽墅嘞嘈嗽嘌嘁嘎暧暝踌踉跽踊蜻蜞蜡蜥蜮蜾蝈蜴蝇蜘蜱蜩蜷蝉蜿螂蜢嘘嘡鹗嘣嘤嘚嘛嘀嗾嘧罴罱幔嶂幢赙罂赚骷骶鹘锲锴锶锷锸锹锻锽锾锵锿镀镁镂镃镄镅舞犒舔稳熏箐箦箧箍箸箨箕箬算箅箩箪箔管箜箢箫箓毓舆僖儆僳僚僭僬劁僦僮僧鼻魄魅魃魆睾艋鄱貌膜膊膈膀膑鲑鲔鲙鲚鲛鲜鲟疑獐獍飗觫雒孵夤馑馒銮裹敲豪膏塾遮麽廙腐瘩瘌瘗瘟瘦瘊瘥瘘瘙廖辣彰竭韶端旗旖膂阚鄯鲞精粼粹粽糁歉槊鹚弊熄熘熔煽熥潢潆潇漤漆漕漱漂滹漫漯漶潋潴漪漉漳滴漩漾演澉漏潍慢慷慵寨赛搴寡窬窨窭察蜜寤寥谭肇綮谮褡褙褐褓褛褊褪禚谯谰谱谲暨屣鹛隧嫣嫱嫩嫖嫦嫚嫘嫜嫡嫪鼐翟翠熊凳瞀鹜骠缥缦缧骡缨骢缩缪缫慧耦耧瑾璜璀璎璁璋璇璆奭撵髯髫撷撕撒撅撩趣趟撑撮撬赭播墦擒撸鋆墩撞撤撙增撺墀撰聩聪觐鞋鞑蕙鞒鞍蕈蕨蕤蕞蕺瞢蕉劐蕃蕲蕰蕊赜蔬蕴鼒槿横樯槽槭樗樘樱樊橡槲樟橄敷鹝豌飘醋醌醇醉醅靥魇餍磕磊磔磙磅碾磉殣慭\震霄霉霈辘龉龊觑瞌瞒题暴瞎瞑嘻嘭噎嘶噶嘲颙暹嘹影踔踝踢踏踟踬踩踮踣踯踪踺踞蝽蝶蝾蝴蝻蝠蝰蝎蝌蝮螋蝗蝓蝣蝼蝤蝙噗嘬颚嘿噍噢噙噜噌嘱噀噔颛幞幡嶓幢嶙嶝墨骺骼骸镊镆镇镈镉镋镌镍镎镏镐镑镒镓镔靠稽稷稻黎稿稼箱箴篑篁篌篓箭篇篆僵牖儇儋躺僻德徵艘磐虢鹞鹟膝膘膛滕鲠鲡鲢鲣鲥鲤鲦鲧鲩鲪鲫鲬橥獗獠觯鹠馓馔熟摩麾褒廛瘛瘼瘪瘢瘤瘠瘫齑鹡凛颜毅羯羰糊糇遴糌糍糈糅翦遵鹣憋熜熵熠潜澍澎澌潵潮潸潭潦鲨潲鋈潟澳潘潼澈澜潽潺澄潏懂憬憔懊憧憎寮窳额谳翩褥褴褫禤谴鹤谵憨熨慰劈履屦嬉勰戮蝥豫缬缭缮缯骣畿耩耨耪璞璟靛璠璘聱螯髻髭髹擀撼擂操熹甏擐擅擞磬鄹颞蕻鞘燕黇颟薤蕾薯薨薛薇檠擎薪薏蕹薮薄颠翰噩薜薅樾橱橛橇樵檎橹橦樽樨橙橘橼墼整橐融翮瓢醛醐醍醒醚醑觱磺磲赝飙殪霖霏霓霍霎錾辙辚臻冀餐遽氅瞟瞠瞰嚄嚆噤暾曈蹀蹅踶踹踵踽嘴踱蹄蹉蹁蹂螨蟒蟆螈螅螭螗螃螠螟噱器噪噬噫噻噼幪罹圜鹦赠默黔镖镗镘镚镛镜镝镞镠氇氆赞憩穑穆穄篝篚篥篮篡簉篦篪篷篙篱盥儒劓翱魉魈邀徼衡歙盦膨膪膳螣膦膙雕鲭鲮鲯鲰鲱鲲鲳鲴鲵鲷鲸鲺鲹鲻獴獭獬邂憝亸鹧磨廨赟癀瘭瘰廪瘿瘵瘴癃瘾瘸瘳斓麇麈凝辨辩嬴壅羲糙糗糖糕瞥甑燎燠燔燃燧燏濑濒濉潞澧澡澴激澹澥澶濂澼憷懒憾懈黉褰寰窸窿褶禧壁避嬖犟隰嬗鹨翯颡缰缱缲缳缴璨璩璐璪戴螫擤壕擦觳罄擢藉薹鞡鞠藏薷薰藐藓藁檬檑檄檐檩檀懋醢翳繄礁礅磷磴鹩霜霞龋龌豳壑黻瞭瞧瞬瞳瞵瞩瞪嚏曙嚅蹑蹒蹋蹈蹊蹓蹐蟥螬螵疃螳螺蟋蟑蟀嚎嚓羁罽罾嶷赡黜黝髁髀镡镢镣镤镥镦镧镨镩镪镫罅穗黏魏簧簌篾簃篼簏簇簖簋繁鼢黛儡鹪鼾皤魍徽艚龠爵繇貘邈貔臌朦臊膻臁臆臃鲼鲽鲾鳀鳁鳂鳃鳄鳅鳆鳇鳈鳉鳊獯螽燮鹫襄糜縻膺癍癌麋辫赢糟糠馘燥懑濡濮濞濠濯懦豁蹇謇邃襕襁臀檗甓臂擘孺隳嬷翼蟊鹬鍪骤鏊鳌鬶鬈鬃瞽藕鞯鞨鞭鞫鞧鞣藜藠藤藩鹲檫檵覆醪蹙礞礓礌燹餮瞿瞻曛颢曜躇蹦鹭蹢蹜蟛蟪蟠蟮嚚嚣鹮黠黟髅髂镬镭镯镰镱馥簠簟簪簦鼫鼬鼩雠艟翻臑鳍鳎鳏鳐鳑鹱鹰癞癔癜癖糨冁蹩瀑瀍瀌鎏懵襟璧戳彝邋鬏攉攒鞲鞴藿蘧孽蘅警蘑藻麓攀醭醮醯礤酃霪霭黼曝嚯蹰蹶蹽蹼蹯蹴蹾蹲蹭蹿蹬蠖蠓蠋蟾蠊巅黢髋髌镲籀簸籁簿鳘齁魑艨鼗鳓鳔鳕鳗鳙鳚蟹颤靡癣麒鏖瓣蠃羸羹鳖爆瀚瀣瀛襦谶襞疆骥缵瓒鬓壤攘馨蘩蘖蘘醵醴霰颥酆耀矍曦躁躅蠕鼍嚼嚷巍巉黩黥镳镴黧籍纂鼯臜鳜鳝鳞鳟獾魔糯灌瀹瀵譬孀骧耰蠢瓘鼙醺礴礳霸露霹颦曩躏黯髓鼱鳡鳢癫麝赣夔爝灏禳鐾羼蠡耲耱懿韂蘸鹳蘼囊霾氍饕躔躐髑镵镶穰鳤瓤饔鬻鬟趱攫攥颧躜罐鼹鼷癯麟蠲矗蠹醾躞衢鑫灞襻纛鬣攮囔馕戆蠼爨齉一
```
